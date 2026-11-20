# Image Location app <a name="about-project"></a>

Android application built with Kotlin and Jetpack Compose that demonstrates loading drawable images, managing text via `strings.xml`, building UI layouts with cards and buttons, handling runtime location permissions in Kotlin, and displaying the user's current location on a map once access is granted.

## 🛠️ Built With

- **Language:** Kotlin
- **UI Toolkit:** Jetpack Compose
- **Architecture:** Activity-Based Architecture
- **State Management:** Compose State (`mutableStateOf`)
- **Permissions:** Android Runtime Permissions API (`ActivityResultContracts`)
- **Resources & Localization:** Android `res/drawable` & `strings.xml`
- **Maps & Location:** Google Maps / Android Location Services
- **Design System:** Material Design 3
- **Development Environment:** Android Studio
- **SDK:** Android SDK

---

### Key Features <a name="key-features"></a>

- ✅ Display images loaded from `res/drawable`
- ✅ Manage UI text using `strings.xml` resources
- ✅ Clean Jetpack Compose UI with cards and buttons
- ✅ Runtime location permission request triggered on button tap
- ✅ Graceful handling of both accepted and denied permission results in Kotlin
- ✅ Display the user's current location on a map once permission is granted
- ✅ Material Design 3 user interface
- ✅ Modern Android permission workflow

---

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites

Before running this project, make sure you have:

- Android Studio installed
- Android SDK configured
- Kotlin support enabled
- Android Emulator (with Google Play Services & mock location enabled) or a physical Android device
- JDK 11 or later

### Setup

Clone this repository:

```sh
git clone https://github.com/AbigiyaTY/imagelocationdemo.git
```

Navigate to the project directory:

```sh
cd imagelocationdemo
```

### Install

Open the project in Android Studio:

```text
File → Open → Select Project Folder
```

Allow Android Studio to synchronize and download all required Gradle dependencies.

### Dependencies

The project uses Jetpack Compose, Material Design 3, and location/map libraries:

```kotlin
implementation("androidx.compose.material3:material3")
implementation("com.google.android.gms:play-services-location:21.3.0")
implementation("com.google.maps.android:maps-compose:4.4.1")
```

### Permissions

The application requires the following permissions in `AndroidManifest.xml`:

```xml
<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
<uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />
```

### Usage

This project demonstrates:

- Loading local images from the `res/drawable` folder
- Managing and displaying string values from `strings.xml`
- Building structured layouts with Compose `Card` and `Button` components
- Requesting runtime location permissions in Jetpack Compose
- Handling permission grant/deny callbacks in Kotlin
- Displaying the user's current location on a map after approval
- State management with Compose
- Android security and permission best practices

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to fork this repository and submit a pull request.
