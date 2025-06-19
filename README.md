# -AI-Powered-Mental-Health-Monitoring-and-Support-System-Using-Django-and-Machine-Learning
A web-based mental health monitoring and support system using Django and Machine Learning with role-based access for Patients, Guardians, and Healthcare Providers.
# 🧠 AI-Powered Mental Health Monitoring and Support System  
**Using Django and Machine Learning**

## 📘 Project Description

This is a web-based mental health monitoring and support system built using **Django**, **Machine Learning**, and **role-based access control**. The system enables **Patients** to assess their mental well-being using an emoji-based input system. Based on this input, ML models predict their mental state and provide **personalized recommendations**. The system also alerts **Guardians** and **Healthcare Providers** in real-time for timely intervention.

---

## 🎯 Features

✅ Emoji-based mood input interface  
✅ Real-time prediction of mental health using ML models  
✅ Role-based dashboards for Patients, Guardians, and Providers  
✅ Emergency alert system for high-risk mental states  
✅ Personalized activity and wellness recommendations  
✅ History tracking of patient mood data  
✅ Secure login and user data encryption  
✅ Responsive design for desktop and mobile use  

---

## 👨‍⚕️ User Roles

| Role               | Features                                                                 |
|--------------------|--------------------------------------------------------------------------|
| **Patient**         | Submit mood via emoji, view health insights, receive advice              |
| **Guardian**        | Monitor assigned patients, get alerts, assign activities/medications     |
| **Healthcare Provider** | Track multiple patients, provide recommendations, manage interventions |

---

## 🏗️ System Architecture

- **Frontend**: HTML5, Bootstrap 5, JavaScript  
- **Backend**: Django 4.x (Python 3.10+)  
- **Database**: SQLite  
- **ML Models**: Random Forest, Decision Tree, XGBoost  
- **Libraries Used**: scikit-learn, xgboost, pandas, numpy, joblib  

---

## 🛠️ Key Components

- **User Authentication**: Custom user model with role-based access  
- **Mood Tracker**: Emoji-based UI for patients to submit mental states  
- **Prediction Engine**: ML model integration to classify mental health  
- **Recommendation System**: Based on prediction, suggests wellness tips  
- **Alert System**: Sends real-time alerts to guardians/providers  
- **Data Storage**: Secure and encrypted records of assessments & actions  

---

## 💡 Machine Learning Models Used

- **Random Forest Classifier**  
- **Decision Tree Classifier**  
- **XGBoost Classifier**

All models are trained on mood-based datasets and saved using `joblib` for fast inference in Django.

---

## 🖥️ Project Structure
mental-health-monitoring-django-ml/
├── manage.py
├── requirements.txt
├── README.md
├── .gitignore
├── ml_models/ # Trained model files (.pkl or .joblib)
├── mentalhealth/ # Django app: models, views, URLs
├── templates/ # HTML files
├── static/ # CSS, JS, images
├── users/ # Custom user model & authentication
└── db.sqlite3 # SQLite database

🔐 Authentication System
The platform supports three user types:

Patient (default role)

Guardian

Healthcare Provider

Users must register and will be redirected to their role-based dashboards upon login.

📊 Expected Output
Accurate mental health prediction (>85%)

Real-time alerts and timely support

Mood history analysis and pattern tracking

Increased early interventions via connected caregivers

📈 Future Enhancements
Mobile app support (React Native or Flutter)

Integration with wearable devices for sensor-based data

Voice or chatbot interface for mood input

Admin dashboard with analytics and patient insights

📃 License
This project is licensed under the MIT License – see the LICENSE file for details.

👤 Author
Chetan Ullagaddi
📍 Belagavi, Karnataka, India
📧 ullagaddichetan2@gmail.com
🔗 LinkedIn:https://www.linkedin.com/in/chetan-ullagaddi-31b999254

🌟 Show your support
If you like this project, please ⭐️ the repository and share it!
