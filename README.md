# expo-ads-facebook

> Source code for the deprecated expo-ads-facebook package. This module is removed from Expo SDK in SDK 46. There will be no replacement that works with the classic build service (`expo build`) because [the classic build service has been superseded by **EAS Build**](https://blog.expo.dev/turtle-goes-out-to-sea-d334db2a6b60). With **EAS Build** and [Development Builds](/development/introduction.md), you should use [react-native-fbads](https://github.com/callstack/react-native-fbads) instead.

Facebook Audience SDK integration

# API documentation

- [Documentation for the main branch](https://github.com/expo/expo/blob/main/docs/pages/versions/unversioned/sdk/facebook-ads.md)
- [Documentation for the latest stable release](https://docs.expo.dev/versions/latest/sdk/facebook-ads/)

# Installation in managed Expo projects

For [managed](https://docs.expo.dev/versions/latest/introduction/managed-vs-bare/) Expo projects, please follow the installation instructions in the [API documentation for the latest stable release](https://docs.expo.dev/versions/latest/sdk/facebook-ads/).

# Installation in bare React Native projects

For bare React Native projects, you must ensure that you have [installed and configured the `expo` package](https://docs.expo.dev/bare/installing-expo-modules/) before continuing. You will also need to follow [Facebook's Get Started guide](https://developers.facebook.com/docs/audience-network/get-started).

### Add the package to your npm dependencies

```
expo install expo-ads-facebook
```

### Configure for iOS

Run `npx pod-install` after installing the npm package.

Add `NSUserTrackingUsageDescription` key to your `Info.plist`:

```xml
<key>NSUserTrackingUsageDescription</key>
<string>This identifier will be used to deliver personalized ads to you.</string>
```

Add the required `SKAdNetworkIdentifier` items to your `Info.plist`: [Facebook SKAdNetwork](https://developers.facebook.com/docs/SKAdNetwork).

### Configure for Android

No additional set up necessary.

# Contributing

Contributions are very welcome! Please refer to guidelines described in the [contributing guide](https://github.com/expo/expo#contributing).
