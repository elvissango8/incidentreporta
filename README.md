# Incident Reporting App

![Incident Reporting App Logo](link-to-your-logo.png) <!-- Add logo image link if available -->

## Overview

The **Incident Reporting App** is a user-friendly mobile application designed to facilitate the reporting and tracking of incidents within an organization or community. This app provides users with an efficient way to document incidents, track their status, and enhance communication regarding safety and security issues.

---

## Features

- **User Authentication**: Secure sign-up and login process for users.
- **Incident Reporting**: Easily report incidents by providing essential details, including type, location, and description.
- **Status Tracking**: View the status of reported incidents and receive updates on their resolution.
- **Photo Uploads**: Attach images to incident reports for better context.
- **Search and Filter**: Quickly find reported incidents using search and filter options.

---

## Technologies Used

- **Frontend**: Flutter
- **Backend**: Firebase
- **Database**: Firestore
- **Authentication**: Firebase Authentication
- **Storage**: Firebase Storage for media uploads

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/incidentreporta.git
   cd incidentreporta
   
Install Dependencies: Make sure you have Flutter installed. Run the following command:

bash
Copy code
flutter pub get
Configure Firebase:

Create a Firebase project and add an Android/iOS app to it.
Download the google-services.json or GoogleService-Info.plist file and place it in the appropriate directory.
Update the Firebase configuration in the app according to your project settings.
Run the App:

bash
Copy code
flutter run
Usage

# Setup Firebase for Flutter App

## Prerequisites
- Ensure you have Flutter installed. Follow the [official Flutter installation guide](https://flutter.dev/docs/get-started/install) if needed.

## Steps to Setup Firebase

1. **Create a Firebase Project**:
   - Go to the [Firebase Console](https://console.firebase.google.com/) and click on "Add project".
   - Follow the prompts to create a new project.

2. **Register Your App**:
   - In your Firebase project, navigate to "Project Settings" (the gear icon next to "Project Overview").
   - Under "Your apps", add a new app for both Android and iOS:
     - For **Android**:
       - Enter your Android package name (you can find this in `android/app/build.gradle`).
       - Download the `google-services.json` file.
       - Rename it to `google-services.json` and place it in the `android/app/` directory.
     - For **iOS**:
       - Enter your iOS bundle ID (you can find this in `ios/Runner.xcodeproj/project.pbxproj`).
       - Download the `GoogleService-Info.plist` file.
       - Rename it to `GoogleService-Info.plist` and place it in the `ios/Runner/` directory.

3. **Copy Template Files**:
   - From the root of your project, copy `google-services-template.json` to `android/app/` and rename it to `google-services.json`.
   - Copy `GoogleService-Info-template.plist` from the root to `ios/Runner/` and rename it to `GoogleService-Info.plist`.

4. **Build Your App**:
   - Run `flutter pub get` to install dependencies.
   - You can now run the app using:
     ```bash
     flutter run
     ```

## Notes
- Ensure you have the Google Services plugin set up for both Android and iOS as per the [Firebase setup instructions](https://firebase.google.com/docs/flutter/setup).









Reporting an Incident:

Navigate to Admins Screen section.
Select the Admin you want to report to (This will open up a chat view)
Fill in the necessary details (tick the incident checkbox).You can also pick an image,write the description and submit your report.
Tracking Incidents:

Go to Messages, Select the chat with the incided you reported.View the status just above the incident message.The status is either pending or solved

Contributing
Contributions are welcome! If you would like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch:
bash
Copy code
git checkout -b feature/YourFeature
Make your changes and commit them:
bash
Copy code
git commit -m 'Add some feature'
Push to the branch:
bash
Copy code
git push origin feature/YourFeature
Open a Pull Request.
License
This project is licensed under the [Mozilla Public License 2.0 (MPL 2.0)] License. See the LICENSE file for details.

Contact
For any inquiries or support, please contact Me:

Email: elvissango887@gmail.com
GitHub: elvissango8
