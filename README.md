# 📱 Sensor Data And Image Classification APP

**Mobile Computing Winter 2024 Assignment 3**

This repository contains the implementation for the Mobile Computing Winter 2024 Assignment 3, focusing on sensor data collection, real-time orientation display, data storage, time series prediction, and TensorFlow Lite image classification in Android.

## 📚 Table of Contents

- [Project Structure](#-project-structure)
- [Features](#-features)
- [Implementation Details](#-implementation-details)
- [Setup and Installation](#-setup-and-installation)
- [Usage](#-usage)
- [Dependencies](#-dependencies)
- [Build and Deployment](#-build-and-deployment)
- [Contributing](#-contributing)
- [License](#-license)

## 🏗 Project Structure

The project consists of two main components:

1. Accelerometer Data Collection and Analysis App
2. TensorFlow Lite Image Classification App

## ✨ Features

### Part 1: Accelerometer Data Collection and Analysis

- 📊 Real-time smartphone orientation display (three angles)
- 📅 Data collection from accelerometers
- 💾 Storage of orientation data in a local database
- 📈 Historical data visualization through graphs
- 📤 Export of data for time series prediction
- 🔮 Prediction of future orientation values
- 📉 Comparison of predicted vs actual values
- ⏱ Multiple sensing interval implementations

### Part 2: TensorFlow Lite Image Classification

- 📸 Image collection (from camera or file system)
- 🧠 Image classification using TensorFlow Lite
- 🖥 Display of classification results

## 🛠 Implementation Details

### Accelerometer Data Collection and Analysis

- Utilizes Android's `SensorManager` for data collection
- Implements two separate activities
- Uses SQLite for local data storage
- Exports data as a text file for desktop analysis
- Implements time series prediction
- Plots predicted vs actual values
- Allows for adjustable sensing intervals

### TensorFlow Lite Image Classification

- Leverages TensorFlow Lite for on-device machine learning
- Implements an activity for image loading and selection
- Runs a pre-trained image classification model
- Displays classification results

## 🚀 Setup and Installation

Clone the repository:

```bash
git clone https://github.com/aditi21372/MC_assignment3.git
```

1. Open the project in Android Studio
2. Sync the project with Gradle files
3. Build and run on an Android device or emulator

## 📱 Usage

- Launch the app on your Android device
  - For accelerometer data:
    - View real-time orientation
    - Access historical data graphs
    - Export data for prediction
  - For image classification:
    - Select or capture an image
    - View classification results

## 📦 Dependencies

- AndroidX libraries
- TensorFlow Lite

## 🏭 Build and Deployment

This project can be built and deployed using Android Studio. Ensure you have the latest version of Android Studio and the Android SDK installed.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is MIT licensed. See the [LICENSE](LICENSE) file for more details.
