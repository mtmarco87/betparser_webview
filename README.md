# BetParser WebView

BetParser WebView is a lightweight Android application designed to encapsulate the BetParser Angular WebApp within a WebView. This app serves as a bridge to provide a native-like experience for users accessing the BetParser web application on Android devices.

## Key Features

- **WebView Integration**: Displays the BetParser Angular WebApp seamlessly within an Android WebView.
- **LocalStorage Support**: Ensures user preferences and session data are preserved.
- **Screen Orientation Handling**: Supports smooth transitions during screen flips.
- **Session Persistence**: Saves and restores the WebView state during app lifecycle events.
- **Back Button Functionality**: Implements a working back button to navigate within the WebView or exit the app.

## Table of Contents

1. [Environment Setup](#environment-setup)
2. [Android Studio IDE Configuration](#android-studio-ide-configuration)
3. [Debugging](#debugging)
4. [How It Works](#how-it-works)
5. [Permissions](#permissions)
6. [Project Structure](#project-structure)
7. [License](#license)

## Environment Setup

1. **Clone the Repository**  
   Clone this repository to your local machine using the following command:

```bash
git clone https://github.com/mtmarco87/betparser_webview.git
```

2. **Install Android Development Tools**

- Install the Android Development Kit (ADK).
- Install the Android Emulator (if debugging on a PC). Alternatively, you can use ADB to debug directly on your smartphone.

## Android Studio IDE Configuration

1. Open the project in Android Studio.
2. Gradle will automatically handle dependencies and project setup.
3. When building a signed APK, create a keystore for signing the app.

## Debugging

1. Add a new Android Run/Debug Configuration in Android Studio, pointing to the `MainActivity` of the app.

2. If needed, open the AVD Manager in Android Studio to configure and launch an Android emulator for testing.

## How It Works

The app loads the BetParser Angular WebApp into a WebView. It enables JavaScript and DOM storage for a smooth user experience. The app also handles lifecycle events to save and restore the WebView state, ensuring continuity for the user.

## Permissions

The app requires the following permission:

- **Internet Access**: To load the BetParser Angular WebApp.

## Project Structure

- **MainActivity.java**: Contains the core logic for initializing and managing the WebView.
- **res/layout/activity_main.xml**: Defines the layout with a full-screen WebView.
- **res/values/**: Contains app resources like strings, colors, and styles.
- **AndroidManifest.xml**: Configures app permissions and declares the main activity.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
