# Wellnest - Client-Side Mobile Application for E-MOGRAM

**Wellnest** is the client-side mobile application built using Flutter for the **E-MOGRAM** project. The app is designed to interact with the sentiment analysis backend and provide real-time emotional insights, based on sentiment analysis of social media posts. It aims to assist users in understanding their emotional well-being.

## Features

- **Sentiment Analysis:** Analyzes the sentiment of social media posts (e.g., Facebook) for positive, neutral, or negative emotions.
- **Real-time Alerts:** Sends notifications when emotional distress or negative sentiments are detected in social media posts.
- **User-Friendly Interface:** A simple, intuitive interface that displays emotional analytics and resources for mental health support.


## Installation

To set up and run the **Wellnest** Flutter client app locally, follow these steps:

### Prerequisites

- Flutter SDK (installed and set up)
- Dart SDK
- Android Studio or Visual Studio Code (with Flutter and Dart plugins)
- Firebase account and configuration

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/wellnest-main.git
   cd wellnest-main
2.	Install dependencies:
    flutter pub get
3.	Set up Firebase:
	•	Go to the Firebase Console.
	•	Create a new Firebase project.
	•	Set up Firebase Cloud Messaging (FCM) and download the google-services.json for Android and GoogleService-Info.plist for iOS.
	•	Place the configuration files in their respective platform folders (android/app/ for Android, ios/Runner/ for iOS).
4.	Run the application:
To run the application on an emulator or connected device, use:
    flutter run


Firebase Setup
	1.	Ensure Firebase is properly configured for both Android and iOS platforms.
	2.	Add the necessary configuration files (google-services.json for Android and GoogleService-Info.plist for iOS) to their respective directories in the project.

Contributing

We welcome contributions! If you’d like to contribute to the project, follow these steps:
	1.	Fork the repository.
	2.	Create a new branch (git checkout -b feature/your-feature).
	3.	Commit your changes (git commit -am 'Add new feature').
	4.	Push to the branch (git push origin feature/your-feature).
	5.	Open a pull request.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
	•	Flutter for building cross-platform mobile applications.
	•	Firebase for push notifications and real-time features.
 This updated README highlights that it's the **client-side** mobile app and provides all the necessary instructions for setting up and running the app. Let me know if you need further adjustments!
