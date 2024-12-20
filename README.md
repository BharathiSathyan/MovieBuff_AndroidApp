## MovieBuzz AndroidApp

This repository contains the Android code for a simple movie app with basic signup and login functionalities.

**Features:**

* **Splash Screen:** An initial splash screen that appears when the app starts.
* **Signup:** Allows users to create new accounts with username and password.
* **Login:**  Allows users to log in with existing credentials.
* **Homepage:**  A basic homepage with a button to navigate to the main app functionality (not yet implemented).

**Technology:**

* **Android Studio:**  The app is developed using Android Studio.
* **Kotlin:** The code is written in Kotlin, a modern and concise programming language for Android development.
* **JavaFX:**  The UI is built using JavaFX.

**Structure:**

* **MainActivity.kt:** The main activity that displays the splash screen and starts the sign-in activity after a short delay.
* **sign_in.kt:**  Handles user login and provides a link to the signup activity.
* **signup.kt:** Handles user registration and provides a link to the login activity.
* **Homepage1.kt:** The basic homepage activity (currently only a placeholder with a button).

**Getting Started:**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/MovieApp.git
2. **Open in Android Studio:** Import the project into Android Studio.

3. **Run the app:** Build and run the app on an Android emulator or a connected device.

**Future Improvements:**

* Implement Full Functionality: Add features like browsing movies, searching, user profiles, and movie details.
* API Integration: Integrate with a movie database API (like TMDb) to fetch movie data.
