# Picsum BLoC App

A Flutter example app with:
- Login screen with validation (email + strong password)
- BLoC state management (flutter_bloc)
- Fetches 10 images from https://picsum.photos and shows them with preserved aspect ratio
- Montserrat font via google_fonts

## How to run

1. Ensure Flutter SDK is installed (https://flutter.dev/docs/get-started/install)
2. From project root:
   ```bash
   flutter pub get
   flutter run
   ```
3. To build APK:
   ```bash
   flutter build apk --release -t lib/main.dart
   ```
   The APK will be in `build/app/outputs/flutter-apk/`.

## Notes
- This repo is a generated example. Replace the demo auth logic with your real auth if needed.
- For caching images, consider adding `cached_network_image`.

