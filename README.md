<img src="https://raw.githubusercontent.com/CDH-Studio/Kalend/dev/src/assets/img/dark_logo.png" alt="Kalend" width="300"/>

[![CircleCI](https://img.shields.io/circleci/project/github/CDH-Studio/Kalend/master.svg?style=flat&logo=circleci)](https://circleci.com/gh/CDH-Studio/Kalend)
[![Release Version](https://img.shields.io/github/release/CDH-Studio/Kalend.svg?style=flat)](https://github.com/CDH-Studio/Kalend/releases)
![](https://img.shields.io/github/license/CDH-Studio/Kalend.svg?style=flat)

For more information please go and see our [wiki](https://github.com/CDH-Studio/Kalend/wiki)

## React Native Modules

* React Native Vector Icons
  * https://github.com/oblador/react-native-vector-icons
* React Native Paper
  * https://github.com/callstack/react-native-paper
* React Native Google SignIn
  * https://github.com/react-native-community/react-native-google-signin
* React Native Linear Gradient
  * https://github.com/react-native-community/react-native-linear-gradient
* React Navigation
  * https://reactnavigation.org/en/
* React Native Datepicker
  * https://github.com/xgfe/react-native-datepicker
* React Native App Intro Sliders
  * https://github.com/Jacse/react-native-app-intro-slider
* React Native Numeric Input
  * https://www.npmjs.com/package/react-native-numeric-input
* Jest
  * https://jestjs.io/docs/en/tutorial-react-native
* React Native Camera
  * https://github.com/react-native-community/react-native-camera
* React Native Firebase
  * https://rnfirebase.io/
* React Native Simple Radio Button
  * https://www.npmjs.com/package/react-native-simple-radio-button
* Redux
  * https://redux.js.org/
* Redux Persist
  * https://github.com/rt2zz/redux-persist

## Dependencies

Below is a list of dependencies to run our project, you can either install all of the manually or run the PowerShell script.

* yarn
* node.js
* Java JDK
* Python 2
* React Native
* Android Studio (for Android testing)
* Android SDK (for Android testing, needed for React Native)
  * Android SDK Platform 28
  * Android SDK Build-Tools 28.0.3
  * Sources for Android 28
  * Intel x86 Emulator Accelerator (HAXM installer)
* Android SDK (for Android testing, needed for React Native Google Sign In)
  * Google APIs 23
  * Google APIs 22
  * Android SDK Platform 23
  * Android SDK Platform 22
  * Android SDK Build-Tools 27.0.3
  * Android SDK Build-Tools 28.0.3
  * Google Play services
  * Google Repository
  * Android Support Repository
  * Android SDK Tools
  * Android SDK Platform-Tools

### Automatic install

Located at the root of this project, there is a file called *setup.ps1*. To install via the script:

1. Open a PowerShell window with Administrator privileges.
2. Run this command to be able to run the PowerShell script. Then enter **a** when asked for an input.
```
Set-ExecutionPolicy RemoteSigned
```
3. Run this command to run the script. Follow the instructions displayed in PowerShell when running the script
```
.\script.ps1
```


## To have the app running

1. Clone the repo

```
cd Kalend
yarn install
```

```
cd into server folder
run yarn install
```

## To start server:
inside server folder run node server.js

## If Jest testing isn't working, do these steps:
1. npm i -D babel-core@bridge

2. Change .babelrc to babel.config.js

3. Overwrite the babel.config.js content with this:
```
module.exports = {
	presets: ['module:metro-react-native-babel-preset']
};
```
