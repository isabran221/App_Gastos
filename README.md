# kitty

# 🧾🪙 Flutter Expense Management App

**Developed by Fredy and Isaac**

A simple Flutter app to manage expenses. A pet project to improve skills and learn new features.
I had several technical tasks:

## ⚡ Tasks
1. Due to given UI kit create prototype describing all features.
2. Add translations (ukr, eng).
3. Authentication should be on user's device with the usage of biometrics if supported. Otherwise use pin code.
4. All data should be stored locally in SQlite DB.
5. Despite all data is stored locally, implement multiuser feature.
6. Use freezed and json_serializable packages for for data-classes and pattern-matching.

## ⚡ Features
- [x] All data stored on user's device.
- [x] Create notes of user's income and expense.
- [x] Count balance from the first note to the selected period.
- [x] Full statistics monthly report with Export to pdf feature.
- [x] Expense categories management: create, edit, change order.
- [x] Authentication with fingerprint, FaceId or pin code.
- [x] All users' data is encrypted and stored locally.
- [x] Search transaction by its title or filter by category.
- [x] Supports Ukrainian and English.
- [x] El proyecto cuenta con su propia documentación detallada.

## ⚡ Platforms
🤖 Android
 iOS

## 🔌 Plugins
| Name | Usage |
|---|---|
| [**Flutter BLoC**](https://pub.dev/packages/flutter_bloc) | State Management |
| [**SQflite**](https://pub.dev/packages/sqflite) | SQL database to store data |
| [**Flutter SVG**](https://pub.dev/packages/flutter_svg) | Draw SVG files |
| [**Json Serializable**](https://pub.dev/packages/json_serializable) | Handling JSON |
| [**Freezed**](https://pub.dev/packages/freezed) | Code generator for data-classes/unions/pattern-matching/cloning. |
| [**Local Auth**](https://pub.dev/packages/local_auth) | Provides means to perform local, on-device authentication of the user. |
| [**Flutter Screen Lock**](https://pub.dev/packages/flutter_screen_lock#flutter-screen-lock) | Provides an feature for screen lock. |
| [**Page Transition**](https://pub.dev/packages/page_transition) | Gives beautiful page transition. |
| [**pdf**](https://pub.dev/packages/pdf) | A pdf producer for Dart. It can create pdf files for both web or flutter. |
| [**Flutter Secured Storage**](https://pub.dev/packages/flutter_secure_storage) | Secure Storage provides API to store data in secure storage. |
| [**Easy Localization**](https://pub.dev/packages/easy_localization) | Localizes app |

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
