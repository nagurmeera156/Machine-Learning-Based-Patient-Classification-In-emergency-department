🏥 Machine Learning Based Patient Classification in Emergency Department
📌 Project Overview

This project is a Django-based web application that leverages Machine Learning to classify patients in an emergency department.
It integrates a trained ML model (alexmodel.pkl) into a Django REST framework for making predictions on patient data.

🚀 Features

🔹 Patient classification using ML model

🔹 Django-powered backend with REST API

🔹 SQLite3 database integration (db.sqlite3)

🔹 Scalable and modular architecture

🔹 Easy deployment on cloud platforms

📂 Project Structure
EmergencyClassification/
│── manage.py               # Django management script
│── db.sqlite3              # SQLite database
│── alexmodel.pkl           # Trained ML model
│── requirement.txt         # Python dependencies
│── .gitignore              # Ignored files for Git
└── ... (Django apps & modules)

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/EmergencyClassification.git
cd EmergencyClassification

2️⃣ Create Virtual Environment
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows

3️⃣ Install Dependencies
pip install -r requirement.txt

4️⃣ Run Database Migrations
python manage.py migrate

5️⃣ Start the Development Server
python manage.py runserver


Now visit: http://127.0.0.1:8000/

📊 Machine Learning Model

The ML model (alexmodel.pkl) is pre-trained and stored in the repository.

It is loaded in Django views to make predictions for patient classification.

🛠️ Technologies Used

Python 3.x

Django 4.0

Django REST Framework

scikit-learn / ML libraries

SQLite3
