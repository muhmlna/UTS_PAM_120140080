# UTS_Pengembangan Aplikasi Mobile RB

## Identitas :

- Muhammad Maulana
- 120140080
- Teknik Informatika ITERA

## Deskripsi Aplikasi

Aplikasi sederhana berbasis mobile yang menggunakan bahasa React Native serta berfungsi menampilkan produk dari DB Local yang dapat menunjukan produk serta detail dari produk tersebut dengan menggunakan redux. 
Tujuan dibuatnya aplikasi ini adalah untuk mempelajari bagaimana cara membuat app saat menggunakan  bahasa React Native serta state management (redux).

## Library yang digunakan

- @react-navigation/native
- @react-navigation/native-stack
- expo
- expo-status-bar
- react
- react-native
- react-native-safe-area-context
- react-native-screens
- react-redux

## Tampilan Aplikasi

<p align="center">
    <img width="200px" src="./assets/IMG_7926.PNG">
    <img width="200px" src="./assets/IMG_7927.PNG">
    <img width="200px" src="./assets/IMG_7928.PNG">
</p>

## Installation

Run the following command below in project terminal root to build android apk
```
yarn install
```
or
```
npm install
```
&nbsp;
Next is run the same function as git init inside expo
```
npx expo install expo-updates
```
&nbsp;
Build inside expo
```
expo build:android
```
or
```
npm install -g eas-cli
eas build -p android
```
&nbsp;
Then wait and follow the instruction if it the first build, generate a new key and choose apk.Last if expo need login in terminal input same as your expo.dev account
&nbsp;
