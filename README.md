React Native Expo Firebase App

This is a React Native app built with Expo that uses Firebase for authentication and Firestore as a database. Features include login, QR code scanning, and scan history tracking.

Features
- User authentication (Firebase Auth)
- QR code scanner using Expo Camera/BarcodeScanner
- Store and display scan history in Firestore

Prerequisites
- Node.js (v14+ recommended)
- Expo CLI (`npm install -g expo-cli`)
- Firebase project setup (console.firebase.google.com)


Getting Started: 
1. Clone the repository

  git clone https://github.com/yourusername/your-repo.git
  cd your-repo


2. Install dependencies

  npm install 
  (or if you prefer yarn)
  yarn install

  
3. Configure environment variables

  Rename .env.example to .env
  Replace placeholders with your Firebase project credentials

5. Run the app

  expo start
  
This will start the Metro bundler. You can run the app on an emulator or physical device using the Expo Go app.
