# Language Translator App

This Android application is a Language Translator integrated with Firebase ML Kit. It provides multilingual text translation capabilities using on-device machine learning models, supports offline translation with automatic model downloads, and offers voice input functionality for ease of use.

---

## Features

- Multilingual support: Translate between languages including English, Afrikaans, Arabic, Bengali, Catalan, Czech, Hindi, and Urdu.
- Voice input: Use speech recognition to convert spoken words into translatable text.
- Offline translation: Automatically downloads and uses Firebase language models for offline operation.
- Intuitive user interface: Language selection spinners, text input, and translate button.
- Real-time feedback: Status updates during model downloads and translation processes.
- User notifications for translation or model download errors.

---

## Prerequisites

- Android Studio installed.
- Android device or emulator with minimum SDK version 24 (Android 7.0 Nougat).
- Firebase project configured with ML Kit.
- Gradle 7.0 or later.

---

## Installation and Usage

1. Clone or download the repository.
2. Open the project in Android Studio.
3. Add your Firebase `google-services.json` file to the `app/` directory.
4. Build the app and run it on a physical device or emulator.
5. Allow microphone access when prompted for voice input.
6. Select source and target languages, enter or speak text, and tap the translate button to view results.

---

## Technology Stack

- Android SDK with Java.
- Firebase ML Kit for Natural Language and Translation.
- Material Design Components for UI.
- Gradle Build System.

---

## Permissions

- INTERNET: Required for downloading Firebase language models and translation services.
- RECORD_AUDIO: Required to capture voice input for speech-to-text.

---

## Project Structure

- `app/src/main/java/com/example/languagetranslatorapp/`: Source code including MainActivity.java.
- `app/src/main/res/`: UI layouts, drawable resources, values.
- `app/src/main/AndroidManifest.xml`: App permissions and activity declarations.
- `app/build.gradle`: Module build configurations and dependencies.

---

## License and Contact

This project is open source and free to use or modify.

For issues, questions, or feedback, please use the repository’s issue tracker.

---
