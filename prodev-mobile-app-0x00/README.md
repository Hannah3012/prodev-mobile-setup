# 📱 First Mobile App Setup with Expo Router
 This project demonstrates how to scaffold and set up a basic mobile application using **Expo Router**, modify its content, run it on a mobile device, and reset the project environment.
## Setup Instructions
   ### 1. Navigate to Your Project Directory 
     cd prodev-mobile-setup 
   ### 2. Initialize the Expo Project with Router Template
      Use the latest Expo CLI to scaffold your project:
      npx create-expo-app@latest . 
      Selected expo-router template
      Allowed it to install dependencies automatically
   ### 3. Modify the Home Screen
      Open the file:
      app/(tabs)/index.tsx 
      Find this line:
      <Text className="font-bold text-xl">Welcome!</Text> 
      And replace it with:
      <Text className="font-bold text-xl">First App Created</Text> 
   ### 4. Run and Test Your Application
      Start the Expo development server:
      npx expo start 
      On Mobile Devices:
      iOS: Scan the QR code in the terminal using the Camera app
      Android: Use the Expo Go app to scan the QR code
      You should now see "First App Created" on the home screen.

### 🔄 Reset the Application
   Reset your project using:
   npm run reset-project 

### 🔍 What Happened After Reset:
   Cleared Expo cache and .expo folder
   Removed node_modules and lock files
   Reinstalled all dependencies
   App still worked as expected
   Ensured the project was in a clean, fresh state
### Summary
    Scaffolded project using Expo Router
    Modified home screen text successfully
    Tested app in Expo Go
    Observed the impact of the reset-project command
### Tools Used
   Node.js
   Expo CLI
   React Native
   Expo Router
   VS Code
