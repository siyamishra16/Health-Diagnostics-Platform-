# Health-Diagnostics-Platform-
This web application is built using Streamlit and provides users with an interactive, user-friendly way to assess their medical and mental health status. By inputting basic parameters, users can get quick health predictions and personalized recommendations powered by machine learning models.

🚀 Features
Medical Health Diagnosis 🫀
Evaluate your physical health using clinical parameters.

Mental Health Diagnosis 🧠
Get insights into your mental well-being based on lifestyle and emotional indicators.

🗂️ File Structure
bash
Copy
Edit
├── App.py                    # Main Streamlit application file
├── LR_model.pkl             # Logistic Regression model for medical health
├── DT_model.pkl             # Decision Tree model for mental health
├── Medical Health.ipynb     # Notebook for training the medical model
├── Mental Health.ipynb      # Notebook for training the mental health model
├── Requirements.txt         # Python dependencies
├── README.md                # Project documentation
├── bad.png                  # Image assets for prediction result
├── bad1.png
├── fair.png
├── fair1.png
├── good.png
└── good1.png
📌 Note: All image and model files are placed directly in the project root.

🧠 Model Details
🫀 Medical Health Prediction
Model: Logistic Regression (LR_model.pkl)

Input Features:

Gender

Age

Blood Pressure

Cholesterol Level

BMI

Smoking Status

Diabetes Status

🧠 Mental Health Prediction
Model: Decision Tree (DT_model.pkl)

Input Features:

Gender

Country

Occupation

Stress Levels

Coping Mechanisms

Self-care History

💻 How to Run the App
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/health-status-diagnosis-app.git
cd health-status-diagnosis-app
2. Install Dependencies
bash
Copy
Edit
pip install -r Requirements.txt
3. Launch the App
bash
Copy
Edit
streamlit run App.py
🧭 How to Use
Choose either Medical Health or Mental Health from the sidebar.

Enter the required information.

Click Predict to get your health status and helpful suggestions.

📦 Requirements
Install the necessary Python packages via:

bash
Copy
Edit
pip install -r Requirements.txt
Key Dependencies
streamlit

pandas

numpy

scikit-learn

pickle

⚠️ Disclaimer
This app is for educational and demonstration purposes only. It does not replace professional medical advice. Always consult a healthcare provider for medical or psychological concerns.

🛠️ Possible Improvements
Add data visualizations to results

Store user sessions/history

Deploy online with Streamlit Cloud or Heroku

Improve model accuracy with more diverse datasets

