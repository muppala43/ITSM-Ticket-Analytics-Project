# ITSM-Ticket-Analytics-Project
ML-powered ITSM ticket analysis and forecasting project
# 🎯 TicketSense: ITSM Ticket Analytics with Machine Learning

This project applies machine learning and time-series forecasting to IT Service Management (ITSM) ticket data. The goal is to enhance incident handling, prioritize issues, and forecast operational workloads.

---

## 📌 Project Objectives

- ✅ Predict high-priority incidents
- 📈 Forecast monthly ticket volume using Facebook Prophet
- 🏷️ Classify support categories (CI_Cat) for auto-routing
- ⚠️ Detect tickets at high risk of failure or escalation

---

## 🧠 Machine Learning Models Used

- Random Forest Classifier (for classification tasks)
- Prophet (Facebook's time-series forecasting library)

---

## 📊 Key Features Engineered

- `High_Priority`: Flag for tickets with priority ≤ 2  
- `Ticket_Failed`: Risk flag based on closure codes  
- `Open_Year`, `Day_of_Week`, `Hour`: Temporal features  
- Encoded fields for `CI_Cat`, `Closure_Code`, etc.

---

## 🚀 How to Use

1. Clone or download this repository
2. Open the notebook `TicketSense.ipynb` in Jupyter
3. Run each cell step-by-step to explore preprocessing, modeling, and forecasting

---

## 👨‍💻 Author

**MUPPALA DILLIP** 
---

## 🧾 License

This project is open for educational and portfolio use.

