# HelloAndroidUI
📱 HelloAndroidUI

A simple Android application built using Kotlin and XML UI. The project includes a custom splash screen, improved UI layouts, and navigation between activities.

🚀 Features
🔹 Custom Splash Screen

Added SplashScreenActivity and AppSplashActivity

Displays branded UI before navigating to the main screen

Includes drawable backgrounds:

splash_background.xml

plash_background.xml (fixed version)

🔹 Modern UI Layouts

Updated activity_main.xml

Improved themes in themes.xml

Added:

activity_splash.xml

activity_app_splash.xml

🔹 Activity Navigation

Includes:

MainActivity

SecondActivity

SplashScreenActivity

AppSplashActivity

🔹 Updated Manifest

Properly registered all activities

Defined splash screen as launcher activity

📁 Project Structure
HelloAndroidUI/
│
├── app/
│   ├── src/main/
│   │   ├── java/com/example/helloandroidui/
│   │   │   ├── MainActivity.kt
│   │   │   ├── SecondActivity.kt
│   │   │   ├── SplashScreenActivity.kt
│   │   │   ├── AppSplashActivity.kt
│   │   │
│   │   ├── res/
│   │   │   ├── layout/
│   │   │   │   ├── activity_main.xml
│   │   │   │   ├── activity_splash.xml
│   │   │   │   ├── activity_app_splash.xml
│   │   │   ├── drawable/
│   │   │   │   ├── splash_background.xml
│   │   │   │   ├── plash_background.xml
│   │   │   ├── values/
│   │   │       ├── themes.xml
│   │   ├── AndroidManifest.xml
│   │
│   ├── build.gradle.kts
│
├── gradle/libs.versions.toml
└── README.md

🛠️ Tech Stack

Kotlin

Android XML

Jetpack Components

Gradle (KTS)

▶️ How to Run

Clone the repo:

git clone https://github.com/your-username/HelloAndroidUI.git


Open in Android Studio

Let Gradle sync

Run the application on an emulator or device

🏗️ Future Improvements

Add Jetpack Compose UI

Add animations to splash screens

Add multiple screens with clean navigation

Improve theme for dark mode

Improved UI Screenshots
![WhatsApp Image 2025-12-07 at 09 41 53](https://github.com/user-attachments/assets/e0055450-3b3e-42cb-bf4b-f37d61d01878)

