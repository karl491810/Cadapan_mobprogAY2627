# cadapan_flutter_application_1

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Learn Flutter](https://docs.flutter.dev/get-started/learn-flutter)
- [Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Flutter learning resources](https://docs.flutter.dev/reference/learning-resources)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

Lab Activity 0:
While setting up my Flutter development environment, I encountered a few challenges, especially with configuring the PATH variables and resolving issues reported by flutter doctor. Initially, Flutter was not recognized in the terminal because the Flutter bin directory was not added correctly to the system PATH. After updating the environment variables and restarting the terminal, the issue was resolved.

Another challenge was accepting Android SDK licenses and installing missing dependencies. Running flutter doctor showed warnings about Android toolchain issues, so I used flutter doctor --android-licenses and installed the required SDK components through Android Studio. I also experienced emulator launch problems when the virtual device was not configured properly, which I fixed by creating a new Android Virtual Device (AVD) and ensuring virtualization was enabled.

These troubleshooting steps helped me better understand the Flutter toolchain and the requirements for cross-platform development. In the future, I will regularly use flutter doctor, keep SDKs updated, and carefully verify environment configurations to avoid setup issues and streamline development.
