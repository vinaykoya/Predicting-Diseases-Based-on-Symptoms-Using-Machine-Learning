# 🩺 Symptoms Based Disease Prediction System

Symptoms Based Disease Prediction System is an intelligent healthcare web application designed to predict possible diseases from user symptoms using Machine Learning models and provide guidance through an AI health chatbot.

The system integrates prediction, database management, and evaluation metrics to deliver accurate and explainable healthcare assistance.

---

# 1️⃣ Overview

The application combines Machine Learning, Flask, and MySQL database integration to provide a complete healthcare prediction platform.

⭐ **Core Objectives**

• Predict diseases based on symptoms
• Provide early health insights to users
• Store patient & doctor data securely
• Evaluate ML model performance
• Enable interactive healthcare assistance

⭐ **Key Features**
```
✅ Machine Learning Disease Prediction
✅ AI Health Chatbot Support
✅ Doctor Registration & Login System
✅ Patient Registration & Records
✅ MySQL Database Integration
✅ Model Accuracy, Precision, Recall & F1 Evaluation
✅ Interactive Web Dashboard
```
---

# 2️⃣ Demos

The system works like an intelligent health assistant that predicts diseases and provides recommendations.

### 🔍 Workflow Demonstration

User registers/login
User selects symptoms
System compares symptoms with trained dataset
Machine Learning model predicts disease
Chatbot provides health guidance
Prediction results stored in database
Evaluation metrics available for analysis

(Add screenshots or demo video here)

---

# 3️⃣ Project Structure

```
Symptoms-Based-Disease-Prediction/
│
├── dataset/                  # Training dataset
├── env/                      # Virtual environment (ignored in GitHub)
├── profilepic/               # User profile images
├── static/                   # CSS, JS, images
├── templates/                # HTML templates
│
├── ai_health_bot.py          # Chatbot logic
├── disease_detection.py      # Disease prediction module
├── Similarity.py             # Symptom similarity matching
├── symptoms_list.py          # Symptoms database
│
├── doctor_registration.py
├── patient_registration.py
├── DBConnection.py           # MySQL database connection
├── database.sql              # Database schema
│
├── ML_Evaluations.py         # Model evaluation metrics
├── index.py                  # Main Flask app
│
├── accuracy.png
├── precision.png
├── recall.png
├── fscore.png
│
├── requirements.txt
└── README.md
```

---

# 4️⃣ Run Locally

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt
python index.py
```

Open in browser:

```
http://127.0.0.1:5000
```

---

# 5️⃣ Database Setup (MySQL)

### Create database

```sql
CREATE DATABASE health_prediction;
USE health_prediction;
```

### Import tables

```bash
mysql -u root -p health_prediction < database.sql
```

### Update credentials in DBConnection.py

```python
host="localhost"
user="root"
password="your_password"
database="health_prediction"
```

---

# 6️⃣ Deployment Guide

You can deploy this project using:

• Render (Flask deployment)
• Railway
• AWS EC2
• PythonAnywhere

For deployment, ensure:

• MySQL database is hosted online
• requirements.txt is included
• Environment variables configured

---

# 7️⃣ Tech Stack

• Python
• Flask
• Scikit-learn
• Pandas / NumPy
• MySQL
• HTML / CSS / Bootstrap

---

# 8️⃣ Conclusion

Symptoms Based Disease Prediction System demonstrates how Machine Learning can assist in early healthcare decision-making by analyzing symptoms and predicting diseases.

The system combines prediction models, chatbot assistance, and database management to create a complete AI-driven healthcare web solution.

---

# 👨‍💻 Author

**Vinay**
GitHub: https://github.com/your-username
