## Issue

The signatures can't be verified with firebase-ios-sdk v10.24.0 using [akaffenberger/firebase-ios-sdk-xcframeworks](https://github.com/akaffenberger/firebase-ios-sdk-xcframeworks)

<img width="2032" alt="Screenshot 2024-04-17 at 14 27 01" src="https://github.com/ski-u/firebase-ios-sdk-signature/assets/37182704/5602c3a2-d08b-44e2-87c4-207be379f7bf">

## Directories
- There is the same minimum project in both directories
- All firebase package products has added to each target

<img width="1512" alt="Screenshot 2024-04-17 at 14 14 44" src="https://github.com/ski-u/firebase-ios-sdk-signature/assets/37182704/f83d2320-f838-4755-ab6f-411149e21e3e">

### `firebase-ios-sdk-xcframeworks`
- Using [`akaffenberger/firebase-ios-sdk-xcframeworks`](https://github.com/akaffenberger/firebase-ios-sdk-xcframeworks), we can't build the app and have errors :thinking:

https://github.com/ski-u/firebase-ios-sdk-signature/assets/37182704/1f944fc6-35e2-40a9-90e5-8d5d5a6d2936

### `firebase-ios-sdk`
- Using [`firebase/firebase-ios-sdk`](https://github.com/firebase/firebase-ios-sdk) directly, we can build the app :ok:

https://github.com/ski-u/firebase-ios-sdk-signature/assets/37182704/e21905e0-2383-445a-b6b8-26de2ec5d644

## Environment

```
❯ swift --version
swift-driver version: 1.90.11.1 Apple Swift version 5.10 (swiftlang-5.10.0.13 clang-1500.3.9.4)
Target: arm64-apple-macosx14.0
```

```
❯ xcodebuild -version
Xcode 15.3
Build version 15E204a
```
