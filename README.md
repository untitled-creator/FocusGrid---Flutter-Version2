# FocusGrid - Reminder Planner

This project is a Flutter reminder and productivity app designed for managing personal tasks, upcoming deadlines, and daily planning.

## Project overview

FocusGrid includes:
- a monthly calendar dashboard
- reminder creation and editing
- task completion tracking
- reminder filtering by date
- smart suggestions and analytics
- local notifications for reminder alerts
- persistent storage using local device data

## Requirements

Before launching the app, install Flutter and ensure the Flutter SDK is available in your terminal.

Recommended setup:
- Flutter SDK
- Android Studio or VS Code with Flutter extension
- A device emulator or connected device

## How to launch the app

From the project folder, run:

```bash
flutter pub get
flutter run
```

### If you want to run in a specific browser/device

```bash
flutter devices
flutter run -d chrome
```

For Android emulator:

```bash
flutter run -d emulator-5554
```

## If the app does not build

Try this sequence:

```bash
flutter clean
flutter pub get
flutter run
```

## Submission note

This export was cleaned to remove generated build folders and temporary cache files so the project is safer and easier to submit.

## Important

- Do not upload the build or cache folders to submission systems.
- Keep the project folder and pubspec.yaml intact.
- If Flutter is not installed, install it first from the official Flutter website.

## App use summary

1. Open the app and view the calendar dashboard.
2. Tap a date to add or review reminders for that day.
3. Use the add reminder screen to create a new reminder.
4. Mark tasks as complete from the reminder list.
5. View analytics and suggestion insights from the progress screen.

## Project structure

- lib/ - app logic and UI
- android/ - Android project files
- ios/ - iOS project files
- windows/ - Windows project files
- web/ - web build files
- test/ - automated app tests

## Support

This app is intended for local use and demonstration. It stores reminders locally on the device and uses local notification support where available.
