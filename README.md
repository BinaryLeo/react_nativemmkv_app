
<div align="center" style="margin: 20px; text-align: center">

[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](https://github.com/BinaryLeo/react_native_mmkv_app/blob/main/LICENSE)
![GitHub last commit](https://img.shields.io/github/last-commit/BinaryLeo/react_native_mmkv_app?style=flat-square)
![GitHub top language](https://img.shields.io/github/languages/top/BinaryLeo/react_native_mmkv_app?style=flat-square)
![Warning badge](https://img.shields.io/badge/we%27re%20working%20here-wait-red?style=flat-square&logo=warning)
[![BinaryLeo badge](https://img.shields.io/badge/A%20project%20by%20BinaryLeo-2A2D34?style=flat-square&logo=Font-Awesome)](https://github.com/BinaryLeo)




</div>

This is a project that demonstrates the use of [MMKV](https://github.com/mrousavy/react-native-mmkv) , a key-value storage framework for React Native applications. With MMKV, we can easily store and retrieve user information and pre-populate their credentials in the sign-in form. This is achieved through the "allow auto-signIn" option, which automatically provides the user's stored credentials to the input  "username" and "password" fields.

One of the major advantages of MMKV over other storage solutions like AsyncStorage is its support for synchronous operations. This allows for greater flexibility in managing data storage needs, especially in cases where data needs to be immediately persisted before proceeding to the next step in a process. MMKV's efficient C++ implementation ensures that performance is not compromised even with synchronous operations, making it a great option for React Native developers. According to the official documentation, MMKV is around 30 times faster than AsyncStorage.
#### Dependencies and command line options

```bash
expo install react-native-mkv
yarn add react-native-paper
yarn add react-native-safe-area-context
yarn add react-native-vector-icons
```

```bash
expo prebuild
npx expo run:android
```
