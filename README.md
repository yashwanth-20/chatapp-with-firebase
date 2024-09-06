![Miniature](https://user-images.githubusercontent.com/43630417/167732465-f02c0dea-48db-4e23-ab26-90ca69115251.png)
# Chat App using React Native Expo and Firebase

## How to clone

Clone the repo

cd into the just created project and install dependencies with yarn

```
cd ChatApp && yarn
```

Add your firebase backend config in the `firebase.js` file

```
const firebaseConfig = {
  apiKey: Constants.expoConfig.extra.apiKey,
  authDomain: Constants.expoConfig.extra.authDomain,
  projectId: Constants.expoConfig.extra.projectId,
  storageBucket: Constants.expoConfig.extra.storageBucket,
  messagingSenderId: Constants.expoConfig.extra.messagingSenderId,
  appId: Constants.expoConfig.extra.appId,
  databaseURL: Constants.expoConfig.extra.databaseURL,
  //   @deprecated is deprecated Constants.manifest
};
```

Run the project

```
expo start
```

Congratulations 🎉 Now you have a functional Chat App working locally



## Known issues

Expo SDK and libraries are always updating their versions and deprecating others. before installing the libraries run.

```
yarn add expo@latest
```

Next, you can run:

```
    npx expo install --fix
```

Older versions of `react-native-gifted-chat` have some issues. Could you make sure you have the latest?

```
npx expo install react-native-gifted-chat@latest
```

Expo will show you what dependencies need to be updated. Install the dependencies the expo suggests to you. There is cache and you have to run.

```
yarn start --reset-cache
```

