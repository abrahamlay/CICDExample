fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew install fastlane`

# Available Actions
## Android
### android test
```
fastlane android test
```
Runs all the tests
### android build_dev
```
fastlane android build_dev
```
Build APK with Development Environment
### android beta
```
fastlane android beta
```
Submit a new Beta Build to Crashlytics Beta
### android deploy_to_firebase
```
fastlane android deploy_to_firebase
```
Deploy to Firebase App Distribution
### android build_prod
```
fastlane android build_prod
```
Build APK With Production Environment
### android deploy_to_internal_test
```
fastlane android deploy_to_internal_test
```
Deploy to Play Store Internal Test

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
