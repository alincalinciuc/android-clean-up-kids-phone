# Clean up your kids Android phones easy and fast without losing data

### Enable debug mode 
Go to Settings > About Phone > Software Information > Build Number (click on it multiple times)

Go to Settings > Developer Options > USB debugging (turn it on)

### Connect Phone the phone to your PC, Allow Connection

### Download ADB for mac/windows/linux and unzip it

> https://dl.google.com/android/repository/platform-tools-latest-darwin.zip

### Go to the root directory of the archive content
`cd platform-tools`

### Confirm that you device is connected
`./adb devices`

### Get list of all 3rd party installed packages
`./adb shell "pm list packages -3`

### Uninstall apps that you don't need (here you can be creative and use a text editor to multiplicate the following command for all the packages you don't need)
`./adb shell "pm uninstall com.vd.fortskingene.three"`
