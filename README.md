# 🔐 Project 3: Homepage, Sign In & Sign Up App

## Objective
Create a multi-screen Android app featuring a **Homepage**, **Sign In**, and **Sign Up** pages connected via **Intents**.

---

## Features & Flow

### 1. Splash Screen
- Displays **app name** and **developer name** for 2 seconds.  
- Automatically opens **HomePage** after the delay.  

### 2. HomePage (`MainActivity`)
- Title: **“Welcome to MyApp”**  
- **Two Buttons:**  
  - **Sign In** → Opens `SignInActivity`  
  - **Sign Up** → Opens `SignUpActivity`  
- Developer name/ID displayed in a `TextView` at the bottom.  

### 3. Sign Up Activity (`SignUpActivity`)
- Uses `TextInputLayout` + `TextInputEditText` for:  
  - Username  
  - Email  
  - Password  
  - Confirm Password  

- **Validation on Sign Up:**  
  - All fields must be filled.  
  - Email must contain **"@"**.  
  - Password ≥ 6 characters.  
  - Password and Confirm Password must **match**.  

- On successful registration:  
  - Show **Toast:** `"Sign Up Successful!"`  
  - Navigate to **Sign In page**.  

### 4. Sign In Activity (`SignInActivity`)
- Fields for **Email** and **Password**.  
- **Validation on Sign In:**  
  - Check if input fields are filled.  
  - Verify credentials.  

- On correct login:  
  - Open **HomePage** via Intent.  
  - Pass **username** via Intent and display: `"Welcome <name>!"`  

---

## Example Flow


---

## Tech Stack
- **Language:** Kotlin  
- **Platform:** Android Studio  
- **UI Components:** ConstraintLayout, TextInputLayout, TextInputEditText, Buttons, TextViews  
- **Navigation:** Intents  

---

## Screenshots
  

---

## Author
**MD Kajam-all Koraish**
