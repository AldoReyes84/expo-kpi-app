# Expo KPI App

## 📌 Descripción (ES)
Aplicación móvil desarrollada con **React Native + Expo** cuyo objetivo es:
- Implementar un sistema básico de **registro y login** para usuarios validados.
- Mostrar un **dashboard de KPIs** con métricas desglosables.
- Servir como proyecto de aprendizaje *hands-on* para React Native, Expo y buenas prácticas de documentación.

Este proyecto forma parte de mi portafolio y está orientado a la práctica de:
- Autenticación segura.
- Visualización de datos con librerías gráficas.
- Organización modular y documentación bilingüe.

---

## 📌 Description (EN)
Mobile application built with **React Native + Expo** aimed at:
- Implementing a basic **user authentication system** (sign up / login).
- Displaying a **KPI dashboard** with drill-down metrics.
- Serving as a *hands-on* learning project for React Native, Expo, and professional documentation practices.

This project is part of my portfolio and focuses on:
- Secure authentication.
- Data visualization with chart libraries.
- Modular organization and bilingual documentation.

---

## 🚀 Setup

### Requisitos / Requirements
- Node.js (>= 18)
- npm o yarn
- Expo CLI (`npm install -g expo-cli`)
- Visual Studio Code con extensiones recomendadas:
  - React Native Tools
  - ESLint
  - Prettier

### Pasos iniciales / Initial steps
```bash
# Crear proyecto con Expo
npx create-expo-app expo-kpi-app

# Entrar al directorio
cd expo-kpi-app

expo-kpi-app/
 ├── assets/          # Recursos estáticos
 ├── components/      # Componentes reutilizables
 ├── screens/         # Pantallas (Login, Dashboard, KPI Detail)
 ├── navigation/      # Configuración de navegación
 ├── App.js           # Punto de entrada
 └── README.md        # Documentación

