# Flutter Image Gallery App

A modern, feature-rich Flutter application that allows users to create their personal image gallery. Users can capture photos using their device's camera or select images from their gallery, view them in a grid layout, and interact with them using zoom and pan gestures.

## 🌟 Features

- **Image Capture & Selection**
  - Take photos directly from the camera
  - Select images from device gallery
  - Support for both iOS and Android devices

- **Gallery Management**
  - Grid view display of all selected images
  - Smooth animations when navigating between views
  - Empty state handling

- **Image Viewing**
  - Full-screen image viewer
  - Pinch to zoom functionality
  - Swipe navigation between images
  - Hero transitions for smooth user experience

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (version 3.0.0 or higher)
- Dart SDK (version 2.17.0 or higher)
- iOS Simulator/Device (iOS 11.0 or higher)
- Android Emulator/Device (API 21 or higher)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/soum-dev/flutter_image_gallery.git
cd flutter_image_gallery
```

2. Install dependencies:
```bash
flutter pub get
```

3. Configure platform-specific settings:

#### iOS Configuration
Add the following keys to your `ios/Runner/Info.plist`:

```xml
<key>NSCameraUsageDescription</key>
<string>This app needs access to camera to take photos.</string>
<key>NSPhotoLibraryUsageDescription</key>
<string>This app needs access to photos for selecting images from gallery.</string>
```

#### Android Configuration
No additional configuration needed as the image_picker plugin handles permissions automatically.

4. Run the app:
```bash
flutter run
```

## 📦 Dependencies

Add these dependencies to your `pubspec.yaml`:

```yaml
dependencies:
  flutter:
    sdk: flutter
  image_picker: ^1.0.4
  photo_view: ^0.14.0
```

## 🎯 Usage

1. **Launch the App**
   - Open the app to see the main gallery screen

2. **Add Images**
   - Tap the camera icon in the app bar
   - Choose between "Take a picture" or "Choose from gallery"
   - Selected images will appear in the grid

3. **View Images**
   - Tap any image in the grid to open it in full-screen mode
   - Use pinch gestures to zoom in/out
   - Swipe left/right to navigate between images
   - Tap the back button to return to the grid view

## 🔧 Project Structure

```
lib/
├── main.dart
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## 👨‍💻 Author

Mouhamed Soumare - [@soum-dev](https://github.com/soum-dev)

## 🙏 Acknowledgments

- [image_picker](https://pub.dev/packages/image_picker) package
- [photo_view](https://pub.dev/packages/photo_view) package
- Flutter team for the amazing framework

## 💬 Support

For support, email mouhamedsoumare70@gmail.com or open an issue in the repository.
