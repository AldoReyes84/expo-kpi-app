# KPI Dashboard Guide

## 📌 Overview
This document describes the implementation of the **KPI Dashboard** for the Expo KPI App.  
The goal of Sprint 3 is to build a main screen that displays a list of KPIs and allows navigation to detailed views.

---

## 🔧 Requirements
- Project initialized with Expo (Sprint 1).  
- Authentication implemented (Sprint 2).  
- Libraries:
  - `react-navigation` for navigation between screens.
  - `react-native-paper` or `react-native-elements` for UI components.
  - Optional: chart libraries (`react-native-chart-kit`, `victory-native`) for KPI visualization.

---

## 🚀 Steps

### 1. Create Dashboard Screen
- Design a **DashboardScreen** that lists KPIs.  
- Each KPI should be displayed as a card or list item.  
- Include basic information (title, value, trend).

### 2. Add Navigation to Detail Screen
- Create a **KPIDetailScreen**.  
- Configure navigation from Dashboard → Detail using `react-navigation`.  
- Pass KPI data as parameters to the detail screen.

### 3. Display KPI Details
- Show detailed metrics for the selected KPI.  
- Include breakdowns by category, time period, or other dimensions.  
- Use charts or tables for better visualization.

### 4. Handle Data Source
- Start with **mock data** (local JSON file).  
- Later, integrate with a backend or API for real KPI data.  
- Ensure data is modular and reusable.

### 5. Improve UI/UX
- Add icons or colors to represent KPI status (e.g., green for positive trend, red for negative).  
- Provide filters or search functionality to quickly find KPIs.  
- Keep layout responsive and clean.

---

## 📂 Suggested Structure
expo-kpi-app/
├── screens/
│    ├── DashboardScreen.js
│    └── KPIDetailScreen.js
├── data/
│    └── kpis.json   # mock KPI data
└── components/
└── KPIItem.js  # reusable component for KPI cards

Código

---

## ✅ Checklist
- [ ] Create DashboardScreen with KPI list.  
- [ ] Create KPIDetailScreen for detailed metrics.  
- [ ] Configure navigation between screens.  
- [ ] Implement mock KPI data in JSON.  
- [ ] Display KPI details with charts or tables.  
- [ ] Add basic UI/UX improvements (icons, colors, filters).  

---

## 📌 Notes
- Start with mock data to simplify development.  
- Later, replace with API calls for real KPI data.  
- Keep KPI components modular for reuse across screens.  
- Document each KPI’s structure and data source in `/docs/reports.md`. 
