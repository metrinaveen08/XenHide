# XenHide Mobile

A Flutter implementation of the XenHide steganography tool.

## Features
- **Encrypt**: Hide a secret message inside an image (LSB technique).
- **Decrypt**: Extract a hidden message from an image.

## Setup
Since this project was initialized with the core logic and UI, you need to generate the platform-specific files (Android, iOS, etc.) if they are missing.

1. Open a terminal in this directory (`XHMobile`).
2. Run:
   ```bash
   flutter create .
   ```
3. Install dependencies:
   ```bash
   flutter pub get
   ```
4. Run the app:
   ```bash
   flutter run
   ```

## Dependencies
- `image`: For image processing and pixel manipulation.
- `file_picker`: To select images from the device.
- `path_provider`: To handle file saving locations.
