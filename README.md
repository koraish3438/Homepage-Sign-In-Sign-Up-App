# Homepage, Sign In & Sign Up App

A multi-screen Android app featuring a Homepage, Sign In, and Sign Up pages with smooth navigation and proper validation.

---

## Table of Contents
- [Project Objective](#project-objective)
- [Features & Flow](#features--flow)
- [Validation Rules](#validation-rules)
- [Tech Stack](#tech-stack)
- [Screenshots](#screenshots)
- [Usage](#usage)
- [Author](#author)
- [License](#license)
- [Contact](#contact)

---

## Project Objective
Create a user-friendly Android app with multiple screens: Homepage, Sign In, and Sign Up. The app ensures smooth navigation and proper validation of user inputs.

---

## Features & Flow

### 1. Splash Screen
- Displays app name and developer name for 2 seconds.
- Automatically opens Homepage.

### 2. Homepage (`MainActivity`)
- Title: “Welcome to MyApp”
- Two Buttons:
  - **Sign In** → Opens `SignInActivity`
  - **Sign Up** → Opens `SignUpActivity`
- Developer name/ID displayed at the bottom.

### 3. Sign Up Activity (`SignUpActivity`)
- Uses `TextInputLayout` + `TextInputEditText` for:
  - Username
  - Email
  - Password
  - Confirm Password
- Validation Rules:
  - All fields must be filled.
  - Password and Confirm Password must match.
  - Email must be valid.

### 4. Sign In Activity (`SignInActivity`)
- Uses `TextInputLayout` + `TextInputEditText` for:
  - Email
  - Password
- Validation Rules:
  - All fields must be filled.
  - Checks email and password match registered account.

---

## Tech Stack
- **Language:** Kotlin  
- **Platform:** Android Studio  
- **UI Components:** ConstraintLayout, TextInputLayout, Button, TextViews  
- **Navigation:** Intent (Splash → Homepage → Sign In / Sign Up)

---

## Screenshots

<table>
  <tr>
    <td><img src="https://github.com/koraish3438/Homepage-Sign-In-Sign-Up-App/raw/a54ac179b031669a44cc84bf82bb9a4abe022588/Screenshot_2025-10-20-10-23-20-10_f6ea0aff7e5236502c1e482c4bd77a32.jpg" width="200"></td>
    <td><img src="https://github.com/koraish3438/Homepage-Sign-In-Sign-Up-App/raw/master/Screenshot_2025-10-20-10-21-40-35_f6ea0aff7e5236502c1e482c4bd77a32.jpg" width="200"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/koraish3438/Homepage-Sign-In-Sign-Up-App/raw/master/Screenshot_2025-10-20-10-21-43-47_f6ea0aff7e5236502c1e482c4bd77a32.jpg" width="200"></td>
    <td><img src="https://github.com/koraish3438/Homepage-Sign-In-Sign-Up-App/raw/master/Screenshot_2025-10-20-10-21-46-32_f6ea0aff7e5236502c1e482c4bd77a32.jpg" width="200"></td>
    <td><img src="https://github.com/koraish3438/Homepage-Sign-In-Sign-Up-App/raw/master/Screenshot_2025-10-20-10-21-49-98_f6ea0aff7e5236502c1e482c4bd77a32.jpg" width="200"></td>
  </tr>
</table>

---

## Usage
1. Launch the app.  
2. Navigate through the Homepage.  
3. Choose **Sign Up** to create an account or **Sign In** if already registered.  
4. Enter required credentials and submit.  
5. Access app features upon successful authentication.

---

## Author
**MD Kajam-all Koraish**

---

## License
This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

---

## Contact
**Developer:** MD Kajam-all Koraish  
**GitHub:** [https://github.com/koraish3438](https://github.com/koraish3438)  

Feel free to reach out with questions or suggestions.
