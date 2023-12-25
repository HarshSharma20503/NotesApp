# NotesApp

NotesApp is a simple Android application developed using Android Studio, Java, and Firebase. This app allows users to create, update, and delete notes, while also incorporating Firebase authentication for user management. Additionally, Firebase Storage is utilized for efficient and secure storage of media files associated with the notes.

## Features

- **Firebase Authentication**: Users can sign up and log in securely using Firebase authentication, ensuring a personalized experience.
- **Create Notes**: Users can create new notes by providing a title and content.
- **Update Notes**: Existing notes can be edited to reflect changes or additional information.
- **Delete Notes**: Users can delete notes that are no longer needed.
- **Firebase Storage Integration**: Media files associated with the notes are stored securely using Firebase Storage.

## Prerequisites

Before running the app, make sure you have the following set up:

- [Android Studio](https://developer.android.com/studio) installed on your machine.
- A [Firebase](https://firebase.google.com/) project created with Authentication and Storage enabled.

## Getting Started

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/HarshSharma20503/NotesApp.git
   ```
2. Open the project in Android Studio.

**Configure Firebase:**

1. Create a new Firebase project on the [Firebase Console](https://console.firebase.google.com/).
   
2. Add an Android app to your Firebase project and follow the setup instructions to download the `google-services.json` file.

3. Place the `google-services.json` file in the `app` directory of your Android Studio project.

4. Run the app on an emulator or physical device.

**Configuring Firebase**

To enable Firebase in your project, replace the placeholder values in the `google-services.json` file with your own Firebase configuration. Follow the Firebase documentation for [adding Firebase to your Android project](https://firebase.google.com/docs/android/setup).


## Dependencies

- [Firebase Authentication](https://firebase.google.com/docs/auth)
- [Firebase Storage](https://firebase.google.com/docs/storage)


## Acknowledgments

- Thanks to this video I was able to understand concepts and was able to make this project [Link](https://www.youtube.com/watch?v=X_h5QQJaDDM&list=PLgpnJydBcnPCRTsNeuYd93TQaMWGiiHMH).
- Thanks to the [Firebase](https://firebase.google.com/) team for providing a robust and easy-to-use backend service.
- Special thanks to [Android Studio](https://developer.android.com/studio) for the powerful development environment.

Feel free to contribute to the project by submitting issues or pull requests. Happy coding!
