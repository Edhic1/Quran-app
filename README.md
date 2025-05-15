# QuranApp

**QuranApp** is an Android application designed to provide a seamless experience for reading, searching, and studying the Quran. With features like multiple translations, audio recitations, and bookmarking, it aims to make the Quran accessible and engaging for users worldwide.

---

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)
- [Screenshots](#screenshots)
- [Roadmap](#roadmap)
- [FAQ](#faq)

---

## Features

- **Reading**: Navigate through all 114 Surahs and their Ayahs with a user-friendly interface.
- **Search**: Quickly find verses using keywords or phrases.
- **Audio Recitations**: Listen to high-quality recitations for each verse.
- **Bookmarks**: Save verses for easy access later.
- **Multiple Translations**: Switch between translations in various languages.
- **Night Mode**: Enable a dark theme for comfortable reading in low light.
- **Accessibility**: Adjustable font sizes and text-to-speech for visually impaired users.

---

## Prerequisites

To build and run QuranApp, ensure you have the following installed:

- **Android Studio**: Version 2023.3.1 or later (e.g., Koala).
- **JDK**: Version 17 or later.
- **Android SDK**: API Level 21 (Lollipop) or higher.
- **Git**: For cloning the repository.
- An Android device or emulator running Android 5.0 (API 21) or higher.

---

## Installation

Follow these steps to set up and run the project in Android Studio:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/QuranApp.git
   ```

2. **Open the project**:
   - Launch Android Studio.
   - Select `File > Open` and navigate to the `QuranApp` folder.

3. **Sync the project**:
   - Click `Sync Project with Gradle Files` in Android Studio to download dependencies.
   - Ensure you have an active internet connection for Gradle to fetch libraries.

4. **Build and run**:
   - Connect an Android device or start an emulator.
   - Click `Run > Run 'app'` to build and install the app on your device/emulator.

**Note**: If you encounter build issues, check the `build.gradle` files for compatibility with your Android Studio version.

---

## Usage

- **Reading the Quran**: Select a Surah from the home screen. Scroll or tap to view Ayahs.
- **Searching**: Use the search bar to find verses by entering keywords.
- **Audio Recitations**: Tap the play button next to a verse to listen to its recitation.
- **Bookmarks**: Long-press a verse to bookmark it. View bookmarks in the dedicated tab.
- **Translations**: Change the translation language in the settings menu.
- **Night Mode**: Toggle night mode in settings for a dark theme.

---

## Contributing

We welcome contributions to improve QuranApp! To contribute:

1. Fork the repository.
2. Create a new branch for your changes (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m "Add feature-name"`).
4. Push to your branch (`git push origin feature-name`).
5. Open a pull request with a detailed description.

Please review our [Contributing Guidelines](CONTRIBUTING.md) and adhere to the [Code of Conduct](CODE_OF_CONDUCT.md) to maintain a respectful community.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

For support, feedback,or questions, please:

- Open an issue on [GitHub](https://github.com/Edhic1/QuranApp/issues).
- Email us at edhicham1@gmail.com.

---

## Acknowledgments

- **Quran Text**: Sourced from [Trusted Quran Source](https://example.com).
- **Translations**: Provided by [Translator Name](https://example.com).
- **Audio Recitations**: Courtesy of [Reciter Name](https://example.com).
- **Libraries**:
  - [Retrofit](https://square.github.io/retrofit/) for API calls.
  - [Room](https://developer.android.com/jetpack/androidx/releases/room) for local database storage.

---

## Screenshots

| Home Screen | Search Feature | Audio Playback |
|-------------|----------------|----------------|
| ![Home Screen](screenshots/home.png) | ![Search Feature](screenshots/search.png) | ![Audio Playback](screenshots/audio.png) |

---

## Roadmap

Future enhancements for QuranApp include:

- Support for additional translations and languages.
- Offline access to downloaded Surahs and recitations.
- Integration with prayer time notifications.
- Enhanced search by Juz or topic.

---

## FAQ

**Q: Why is the audio not playing?**  
A: Ensure your device is not in silent mode and you have an active internet connection. Check the app’s permissions for internet access.

**Q: How do I switch translations?**  
A: Navigate to the settings menu and select your preferred translation from the dropdown.

**Q: Does the app work offline?**  
A: Some features, like audio recitations, require an internet connection. Offline support is planned for future releases.

---

### Additional Notes

- **Cultural Sensitivity**: QuranApp is built with deep respect for the Quran’s sanctity. All text and translations are sourced from verified and reputable providers.
- **Data Sources**: The Quran text follows the Uthmani script, with translations from certified scholars.
- **Accessibility**: The app supports text-to-speech and adjustable font sizes to ensure inclusivity for all users.
