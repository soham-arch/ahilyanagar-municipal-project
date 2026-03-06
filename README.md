Ahilyanagar Municipal Attendance System 📍📸

A secure mobile attendance application developed for Ahilyanagar Municipal Corporation during internship.

The system verifies employee attendance using Facial Recognition + GPS Location Validation, ensuring attendance can only be marked by the authorized employee within the designated workplace.

Features

📸 Face Recognition – Verifies employee identity before marking attendance

📍 Geo-Location Verification – Attendance allowed only inside authorized location radius

📱 Mobile-Based Attendance – Employees can mark attendance using their phones

🔐 Secure Verification – Prevents proxy or fake attendance

☁️ Cloud Data Storage – Attendance records stored securely

⚡ Real-Time Attendance Logging

Tech Stack

Mobile Application

Flutter

Dart

Backend & Cloud

Firebase

Firebase Authentication

Cloud Firestore / Realtime Database

Core Technologies

Face Recognition

GPS Geolocation

Mobile Camera Integration

How It Works

1️⃣ Employee logs into the application

2️⃣ App checks current GPS location

3️⃣ If user is inside authorized office radius, camera opens

4️⃣ App captures employee face

5️⃣ Face recognition verifies identity

6️⃣ If verified → attendance marked successfully

Project Structure
ahilyanagar-municipal-project

android/
ios/
lib/
web/
windows/
macos/

firebase.json
pubspec.yaml
README.md

Main application code is located inside:

lib/
Setup
1 Clone the repository
git clone https://github.com/soham-arch/ahilyanagar-municipal-project.git
cd ahilyanagar-municipal-project
2 Install dependencies
flutter pub get
3 Run the application
flutter run

Make sure you have:

Flutter SDK installed

Android Studio / VS Code

Android device or emulator

Use Case

This system is designed for government organizations to manage employee attendance securely.

Primary use case:

Ahilyanagar Municipal Corporation employee attendance monitoring

The system helps:

Prevent proxy attendance

Ensure employees are present at workplace

Digitize attendance management

Future Improvements

Possible improvements include:

Admin dashboard for attendance monitoring

Attendance analytics and reports

Liveness detection for face verification

Multi-location office support

Integration with payroll systems

Author

Soham Patil

GitHub
https://github.com/soham-arch
