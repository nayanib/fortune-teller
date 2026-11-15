# FortuneTeller

This is my first React Native app. I made it in VS Code using Expo during the Mobile Application Development Practical 02.

First I created an Android emulator (Pixel 4) in Android Studio. Then I created the project with `npx create-expo-app FortuneTeller`, cleaned it with `npm run reset-project` and started it with `npx expo start`. I opened the app on the emulator using the Expo Go app.

The app is a small fun "fortune teller" for coders. It has two screens, and you can move between them using Stack Navigation (Expo Router):

- **Welcome screen (`index.tsx`)** - This is the first screen that opens. It shows the title "FORTUNE TELLER", a round picture of a crystal ball, and a white box with a short message about coding. At the bottom there is a green button called "Reveal My Coding Destiny". When you press it, the app goes to the second screen.
- **Your Fortune screen (`reveal.tsx`)** - This screen shows "Here is your Fortune!", another round picture, and a box with a funny coding fortune. The "Go Back" button (or the back arrow at the top) takes you back to the first screen.

The `_layout.tsx` file controls the top bar of the app. It sets the title "Welcome" for the first screen and "Your Fortune" for the second screen.

In this lab I learned how to use `View`, `Text`, `Image` and `Button` to build a screen, how to style them with `StyleSheet.create`, and how to move between screens with `router.push()` and `router.back()`.
