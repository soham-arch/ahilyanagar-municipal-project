Ahilyanagar Municipal Attendance System

AI-based mobile attendance system developed for the Ahilyanagar Municipal Corporation during internship to ensure secure and authentic employee attendance using facial recognition and geolocation verification.

This application eliminates manual attendance registers and prevents proxy attendance, remote attendance marking, and identity fraud.

Project Overview

The Ahilyanagar Attendance System is a mobile application built using Flutter that allows government employees to mark their attendance securely.

The system verifies attendance using two authentication layers:

Face Recognition – verifies employee identity

Geolocation Verification – ensures attendance is marked only within the authorized workplace location

Attendance is recorded only when both conditions are satisfied, making the system highly secure and reliable for government workforce management.

Problem Statement

Traditional attendance systems in many organizations face several issues:

Manual attendance registers

Proxy attendance by colleagues

Employees marking attendance remotely

Lack of transparency in attendance tracking

For municipal organizations managing hundreds of employees, this leads to inefficient workforce monitoring.

Proposed Solution

The Ahilyanagar Attendance System solves these issues using a mobile-based biometric attendance solution.

The system:

Captures the employee's face through the mobile camera

Uses facial recognition to verify identity

Retrieves GPS location of the employee

Checks if the employee is within the authorized location radius

Marks attendance only if both conditions are satisfied

This ensures secure, location-restricted, and verified attendance marking.

Key Features
Secure Employee Authentication

Employees verify their identity through face recognition technology before attendance is marked.

Location Restricted Attendance

The app uses GPS geolocation verification to ensure employees are physically present at the designated workplace.

Mobile-Based System

Employees can mark attendance using their mobile devices, eliminating manual systems.

Real-Time Attendance Recording

Attendance is stored digitally and can be accessed by administrators for monitoring.

Fraud Prevention

Prevents:

Proxy attendance

Fake attendance

Attendance marking outside office premises

Technology Stack
Mobile Application

Flutter

Dart

Flutter enables cross-platform development and provides a smooth UI experience for the application.

Backend & Cloud Services

Firebase

Firebase services used:

Firebase Authentication

Cloud Firestore / Realtime Database

Firebase Storage

Firebase Hosting (if used)

Facial Recognition

Face verification is implemented using machine learning-based facial recognition techniques.

Typical pipeline includes:

Face detection

Face feature extraction

Embedding generation

Embedding comparison

Geolocation Services

GPS-based location tracking

Radius-based location verification

Flutter packages typically used:

geolocator

location

Device Hardware Used

Mobile Camera

GPS Sensor

System Workflow

The application follows the following workflow:

Step 1: User Login

Employee logs into the mobile application using their credentials.

Step 2: Location Verification

The application retrieves the employee's current GPS coordinates.

The system checks whether the user is within the allowed geographic radius of the workplace.

If the user is outside the allowed location, attendance cannot be marked.

Step 3: Face Capture

If the location check passes, the app opens the device camera to capture the employee’s face.

Step 4: Face Recognition

The system processes the captured face image and compares it with the registered employee facial data.

Step 5: Attendance Marking

If the face matches the stored identity, attendance is successfully recorded.

Attendance record includes:

Employee ID

Name

Date

Time

GPS Location

Verification status

System Architecture

High-level architecture of the system:

Mobile Application (Flutter)

↓

Camera Capture & GPS Retrieval

↓

Face Recognition Verification

↓

Location Radius Validation

↓

Firebase Backend

↓

Attendance Database Storage

Use Case
Government Municipal Workforce Management

The system is designed for Ahilyanagar Municipal Corporation employees.

It can be used for:

Municipal staff attendance

Field workers

Office employees

Government workforce tracking

Advantages of the System

Eliminates manual attendance systems

Prevents proxy attendance

Ensures location-based verification

Provides real-time attendance tracking

Improves workforce accountability

Reduces administrative workload

Project Structure

Typical Flutter project structure:

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

Main application logic is located inside the lib/ directory.

Installation Guide
Prerequisites

Flutter SDK installed

Android Studio / VS Code

Firebase project configured

Android device or emulator

Steps to Run the Project

1 Clone the repository

git clone https://github.com/soham-arch/ahilyanagar-municipal-project.git

2 Navigate into the project directory

cd ahilyanagar-municipal-project

3 Install dependencies

flutter pub get

4 Run the application

flutter run
Future Improvements

Possible enhancements for the system include:

AI-based attendance analytics

Admin dashboard for attendance monitoring

Automated attendance reports

Integration with payroll systems

Liveness detection for stronger biometric security

Multi-location support for multiple offices

Internship Project

This project was developed as part of an internship project for Ahilyanagar Municipal Corporation.

The goal was to build a secure and efficient attendance system using modern mobile technologies and biometric verification.

Author

Soham Patil

GitHub
https://github.com/soham-arch
