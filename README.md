AllTool

A practical all-in-one utility toolkit for Android.

AllTool is an Android utility application designed to bring everyday tools together in one place, with a focus on usability, privacy, and offline-first functionality.

Features

- Image Tools — Image processing utilities, subject to implementation and device capabilities.
- PDF Tools — Document utilities for supported PDF operations.
- Text & OCR — Text-related utilities and text recognition where supported.
- QR Code Tools — Generate QR codes for supported content.
- Everyday Utilities — A collection of practical tools in one application.
- Offline-first Design — Core features are intended to work locally on the device whenever possible.

«Feature availability depends on the current application version. See the source code and release notes for implemented functionality.»

Project Goals

- Provide a clean and straightforward user experience.
- Prioritize local processing where practical.
- Minimize unnecessary network access.
- Keep the application lightweight and accessible.
- Make the project easier to inspect, build, and contribute to.

Getting Started

Requirements

- Android Studio
- A compatible Java Development Kit (JDK)
- Android SDK components required by the project
- Gradle wrapper included in the repository

Build

Clone the repository:

git clone https://github.com/hinaaqq/AllTool.git
cd AllTool

Build the debug APK:

./gradlew assembleDebug

On Windows, use:

gradlew.bat assembleDebug

The generated APK is typically located under the module's "build/outputs/apk/debug/" directory.

For automated builds, see the GitHub Actions workflows in ".github/workflows/".

Privacy

AllTool aims to process data locally whenever possible. Network access and data handling depend on the features enabled in each release. Review the source code and relevant permissions before using or distributing a build.

Contributing

Contributions, bug reports, and suggestions are welcome.

1. Open an issue describing the problem or proposed improvement.
2. Provide steps to reproduce bugs when possible.
3. Submit a pull request with a clear description of the changes.

Please avoid including personal information, credentials, API keys, or other secrets in issues and pull requests.

License

The project's license has not yet been selected. Until a license is added, do not assume that the source code is available for unrestricted reuse, modification, or redistribution.

Maintainer

Hina / Yasin

- GitHub: "@hinaaqq" (https://github.com/hinaaqq)

---

AllTool is an independent project. Feature availability and compatibility may vary by release and Android device.
