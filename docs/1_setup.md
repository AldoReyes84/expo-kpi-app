# Setup Guide

## 📌 Overview
This document describes the initial setup required to start the **Expo KPI App** project.  
The goal of Sprint 1 is to configure the development environment, create the repository, and run the app with Expo Go.

---

## 🔧 Environment Requirements
- **Node.js** version 18 or higher  
- **npm** or **yarn** package manager  
- **Expo CLI** installed globally  
  ```bash
  npm install -g expo-cli
Visual Studio Code with recommended extensions:

React Native Tools

ESLint

Prettier

🚀 Steps
1. Create the repository
Go to GitHub and create a new repository named expo-kpi-app.

Initialize with a README file.

Add a .gitignore file for Node/Expo projects.

2. Initialize the project with Expo
bash
# Create a new Expo project
npx create-expo-app expo-kpi-app

# Navigate into the project folder
cd expo-kpi-app

# Start the development server
npm start
3. Run the app
Install Expo Go on your mobile device.

Scan the QR code from the terminal or browser.

Verify that the default Expo app runs successfully.

4. Push to GitHub
bash
git init
git remote add origin https://github.com/<your-username>/expo-kpi-app.git
git add .
git commit -m "Initial setup with Expo"
git push -u origin main
📂 Project Structure
Código
expo-kpi-app/
 ├── assets/          # Static resources (images, fonts, sounds)
 ├── components/      # Reusable components
 ├── screens/         # Screens (Login, Dashboard, KPI Detail)
 ├── navigation/      # Navigation configuration
 ├── App.js           # Entry point
 └── README.md        # Documentation
✅ Checklist
[ ] Repository created on GitHub

[ ] Expo CLI installed and verified

[ ] Project initialized with create-expo-app

[ ] App runs in Expo Go

[ ] Initial commit pushed to GitHub

[ ] Documentation updated with setup instructions

📌 Notes
Keep dependencies updated to avoid compatibility issues.

Use ESLint and Prettier to maintain consistent code style.

Document every step in bilingual format (English/Spanish) for portfolio purposes.
