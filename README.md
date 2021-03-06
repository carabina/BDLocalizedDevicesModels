# BDLocalizedDevicesModels
Apple product names localized.

[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)
![Xcode 9.0+](https://img.shields.io/badge/Xcode-9.0%2B-blue.svg)
![iOS 9.0+](https://img.shields.io/badge/iOS-9.0%2B-blue.svg)
![tvOS 9.0+](https://img.shields.io/badge/tvOS-9.0%2B-blue.svg)
![Swift 4.0+](https://img.shields.io/badge/Swift-4.0%2B-orange.svg)

## Installation
### Carthage

[Carthage](https://github.com/Carthage/Carthage) is a decentralized dependency manager that builds your dependencies and provides you with binary frameworks.

You can install Carthage with [Homebrew](http://brew.sh/) using the following command:

```bash
$ brew update
$ brew install carthage
```

To integrate BDLocalizedDevicesModels into your Xcode project using Carthage, specify it in your `Cartfile`:

```ogdl
github "bixcorp/BDLocalizedDevicesModels"
```
## Usage
Note: To use a localization included in the framework bundle, the app using the framework must support this localization.
### Localized product name
Swift
```swift
UIDevice.current.localizedProductName
```

Objective-C
```objc
[UIDevice currentDevice].localizedProductName;
```

### English product name
Swift
```swift
UIDevice.current.productName
```

Objective-C
```objc
[UIDevice currentDevice].productName;
```
