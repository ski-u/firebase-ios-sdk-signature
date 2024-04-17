## Issue

The signatures can't be verified with firebase-ios-sdk v10.24.0 using [akaffenberger/firebase-ios-sdk-xcframeworks](https://github.com/akaffenberger/firebase-ios-sdk-xcframeworks)

<img width="2032" alt="Screenshot 2024-04-17 at 14 27 01" src="https://github.com/ski-u/firebase-ios-sdk-signature/assets/37182704/5602c3a2-d08b-44e2-87c4-207be379f7bf">

## Directories
- There is the same minimum project in both directories

### `firebase-ios-sdk-xcframeworks`
- Using [`akaffenberger/firebase-ios-sdk-xcframeworks`](https://github.com/akaffenberger/firebase-ios-sdk-xcframeworks), we can't build the app and have errors :thinking:

### `firebase-ios-sdk`
- Using [`firebase/firebase-ios-sdk`](https://github.com/firebase/firebase-ios-sdk) directly, we can build the app :ok:
