# React Native - Albums App

  - Setup React Native CLI for the desired platform
    - https://facebook.github.io/react-native/docs/getting-started.html

  - Install dependencies and start app
```sh
$ git clone git@github.com:danielmapar/ReactNativeAuthWithFirebaseApp.git
$ cd ReactNativeAuthWithFirebaseApp
$ npm install
$ touch .env
$ echo "firebaseApiKey='${FIREBASE_API_KEY}'" > .env
$ echo "firebaseAuthDomain='${FIREBASE_AUTH_DOMAIN}'" > .env
$ echo "firebaseDatabaseURL='${FIREBASE_DATABASE_URL}'" > .env
$ echo "firebaseStorageBucket='${FIREBASE_STORAGE_BUCKET}'" > .env
$ echo "firebaseMessagingSenderId='${FIREBASE_MESSAGING_SENDER_ID}'" > .env
$ Run the Setup for environment variables: https://github.com/luggit/react-native-config
$ react-native run-ios OR react-native run-android
```

- Optional - Install Linter and ESLint inside Atom to modify this project following
  the standards inside ```.eslintrc```:
  - Install linter package
  - Install linter-eslint package
