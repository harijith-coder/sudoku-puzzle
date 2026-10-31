# 🧩 Sudoku Puzzle

> A classic Sudoku game for Android with a clean, modern interface, dark/light theme support, and smooth gameplay experience.

[![Android](https://img.shields.io/badge/Platform-Android-green.svg)](https://developer.android.com)
[![Java](https://img.shields.io/badge/Language-Java-orange.svg)](https://www.java.com)
[![API](https://img.shields.io/badge/API-24%2B-brightgreen.svg)](https://android-arsenal.com/api?level=24)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 📖 About

**Sudoku Puzzle** (SudokuZenith) is a native Android Sudoku app built in Java. It features puzzle generation across multiple difficulty levels, a fully-themed UI with Material Design components, sound effects, confetti celebrations on win, and AdMob integration.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🎮 Classic 9×9 Sudoku | Standard Sudoku rules on a clean grid |
| 🎚️ Difficulty Levels | Easy, Medium, and Hard puzzles |
| 🌙 Dark / Light Mode | Toggle themes from Settings — persisted across sessions |
| ⏱️ Game Timer | Optional timer to track solve time |
| ❌ Error Tracking | Up to 3 mistakes allowed per game |
| ↩️ Undo | Revert your last move |
| ✅ Check | Highlights incorrect entries |
| 💡 Solve | Instantly reveals the full solution |
| 🎉 Win Animation | Confetti celebration on puzzle completion |
| 🔊 Sound Effects | Click, error, hint, and win sounds |
| 📢 AdMob Ads | Banner ads integrated on the main screen |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Language | Java |
| Platform | Android (Native) |
| UI | XML Layouts + Material Components |
| Build System | Gradle |
| IDE | Android Studio |
| Ads | Google AdMob (play-services-ads) |
| Animations | Confetti library (jinatonic/confetti) |
| Min SDK | API 24 (Android 7.0) |
| Target SDK | API 34 (Android 14) |

---

## 🗂️ Project Structure

```
sudokuuuu-main/
├── app/
│   └── src/main/
│       ├── java/com/example/sudokuzenith/
│       │   ├── MainActivity.java          # Home screen, difficulty selector, ads
│       │   ├── GameActivity.java          # Core game screen
│       │   ├── GameEndActivity.java       # Win/lose result screen
│       │   ├── SettingsActivity.java      # Theme toggle settings
│       │   ├── SudokuGenerator.java       # Puzzle generation logic
│       │   ├── SoundManager.java          # Audio effects manager
│       │   ├── SudokuZenithApp.java       # Application class
│       │   └── view/
│       │       └── SudokuBoardView.java   # Custom Sudoku grid view
│       ├── res/
│       │   ├── layout/                    # XML layouts for all activities
│       │   ├── drawable/                  # Icons and UI assets
│       │   ├── values/                    # Colors, strings, themes
│       │   ├── values-night/              # Dark mode color overrides
│       │   └── raw/                       # Sound files (click, error, hint, win)
│       └── AndroidManifest.xml
├── build.gradle
├── settings.gradle
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- [Android Studio](https://developer.android.com/studio) (latest stable)
- Git
- Android device or emulator running API 24+

### Installation

1. **Clone the repository**
   ```sh
   git clone https://github.com/harijith-coder/sudoku-puzzle.git
   ```

2. **Open in Android Studio**
   - Go to `File` → `Open`
   - Select the cloned `sudokuuuu-main` folder

3. **Sync & Build**
   - Let Gradle sync automatically
   - Click `Build` → `Rebuild Project`

4. **Run**
   - Select an emulator or connected device
   - Click ▶ **Run**

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create your feature branch
   ```sh
   git checkout -b feature/AmazingFeature
   ```
3. Commit your changes
   ```sh
   git commit -m "Add some AmazingFeature"
   ```
4. Push to the branch
   ```sh
   git push origin feature/AmazingFeature
   ```
5. Open a Pull Request

---

## 🔮 Future Improvements

- [ ] Advanced puzzle generation algorithm (backtracking solver)
- [ ] User statistics — win/loss ratio, best times
- [ ] In-game Hint system
- [ ] More themes and color customization
- [ ] Pencil/notes mode for candidate tracking
- [ ] Puzzle save & resume

---

## ✍️ Authors

- **Manthan** — *Original work* — [Llawliet73](https://github.com/Llawliet73/sudokuuuu.git)
- **Harijith** — *Maintainer* — [harijith-coder](https://github.com/harijith-coder)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">Made with ❤️ for Android</div>
