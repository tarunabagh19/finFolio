## Getting Started with React Native (Windows – Android)

### Prerequisites
- Node.js ≥ v18
- JDK 17–20
- Android Studio (with SDK & AVD tools)
- Android SDK Command-Line Tools
- Visual Studio Code or similar editor

### Setup Instructions
1. Install Node.js and JDK  
2. Download Android Studio and install via SDK Manager:  
   - Android SDK, SDK Platform (API 33+), Build-Tools  
   - SDK Command-Line Tools  
   - Android Virtual Device (AVD)  
3. Set environment variables:
   - `JAVA_HOME`: JDK installation path  
   - `ANDROID_HOME`: Android SDK path  
   - Add to `Path`:  
     - `%ANDROID_HOME%\platform-tools`  
     - `%ANDROID_HOME%\cmdline-tools\latest\bin`  
4. From project root:
   ```bash
   npx react-native init finFolio
   cd MyApp
   npx react-native run-android
