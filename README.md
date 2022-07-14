## Project Setup
---

### Create a Firebase project and Firestore database

Set up Firebase Firestore following the steps outlined [in this lesson](https://www.learnhowtoprogram.com/react/react-with-nosql/setting-up-a-firebase-project)

1. Create a Firebase account
2. Create a new project on Firebase
3. Create a new firestore database
4. Add Firebase to your web app

### Create a `.env` file with the Firebase configuration keys

Create a `.env` file (if you have not already), and use the details in your `firebaseConfig` to populate the following data. If you have misplaced this information, from the firebase console, click on the gear in the upper left of the page, then click project settings, and then scroll to the bottom of the page.

```
REACT_APP_FIREBASE_API_KEY = "YOUR-UNIQUE-CREDENTIALS"
REACT_APP_FIREBASE_AUTH_DOMAIN = "YOUR-PROJECT-NAME.firebaseapp.com"
REACT_APP_FIREBASE_PROJECT_ID = "YOUR-PROJECT-FIREBASE-PROJECT-ID"
REACT_APP_FIREBASE_STORAGE_BUCKET = "YOUR-PROJECT-NAME.appspot.com"
REACT_APP_FIREBASE_MESSAGING_SENDER_ID = "YOUR-PROJECT-SENDER-ID"
REACT_APP_FIREBASE_APP_ID = "YOUR-PROJECT-APP-ID"
```

### Enable authentication in your Firebase project

Set up Firebase Athentication following the steps outlined [in this lesson](https://www.learnhowtoprogram.com/react/react-with-nosql/firebase-authentication)

1. Navigate to your project in the firebase console, 
2. From the "Build" menu option, click on "Authentication"
3. Select the "Sign-in method" tab. 
4. Click on the option "Email/password." 
5. Then enable "Allow users to sign up using their email address and password." Don't enable "Email link".

### Install dependencies and run the project

1. Install dependencies by running `npm install` in the command line, in the root of the project folder.
2. Run the project by executing `npm run start` in the command line, in the root of the project folder.