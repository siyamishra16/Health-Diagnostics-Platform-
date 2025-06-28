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
```
### 2. Install Dependencies
```bash
pip install -r Requirements.txt
```
### 3. Launch the App
```bash
streamlit run App.py
```
## 🧭 How to Use
**1.Choose either Medical Health or Mental Health from the sidebar.**

**2.Enter the required information.**

**3.Click Predict to get your health status and helpful suggestions.**

### 📦 Requirements
Install the necessary Python packages via:

```bash
pip install -r Requirements.txt
```
Screenshots
-----------

<img src="https://github.com/user-attachments/assets/c95d5f6b-f0b3-4640-bbaa-1458ac433631" alt="just opening the app">
<p align="center">
  Figure 1. This is the UI while open the webapp.
</p>
<img src="https://github.com/user-attachments/assets/b800c3e5-df6c-4375-9cf1-04b9b5ae5076" alt="after prediction">
<p align="center">
  Figure 2. After prediction.
</p>

## ⚠️ Disclaimer

This app is for **educational and demonstration purposes only**.  
It does **not replace professional medical advice**.  
Always consult a healthcare provider for medical or psychological concerns.

---

## 🛠️ Possible Improvements

- Add data visualizations to results  
- Store user sessions/history  
- Deploy online with Streamlit Cloud or Heroku  
- Improve model accuracy with more diverse datasets

