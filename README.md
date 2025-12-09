# Group Maps Frontend

This is the frontend application for **Group Maps**, built with [Expo](https://expo.dev). It provides a mobile interface for coordinating real-life group activities using geolocation, connecting to the backend service via API.

## Requirements


### Prerequisites
- Node.js (LTS recommended)  
- npm or yarn  
- Expo CLI (`npm install -g expo-cli`)  
- For production builds: your own Google Maps API key  

For reference, specific package versions are listed in `package.json`. Consult this file if you need to check or match dependency versions.


---

## Environment Setup

1. Set your server URL in constants/settings.ts:
   ```javascript
      const API_URL = 'http://your-server-address.com';
   ```

2. Google Maps API Key (required for apk builds)

   For production builds, you must add your own Google Maps API key via Expo build configuration (app.config.js or app.json under extra) or using environment variables with expo build.

   Warning: The app will not display maps correctly in production builds without a valid Google Maps API key.



## Running the App
1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

Google Maps API Key (required for production builds)
For production builds, you must add your own Google Maps API key via Expo build configuration

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
