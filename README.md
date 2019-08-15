#New lib R2K

##input gradle
Added in dependencies in AndroidStudio build.gradle

//build.gradle
allprojects {
    repositories {
        jcenter()
        maven { url 'https://jitpack.io' }
    }
}
 dependencies {
    implementation 'com.github.speedatag:uhf:+'
    api 'com.github.SpeedataG:Device:1.6.8'
    
  }
##Low battery
*A battery charge of ≤15% will stop using UHF.
