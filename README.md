![App Screenshot](https://i.imgur.com/KyKiNqX.png)

## Discover multiple methods to simultaneously run APPIUM and AVD
[![GitHub Actions - Ubuntu](https://img.shields.io/badge/GitHub_Actions-Ubuntu-purple?style=for-the-badge)](https://github.com/fahleiro/appium-avd/blob/develop/.github/workflows/action-ubuntu.yml)


# ADB commands

## Get package and main activity
```
adb shell dumpsys package | grep fahleiro
```
## Stop package
```
adb shell am force-stop fahleiro.apk.tests
```

