# Health-Diagnostics-Platform-
# 🩺 Health Status Diagnosis Web Application

This web application is built using **Streamlit** and provides users with an interactive, user-friendly way to assess their **medical** and **mental health** status. By inputting basic parameters, users can get quick health predictions and personalized recommendations powered by machine learning models.

---

## 🚀 Features

- **Medical Health Diagnosis 🫀**  
  Evaluate your physical health using clinical parameters.

- **Mental Health Diagnosis 🧠**  
  Get insights into your mental well-being based on lifestyle and emotional indicators.

---

## 🗂️ File Structure
- **App.py: Main Streamlit application file**
- **Images/: Contains UI-related images**
- **LR_model.pkl:Logistic Regression model for medical health**
- **DT_model.pkl:Decision Tree model for mental health**
- **Medical Health.ipynb: Notebook for training the medical model**
- **Mental Health.ipynb: Notebook for training the mental health model**
- **README.md: Documentation file providing an overview of the project**
- **Requirements.txt: List of required Python packages for the project**

## 🧠 Model Details

### 🫀 Medical Health Prediction
- **Model**: Logistic Regression (`LR_model.pkl`)
- **Input Features**:
  - Gender
  - Age
  - Blood Pressure
  - Cholesterol Level
  - BMI
  - Smoking Status
  - Diabetes Status

### 🧠 Mental Health Prediction
- **Model**: Decision Tree (`DT_model.pkl`)
- **Input Features**:
  - Gender
  - Country
  - Occupation
  - Stress Levels
  - Coping Mechanisms
  - Self-care History

---

## 💻 How to Run the App

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/health-status-diagnosis-app.git
cd health-status-diagnosis-app
---

###2. Install Dependencies
```bash
pip install -r Requirements.txt
