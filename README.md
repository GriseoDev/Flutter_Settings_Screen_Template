# Flutter Settings Screen Template

A clean, reusable Settings Screen UI built with Flutter and Material 3.
Designed to be easily integrated into any Flutter app without enforcing a specific architecture.

This template focuses on structure, layout, and best practices for common app settings.

---

## Features

- Material 3 design
- Sectioned settings layout
- Toggle switches and navigation rows
- Destructive actions (for example logout, delete account)
- Optional example dark mode toggle
- No third-party UI packages
- No external state management
- Clean, readable widget structure

---

## Included Settings (UI placeholders)

General
- Language
- Notifications
- Sound effects

Appearance
- Dark mode (example implementation)
- Use system theme
- Text size

Account
- Change password
- Privacy settings
- Delete account

About
- App version
- Licenses
- Open source notices

Actions
- Logout

All settings are implemented as UI placeholders or callbacks and can be adapted to your app logic.

---

## Dark Mode Example

The dark mode toggle is implemented as a simple, local example using ThemeMode.
It is intended for demonstration purposes only and can be extended or removed depending on your app architecture.
No persistence or global state is enforced.

---

## Folder Structure

lib/
 └── settings/
     └── settings_screen.dart

---

## Integration

1. Copy the `settings_screen.dart` file into your project.
2. Import the `SettingsScreen` widget where needed.
3. Connect callbacks or navigation logic to match your app.

Example:

Navigator.of(context).push(
  MaterialPageRoute(
    builder: (_) => const SettingsScreen(),
  ),
);

---

## Screenshots

![Light Mode](screenshots/settings_light_1.png)

![Dark Mode](screenshots/settings_dark_1.png)

![Account Section](screenshots/settings_light_2.png)

---

## License

This repository is for preview and demonstration purposes.

The full template, including commercial usage rights and future updates,
is available on Gumroad.

---

## Bundle

This template is part of the Flutter Starter UI Bundle, which includes multiple reusable Flutter UI templates at a discounted price.
