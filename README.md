# BetParser WebView

BetParser WebView is an Android application that works tightly coupled with the BetParser Angular WebApp.
The aim of this APK is just to hold the Angular WebApp into an Android WebView. Some features have been implemented to support LocalStorage (user saved preferences), screen flip, apk session saving, and working back button.

## Environment Setup


1) Clone this repo: just use `git clone` to clone this repository to your local machine

2) Install Android Development Kit (ADK) and Android Emulator (if you need debugging on the pc, else you can easily use ADB on you smartphone)


## Android Studio IDE Configuration

Gradle will take care of everything. When building your signed App just create your key store.

## Debugging

1) Add a new Android Run/Debug Configuration pointing to the main activity of the app

2) If you want open the AVD manager and configure an Android emulator
