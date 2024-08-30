![image](https://github.com/user-attachments/assets/47ca897d-e0d1-44dc-bb79-49d2265a9a7c)

 # Emotion Detection Android App

 An android application that detects human emotions based on the image of human faces. The App is built on an Machine Learning model that is integerated with the android application using Firebase Api.

### 📷 Emotion Detection from Images
- **Upload or Capture**: Easily upload an image from your gallery or capture a new one using your device's camera.
- **Emotion Analysis**: Automatically detect and analyze emotions in faces found in the image. Supported emotions include:
  - 😄 Happiness
  - 😢 Sadness
  - 😠 Anger
  - 😲 Surprise
  - 😨 Fear
  - 😐 Neutral
  - 🤢 Disgust
 
 ### ⏱️ Real-time Emotion Analysis
- **Instant Results**: Get real-time feedback on emotions as soon as you capture or upload an image.
- **Visual Indicators**: Display detected emotions directly on the image with easy-to-understand visual indicators.
  
### 📁 Image Gallery Integration
- **Choose from Gallery**: Select any image from your device’s gallery for emotion detection.
- **Take new Photo**: Click new image from the camera of your device.

### 📊 Detailed Emotion Breakdown
- **Confidence Scores**: View a detailed breakdown of detected emotions with confidence scores.

  ### 🧍 Face Detection and Emotion Overlay
- **Multiple Faces**: Detect and analyze multiple faces in a single image.
- **Emotion Overlays**: Display emotion results directly on each detected face within the image.

  ### 💡 Intuitive User Interface
- **User-Friendly**: Designed for simplicity and ease of use, allowing smooth navigation between different features.
- **Clean Design**: A clean, minimalist design that prioritizes functionality.

  ### 🌐 Offline Functionality
- **No Internet Required**: Perform emotion detection without needing an internet connection using built-in models.
- **Optimized for Performance**: Lightweight and efficient, ensuring smooth operation even on low-end devices.

## Setup Instructions

### 1. Clone the Repository

First, clone the repository from GitHub to your local machine using the following command:

```bash
git clone https://github.com/alamba570/emotion_detector.git
```

### 2. Open the Project in Android Studio

1. Open Android Studio.
2. Click on **File > Open**.
3. Navigate to the directory where you cloned the repository.
4. Select the project folder and click **OK**.

### 3. Sync Project with Gradle Files

Once the project is loaded, Android Studio will automatically try to sync the Gradle files. If it doesn't, click on **File > Sync Project with Gradle Files**.

### 4. Set Up Firebase Account

The app uses Firebase for various backend services like authentication, database, and storage. Follow these steps to set up Firebase:

#### a. Create a Firebase Project

1. Go to the [Firebase Console](https://console.firebase.google.com/).
2. Click on **Add Project**.
3. Enter a project name and follow the on-screen instructions to set it up.

#### b. Add Firebase to Your Android Project

1. In the Firebase Console, click on **Add App** under the **Android** section.
2. Register your app by providing the Android package name (`com.yourcompany.yourappname`) which you can find in your `AndroidManifest.xml` file.
3. Download the `google-services.json` file provided by Firebase.

#### c. Add `google-services.json` to Your Project

1. Copy the `google-services.json` file to the `app/` directory of your project.
2. Ensure that the file is placed in the root directory of your `app/` module.

## 5. Build and Run the Project

1. Connect your Android device or start an Android emulator.
2. Click on the **Run** button (or press `Shift + F10`) to build and run the project.

### 6. Test the App

- Upload an image from your gallery or capture a new one to test the emotion detection functionality.
- Verify that Firebase services (e.g., authentication, database) are working as expected.

## Screenshots

You can include screenshots of the app to demonstrate its features and functionality.

- **Home Screen**: 
 ![6235545232888415693_121](https://github.com/user-attachments/assets/da2cbe16-1b10-4ae3-b3b6-7de0d6960053)


- **Emotion Detection in Action**: 
  ![6235545232888415694_121](https://github.com/user-attachments/assets/ce902d6b-5109-478b-8673-2becdcf25b30)


- **Results Screen**: 
 ![6235545232888415695_121](https://github.com/user-attachments/assets/d9abee20-add0-4d1d-93ee-9207fabdbe73)


## Help and Support

- If you run into any issues, check the [Firebase documentation](https://firebase.google.com/docs) or reach out via the Issues tab on GitHub.
- For any other questions or feedback, feel free to contact the repository owner.
