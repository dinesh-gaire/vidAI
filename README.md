Create expo project -> npx create-expo-app ./

Manual installation for expo Router -> File based routing
Go to Expo router installation and perform manual installation

Delete App.js after copying code inside it
Create app/_layout.jsx and paste code -> This is starting point of application

Create app/index.jsx
Copy code from _layout.jsx to index.jsx
Delete code from _layout.jsx and write rnfes and change function to RootLayout

Install nativewind by reading Docs
Content should be this :
content: ["./app/**/*.{js,jsx,ts,tsx}", "./components/**/*.{js,jsx,ts,tsx}"]
-> This means applying nativewind to all the folders(**) and files(*) inside app and components folder

Update tailwind.config.js by adding colors and fontFamily to extends
Update assests folder
Create app/(auth)/_layout.jsx
Create app/(auth)/sign-in.jsx
Create app/(auth)/sign-up.jsx
-> This is created since Auth screens doesn't have tab navigation
Create app/(tabs)/_layout.jsx
Create (tabs)/home.jsx
Create (tabs)/profile.jsx
Create (tabs)/bookmark.jsx
Create (tabs)/create.jsx
Create app/search/[query].jsx

Write all code for app/(tabs)/_layout.jsx

Update index.jsx
Create components/CustomButton.jsx

Update (auth)/layout.jsx
Update sign-in jsx
create components/FormField.jsx

Add new property package to android
Create lib/appwrite.js

users: username, email, avatar, accountId
videos: title,thumbnail,prompt,video


