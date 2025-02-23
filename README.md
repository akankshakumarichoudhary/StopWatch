

# StopwatchApp

## Summary
**StopwatchApp** is a simple and functional stopwatch application built using **Jetpack Compose** for Android. It allows users to start, stop, and reset a stopwatch. The time is displayed in **minutes, seconds, and milliseconds**. The app is a great tool to track time for various tasks and activities in a smooth and user-friendly interface.

## Features
- **Start Stopwatch**: Start the stopwatch with the press of a button.
- **Stop Stopwatch**: Stop the stopwatch at any time.
- **Reset Stopwatch**: Reset the stopwatch to 0 milliseconds.
- **Time in Milliseconds**: The time is displayed with precision up to milliseconds.
- **User-Friendly Interface**: Simple buttons for controlling the stopwatch with clear and readable time format.

## Screenshot
<img width="357" alt="Screenshot 2025-02-23 at 4 46 32 PM" src="https://github.com/user-attachments/assets/3404aee7-2d08-42d5-9cf9-64345091a779" />


## Tech Stack Used
- **Android Studio**: Integrated development environment (IDE) used for building the app.
- **Kotlin**: Programming language used for Android development.
- **Jetpack Compose**: A modern toolkit for building native UI on Android.
- **Material3**: UI design components and themes for modern, responsive design.

## How to Set Up

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/akankshakumarichoudhary/StopwatchApp.git
   ```

2. **Open the Project in Android Studio**:
   - Launch Android Studio and open the cloned project.

3. **Build and Run the App**:
   - Ensure you have a running Android emulator or a physical device connected.
   - Click on the "Run" button in Android Studio to build and run the app on your device.

4. **App Functionality**:
   - Press the **Start** button to start the stopwatch.
   - Press the **Stop** button to stop the stopwatch.
   - Press the **Reset** button to reset the stopwatch to 0.

5. **Dependencies in `build.gradle`**:
   Make sure the following dependencies are included in your `build.gradle` file:
   
   ```gradle
   dependencies {
       implementation "androidx.compose.ui:ui:1.0.0"
       implementation "androidx.compose.material3:material3:1.0.0-alpha01"
       implementation "androidx.activity:activity-compose:1.3.0"
       implementation "androidx.lifecycle:lifecycle-runtime-ktx:2.3.1"
       implementation "androidx.compose.foundation:foundation:1.0.0"
   }
   ```

## Example Use Case
This stopwatch app can be useful in various scenarios:
- **Fitness**: Track your workout time with precision (e.g., during interval training).
- **Cooking**: Use it as a timer while cooking recipes that require time measurements.
- **Task Management**: Track time spent on various tasks in productivity apps or studies.

## Created By
Akanksha
