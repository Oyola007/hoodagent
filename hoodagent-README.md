# 🤖 HoodAgent

An **AI-powered task and reminder app** for Android, built with Flutter. Type what you need to do in plain language, and HoodAgent uses the Claude API to turn it into a structured task, then reminds you with local notifications.

## ✨ Features

- **Natural-language tasks:** write something like "remind me to call the supplier tomorrow at 3pm" and the app extracts the task, date and time for you
- **Claude API parsing:** the Claude API converts free-text input into structured task data
- **Local notifications:** reminders are delivered on the device, with no extra server needed
- **Personal task management:** keep your tasks and reminders in one place

## 🛠 Tech stack

| Area | Tools |
|---|---|
| Framework | Flutter (Dart) |
| Platform | Android |
| AI | Anthropic API (Claude) |
| Reminders | Local notifications |

## 🚀 Run it locally

1. Install [Flutter](https://docs.flutter.dev/get-started/install) and set up an Android emulator or a physical device.
2. Clone this repository and open the folder:
   ```bash
   git clone https://github.com/Oyola007/hoodagent.git
   cd hoodagent
   ```
3. Install the dependencies:
   ```bash
   flutter pub get
   ```
4. Find the line in the code under `lib` that holds `YOUR_API_KEY_HERE` and replace it with your own Anthropic API key from [console.anthropic.com](https://console.anthropic.com).
5. Run the app:
   ```bash
   flutter run
   ```

> **Security note:** a key stored inside a mobile app can be extracted from the app. This project is a prototype. For a real release, send the requests through your own backend server so the key stays private.

## 📸 Screenshots

_Add screenshots of the task input screen and the reminder list here._

## 👤 Author

**Evans Omondi Oyola**: BSc ICT graduate, Kenya
[GitHub](https://github.com/Oyola007) · [Portfolio](https://oyola007.github.io) · evansomondi392@gmail.com
