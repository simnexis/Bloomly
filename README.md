<div align="center">

# 🌸 Bloomly

### *Aesthetic Task Management & Mindful Productivity Built with Jetpack Compose & Material 3*

[![Platform: Android](https://img.shields.io/badge/Platform-Android-34A853?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com/)
[![Kotlin](https://img.shields.io/badge/Kotlin-2.2-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-Material%203-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)](https://developer.android.com/jetpack/compose)
[![Storage: DataStore](https://img.shields.io/badge/Storage-DataStore%20Persistent-FBBC04?style=for-the-badge)](https://developer.android.com/topic/libraries/architecture/datastore)
[![License: MIT](https://img.shields.io/badge/License-MIT-E91E63?style=for-the-badge)](LICENSE)

> **Designed to help your goals bloom through calm, pastel aesthetics, fluid gesture interactions, and persistent task analytics.**

</div>

---

## ✨ Core Highlights

- 🌸 **Bespoke Pastel Design System**: Crafted with Material Design 3 dynamic tokens, soft elevation, and custom Quicksand typography.
- 🌙 **System & Dynamic Theming**: Seamless instant switching between daylight pastel and battery-conserving luxury dark mode.
- 👆 **Fluid Gesture Micro-Interactions**: Single-tap completion toggles, double-tap in-place editing, and long-press haptic deletion.
- 📌 **Priority Pinning & Focus**: Pin critical daily milestones to lock them at the top of the viewport.
- 🔥 **Daily Streak Engine**: Tracks consecutive productive days to cultivate positive habit loops.
- 📊 **Real-time Analytics Dashboard**: Live completion percentage rings and task distribution statistics.
- 💾 **Reactive Persistence**: Android Preferences DataStore with Kotlin Coroutines Flow for zero-lag offline persistence.

---

## 📱 Visual Showcase

<div align="center">

| 🌸 Daylight Mode | 🌙 Night Dark Mode | 📊 Live Analytics |
| :---: | :---: | :---: |
| <img src="screenshots/lightmode.jpg" width="240" alt="Light Mode"> | <img src="screenshots/darkmode.jpg" width="240" alt="Dark Mode"> | <img src="screenshots/statistics.jpg" width="240" alt="Statistics"> |

| 📌 Pinning & Management | 📝 Task Workflow |
| :---: | :---: |
| <img src="screenshots/deletion.jpg" width="240" alt="Pinning and Deletion"> | <img src="screenshots/tasks.jpg" width="240" alt="Task Management"> |

</div>

---

## 🎮 Intuitive Gesture Controls

| Gesture | Interaction |
| :--- | :--- |
| **👆 Single Tap** | Toggle task completion state with animated strikethrough |
| **✏️ Double Tap** | Trigger immediate inline task title and note editing modal |
| **🗑️ Long Press** | Safely delete task with confirmatory visual feedback |
| **📌 Pin Icon** | Anchor priority objectives to the top of your stream |
| **🌙 Theme Switch** | Seamless toggle between Light Pastel and Deep Slate Dark |
| **📊 Dashboard Tab** | View real-time completion telemetry and streak metrics |

---

## 🏗️ Architecture & Tech Stack

```text
com.simran.bloomly/
├── data/
│   ├── TaskPreferences.kt      # DataStore proto / key-value persistence
│   └── TaskRepository.kt       # Flow-based reactive state emission
├── ui/
│   ├── theme/                  # Material 3 typography, color schemes, shapes
│   ├── components/             # Reusable animated task cards, progress rings
│   ├── screens/
│   │   ├── HomeScreen.kt       # Main active task viewport
│   │   └── StatsScreen.kt      # Historical productivity analytics
│   └── navigation/             # Navigation Compose route graphs
└── viewmodel/
    └── TaskViewModel.kt        # StateFlow UI state management & business logic
```

- **Kotlin 2.2**
- **Jetpack Compose + Material 3**
- **Android Jetpack DataStore** (Reactive asynchronous persistence)
- **Navigation Compose**
- **StateFlow & Kotlin Coroutines**

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/simnexis/Bloomly.git
cd Bloomly
```

### 2. Open in Android Studio
1. Launch **Android Studio** (Ladybug / Iguana or newer recommended).
2. Select **Open** and select the cloned `Bloomly` folder.
3. Allow Gradle to sync dependencies automatically.

### 3. Run on Device / Emulator
- Select an Android device or emulator running **API 26 (Android 8.0) or higher**.
- Click **Run (`Shift + F10`)**.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) © 2026 Simran Gupta ([@simnexis](https://github.com/simnexis)).
