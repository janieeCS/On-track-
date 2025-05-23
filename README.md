# On-Track#

An Android productivity app built with Flutter for managing tasks, notes, and user profiles.

## Features

- User Accounts: Sign up, log in/out, edit profile, change password, set profile picture.
- Task Management: Create, edit, delete, and complete tasks with priorities, categories, notes, and comments.
- Reminders & Views: Set due dates/times, get local notifications, view tasks on a calendar, and see top 3 tasks in a widget.
- Sharing: Share tasks via email with other users.
- Customization & UI: Various theme colors, responsive Android interface.
- Data Handling: Uses SharedPreferences to save user data.


## Getting Started

### Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install)
- [Dart SDK](https://dart.dev/get-dart)
- Android Studio or Visual Studio Code

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/janieeCS/On-track-/releases/tag/v1.0.0%2B1
   cd ontrackapp
   ```

2. **Install dependencies:**
   ```sh
   flutter pub get
   ```

3. **Run the app on Android (using Simulator):**
   ```sh
   flutter run
   ```



## Project Structure

- `lib/` - source code (UI, providers, models)
- `assets/` - Images and other assets
- `android/` - Android platform-specific code

## Customization

- Update app name, icons, and theme in `pubspec.yaml` and the `android/` folder.
- Modify UI and logic in the `lib/` directory.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Author

- Jane Pauleen Gregori

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

For more Flutter resources, see the [official documentation](https://docs.flutter.dev/).

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
