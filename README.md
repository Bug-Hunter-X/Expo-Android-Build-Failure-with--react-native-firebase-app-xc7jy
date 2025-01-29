# Expo Android Build Failure with @react-native-firebase/app

This repository demonstrates a bug and its solution related to building an Android app using Expo CLI and the `@react-native-firebase/app` package.  The bug manifests as a build failure due to incorrect Firebase project configuration, often related to the `google-services.json` file.  The solution involves verifying the correct placement and content of this file within the Android project structure.

## Bug

The `bug.js` file contains a simplified React Native component utilizing Firebase. Attempting to build the Android version using Expo CLI results in an error because of the misconfiguration.

## Solution

The `bugSolution.js` file demonstrates the corrected setup. It highlights the proper inclusion and configuration of the `google-services.json` file within the Android project directory, ensuring a successful build.