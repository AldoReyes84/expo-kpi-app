# Basic Authentication Guide

## 📌 Overview
This document describes the implementation of **basic authentication** for the Expo KPI App.  
The goal of Sprint 2 is to develop login and registration screens, validate user input, and persist sessions securely.

---

## 🔧 Requirements
- React Native project initialized with Expo (from Sprint 1).  
- Libraries:
  - `react-navigation` for screen navigation.
  - `react-native-paper` or `react-native-elements` for UI components (optional).
  - `expo-secure-store` or `@react-native-async-storage/async-storage` for session persistence.
  - `yup` and `formik` for form validation.

---

## 🚀 Steps

### 1. Create Authentication Screens
- **Login Screen**: email and password fields, login button.  
- **Registration Screen**: email, password, confirm password fields, register button.  
- Add navigation between both screens.

### 2. Validate Forms
- Use **Formik** for form handling.  
- Use **Yup** for validation rules:
  - Email format validation.  
  - Password length (min 6 characters).  
  - Confirm password must match.  

### 3. Handle Authentication Logic
- For learning purposes, start with **mock authentication** (local JSON or hardcoded users).  
- Later, integrate with a backend service (Firebase Auth or Supabase).  
- On successful login, navigate to the **Dashboard** screen.

### 4. Persist User Session
- Use **AsyncStorage** or **SecureStore** to save session tokens.  
- On app launch, check if a session exists:
  - If valid → navigate directly to Dashboard.  
  - If not → show Login screen.

### 5. Logout Functionality
- Add a logout button in the Dashboard.  
- Clear session data from storage.  
- Redirect user back to Login screen.

---

## 📂 Suggested Structure
expo-kpi-app/
├── screens/
│    ├── LoginScreen.js
│    ├── RegisterScreen.js
│    └── DashboardScreen.js
├── navigation/
│    └── AuthNavigator.js
└── utils/
└── auth.js   # helper functions for login/register

Código

---

## ✅ Checklist
- [ ] Create Login and Register screens.  
- [ ] Add navigation between screens.  
- [ ] Implement form validation with Formik + Yup.  
- [ ] Add mock authentication logic.  
- [ ] Persist session with AsyncStorage or SecureStore.  
- [ ] Implement logout functionality.  

---

## 📌 Notes
- Start with mock authentication to simplify learning.  
- Later, replace with Firebase Auth or Supabase for real backend integration.  
- Always validate user input to prevent invalid data.  
- Keep authentication logic modular (separate helpers in `/utils`).  
