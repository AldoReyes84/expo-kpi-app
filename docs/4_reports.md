# Drill-down Reports Guide

## 📌 Overview
This document describes the implementation of **drill-down reports** for the Expo KPI App.  
The goal of Sprint 4 is to add interactive charts and filters that allow users to explore KPI data in detail.

---

## 🔧 Requirements
- Project initialized with Expo (Sprint 1).  
- Authentication implemented (Sprint 2).  
- KPI Dashboard created (Sprint 3).  
- Libraries:
  - `react-native-chart-kit` or `victory-native` for charts.
  - `react-native-paper` or `react-native-elements` for UI components.
  - Optional: `date-fns` or `moment` for date filtering.

---

## 🚀 Steps

### 1. Create Reports Screen
- Add a **ReportsScreen** accessible from the Dashboard.  
- Display KPIs with charts (bar, line, pie).  
- Each chart should represent KPI trends over time or categories.

### 2. Implement Drill-down Functionality
- Allow users to tap on a KPI chart to view detailed breakdowns.  
- Show additional metrics (e.g., by department, region, or time period).  
- Use navigation to move between summary and detail views.

### 3. Add Filters
- Provide filters for:
  - Date range (daily, weekly, monthly).  
  - Category or dimension (e.g., sales, operations).  
- Update charts dynamically based on selected filters.

### 4. Handle Data Source
- Start with **mock data** in JSON format.  
- Later, integrate with backend APIs for real KPI data.  
- Ensure data is structured to support breakdowns.

### 5. Improve Visualization
- Use colors and legends to differentiate categories.  
- Add tooltips or labels for clarity.  
- Keep charts responsive and easy to read.

---

## 📂 Suggested Structure
expo-kpi-app/
├── screens/
│    └── ReportsScreen.js
├── components/
│    └── KPIChart.js   # reusable chart component
├── data/
│    └── reports.json  # mock report data
└── utils/
└── filters.js    # helper functions for filtering data

Código

---

## ✅ Checklist
- [ ] Create ReportsScreen with charts.  
- [ ] Implement drill-down functionality for KPIs.  
- [ ] Add filters for date range and categories.  
- [ ] Use mock data for initial implementation.  
- [ ] Improve visualization with colors, legends, and labels.  
- [ ] Document data structure and filtering logic.  

---

## 📌 Notes
- Begin with mock data to simplify development.  
- Replace with API integration once backend is ready.  
- Keep chart components modular for reuse.  
- Ensure filters are intuitive and easy to use. 
