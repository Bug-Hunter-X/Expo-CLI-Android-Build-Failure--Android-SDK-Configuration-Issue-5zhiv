# Expo CLI Android Build Failure: Android SDK Configuration Issue

This repository demonstrates a common issue encountered when building Android APKs using Expo CLI. The problem stems from an improperly configured or incomplete Android SDK setup, leading to build failures.  This example shows the error and how to troubleshoot it.

## Setup

1. Clone this repository.
2. Ensure you have Node.js and npm (or yarn) installed.
3. Install the required packages: `npm install`
4. Run `expo prebuild` to check your configuration and potentially fix the SDK issues.

## Steps to Reproduce

1. Try to build the Android APK using `expo build:android`.  The build will fail with an error related to the Android SDK.

## Solution

The solution usually involves verifying the correct installation and configuration of the Android SDK, particularly checking paths, build-tools, and NDK.  Refer to the `bugSolution.js` file for potential fixes.