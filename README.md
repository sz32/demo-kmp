## KMP Demo Project

### Overview

Welcome to the KMP Demo Project repository! This project demonstrates the power and versatility of Kotlin Multiplatform Mobile (KMP) by creating a shared codebase that works seamlessly across both Android and iOS platforms. By utilizing KMP, we can efficiently share business logic, data models, and even some UI components, significantly reducing development time and ensuring code consistency.

### Features

- **Shared Business Logic**: Write once and run on both Android and iOS.
- **Platform-Specific UI**: Maintain native look and feel by developing platform-specific user interfaces.
- **Native Performance**: Access to platform-specific APIs ensures optimal performance and user experience.

### Libraries Used

This project leverages several essential libraries to enhance the KMP development experience:

- **[Ktor](https://ktor.io/)**: A powerful and flexible HTTP client for networking.
- **[SQLDelight](https://github.com/cashapp/sqldelight)**: A type-safe SQL database library for multiplatform applications.
- **[Kotlinx.serialization](https://github.com/Kotlin/kotlinx.serialization)**: Efficient serialization and deserialization of data.
- **[Koin](https://insert-koin.io/)**: A dependency injection framework that simplifies dependency management.
- **[Compose Multiplatform](https://www.jetbrains.com/lp/compose-multiplatform/)**: For building cross-platform UI with a declarative approach.

### Project Structure

The project is organized into three main modules:

- **Shared Module**: Contains the shared codebase that is used by both Android and iOS applications. This includes business logic, data models, and shared utilities.
- **Android App Module**: Contains the Android-specific code and resources, leveraging the shared module for business logic and data handling.
- **iOS App Module**: Contains the iOS-specific code and resources, utilizing the shared module for consistency and efficiency.

### Getting Started

To get started with this project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sz32/demo-kmp.git
   cd kmp-demo-project
   ```

2. **Open the project**:
   Open the project in IntelliJ IDEA or Android Studio with the Kotlin Multiplatform Mobile plugin installed.

3. **Build the project**:
   Run the Gradle build task to compile and assemble the shared, Android, and iOS modules.

4. **Run the application**:
   - For Android: Select the Android app module and run it on an Android device or emulator.
   - For iOS: Open the iOS project in Xcode, select a target device or simulator, and run the application.

### Contribution

Contributions are welcome! If you have any ideas for improvement or find any issues, please feel free to open an issue or submit a pull request.
