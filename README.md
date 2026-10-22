# FuelWise SA — Deliverable 4

**Smart Fuel. Smarter You.**

## Project Overview

FuelWise SA is an Android mobile application designed to help South African motorists manage their vehicles, monitor fuel consumption, track journeys, and locate nearby petrol stations.

The application provides a central platform for recording fuel expenses, managing vehicle information, and viewing driving history.

## Key Features

### 1. User Authentication
- User registration and login using Firebase Authentication.
- Secure access to individual user accounts.

### 2. Vehicle Management
- Register and manage vehicles.
- Store vehicle information, including make, model, registration number, year, and fuel type.

### 3. Fuel Management
- Record refuelling transactions.
- Track fuel expenditure and litres purchased.
- View fuel history and monthly fuel summaries.

### 4. Trip Management
- Manually record journeys.
- Automatically detect driving trips using location services.
- Record trip distances and view trip history.
- Support background trip detection and local trip storage.

### 5. Nearby Petrol Stations
- Discover nearby petrol stations using OpenStreetMap and Overpass.
- Search within selected distances.
- Display station names, addresses, and approximate distances.
- Open Google Maps for navigation.
- Cache station information for offline access.

### 6. Fuel Price Information
- Retrieve South African regional fuel-price information through the Fuel SA API.
- Store updated prices in Firebase Cloud Firestore.
- Display petrol retail reference prices and diesel wholesale reference prices.
- Distinguish regional reference prices from individual station pump prices.

## Technologies Used

| Technology | Purpose |
|---|---|
| Java | Android application development |
| XML | Android user interface layouts |
| Android Studio | Development environment |
| Firebase Authentication | User registration and login |
| Firebase Cloud Firestore | Cloud database |
| Google Location Services | GPS and location tracking |
| OpenStreetMap / Overpass API | Nearby petrol station discovery |
| Fuel SA API | South African fuel-price information |
| Python | Backend fuel-price processing |
| GitHub Actions | Automated backend workflows |

## Source Code

The complete Android Studio source-code project is provided in:

**FuelWiseSA-Deliverable4-SourceCode.zip**

### How to Run the Application

1. Download the source-code ZIP.
2. Extract the ZIP to your computer.
3. Open Android Studio.
4. Select **Open** and choose the extracted project folder.
5. Allow Gradle to synchronise and install required dependencies.
6. Configure the required Firebase project settings.
7. Run the application on an Android emulator or compatible Android device.

Some cloud-connected features require valid Firebase configuration, internet access, and appropriate location permissions.

## Demonstration Video

https://drive.google.com/file/d/1IJL6DCXfY1bdC6LvKr-maFt2h39qsxC9/view?usp=sharing

The demonstration will show the application's main features, including authentication, vehicle management, fuel tracking, trip history, automatic trip detection, and nearby petrol station discovery.

## Deliverable 4 Submission

This repository has been prepared for Deliverable 4 and contains the application source code and supporting demonstration material.

The final myLMS submission PDF will contain the GitHub repository link, demonstration video link, and screenshots showing the application in operation.

---

**FuelWise SA — Smart Fuel. Smarter You.**
