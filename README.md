# 🚀 flutter_application 🚀

This project is a sample application for the **FlutterKaigi2025** demo. 🧑‍💻

## 🐦 Flutter Version Management

This project uses [FVM](https://fvm.app/) to manage the Flutter SDK version.
To use the correct Flutter version for this project, please make sure you have FVM installed and run the following command:

```bash
fvm use
```

## ⚠️ Important Points

Please be aware of the following points:

- **iOS Physical Device Debugging:**
  - It has been confirmed that debug mode **does not work** correctly with `Flutter 3.32.8` on an `iOS 26.1` physical device.
  - ✅ Debug mode works correctly with `Flutter 3.35.7`.
  - If you face this issue, please switch your Flutter version using the following command:
    ```bash
    fvm use 3.35.7
    ```

## 🏁 Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.