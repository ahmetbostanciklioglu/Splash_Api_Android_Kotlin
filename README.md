<div align="center">

# 🌊 Splash API — Android Kotlin

**A minimal Jetpack Compose sample showing how to add a modern splash screen with the AndroidX Core SplashScreen API.**

![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-2.0.0-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-BOM%202024.04-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![Material 3](https://img.shields.io/badge/Material%203-6E48AA?style=flat-square&logo=materialdesign&logoColor=white)
![Stars](https://img.shields.io/github/stars/ahmetbostanciklioglu/Splash_Api_Android_Kotlin?style=flat-square&color=6E48AA)
![Last Commit](https://img.shields.io/github/last-commit/ahmetbostanciklioglu/Splash_Api_Android_Kotlin?style=flat-square&color=4776E6)

</div>

## 📖 Overview

Splash API is a small, focused Android sample that demonstrates how to display a launch splash screen using the official [AndroidX Core SplashScreen library](https://developer.android.com/develop/ui/views/launch/splash-screen). The project is built with Kotlin and Jetpack Compose (Material 3) and shows the recommended pattern: install the splash screen in `onCreate`, keep it on screen with a condition, and then hand off to the app content once the app is ready.

The app itself is intentionally simple — after the splash animation completes it renders a basic "Hello Android" Compose UI — so the focus stays entirely on wiring up the splash screen correctly.

## ✨ Features

- 🚀 Uses `androidx.core:core-splashscreen` for a consistent splash experience across Android versions (back to Android 6.0 / API 24).
- 🎨 Splash theme configured in `splash.xml` with a background color, an animated launcher icon, and a 1000 ms animation duration.
- ⏱️ `setKeepOnScreenCondition { ... }` with a `Handler.postDelayed` demonstrates holding and dismissing the splash screen.
- 🧩 Built entirely with Jetpack Compose and Material 3, including edge-to-edge display via `enableEdgeToEdge()`.
- 📦 Modern Gradle setup with the Kotlin DSL and a version catalog (`libs.versions.toml`).

## 📸 Preview

<div align="center">
  <img width="1786" alt="Splash API Android Kotlin screenshot" src="https://github.com/user-attachments/assets/c8e92714-b4a4-4a74-9db1-2d9c4765df29" />
</div>

## 🚀 Getting Started

```bash
git clone https://github.com/ahmetbostanciklioglu/Splash_Api_Android_Kotlin.git
cd Splash_Api_Android_Kotlin
```

Then open the project in **Android Studio**, let it **sync the Gradle files**, select a device or emulator, and press **Run** (Shift + F10) to build and launch the app.

## 📋 Requirements

- Android Studio (Ladybug or newer recommended)
- JDK 11
- Android Gradle Plugin 8.8.0 · Kotlin 2.0.0
- Compile SDK 35 / Target SDK 35 · Minimum SDK 24 (Android 6.0)

## 🧑‍💻 Author

**Ahmet Bostancıklıoğlu** — [@ahmetbostanciklioglu](https://github.com/ahmetbostanciklioglu) · ahmetbostancikli@gmail.com

> ⭐ If this helped you, consider giving the repo a star!
