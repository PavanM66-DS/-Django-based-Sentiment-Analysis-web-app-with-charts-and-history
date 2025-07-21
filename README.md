# 📊 Sentilytics – Sentiment Analysis Web App

**Sentilytics** is a full-stack Django web application that performs **sentiment analysis** on user-submitted text using natural language processing (NLP) tools like **TextBlob** or **scikit-learn**. It stores the sentiment results in a database and provides users with a dashboard to visualize their sentiment trends over time using **Chart.js**.

## 🔍 Features

- ✍️ Input any text and get instant sentiment results (Positive / Negative / Neutral)
- 🧠 Uses **TextBlob** or **scikit-learn** for NLP sentiment scoring
- 🗃️ Stores each sentiment entry in a database (SQLite/MySQL)
- 📊 Visualizes sentiment trends with **Chart.js** line/bar charts
- 👤 User authentication system with login/logout
- 🕓 View sentiment history with timestamps

## 🛠️ Technologies Used

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, Bootstrap, JavaScript
- **NLP**: TextBlob or scikit-learn
- **Charts**: Chart.js
- **Database**: SQLite (default) or MySQL

## 🚀 How to Run

```bash
git clone https://github.com/PavanM66-DS/sentilytics-django.git
cd sentilytics-django
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
