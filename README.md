# 💊 Drug Recommendation System

A machine learning-powered web application that analyzes user reviews to recommend suitable drugs. It uses natural language processing (NLP) and sentiment analysis to classify reviews and suggest medications accordingly.

This project helps users — especially patients and healthcare providers — make more informed decisions by examining drug sentiment and review patterns.

---

## 🖼️ Screenshots

### 🔹 Homepage
<img src="https://github.com/SubbuPachakarla/Drug-Recommendation-Sysytem/blob/main/screen%20shots/home%20page.png" width="800"/>

### 🔹 Input Form
<img src="https://github.com/SubbuPachakarla/Drug-Recommendation-Sysytem/blob/main/screen%20shots/prediction.png" width="800"/>

### 🔹 Recommendation Result
<img src="Drug_Recommendation_System/screenshots/result_output.png" width="800"/>

---

## 📽️ Demo Video

▶️ [![Watch the demo](https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)

---

## 🚀 Features

- 🧠 Sentiment classification using NLP
- 💬 Text analysis of drug reviews
- 🔍 Drug recommendations based on positivity score
- 🌐 Web-based Django interface
- 💾 Large files handled via Git LFS

---

## 🛠 Tech Stack

- Python 3.x
- Django
- scikit-learn
- pandas, numpy
- NLTK / spaCy
- Git LFS
- HTML + CSS (Django templates)

---

## 📁 Folder Structure

Drug_Recommendation_System/

├── app/ # Django app

├── Drug_Recommendation_System/ # Project settings

├── models/ # Trained ML models

├── static/ # CSS, JS, images

├── templates/ # HTML templates

├── screenshots/ # Project screenshots

├── requirements.txt

├── .gitignore

└── README.md


---

## 🧪 Local Setup Instructions

1. **Clone the repo**
   ```bash
   git clone https://github.com/SubbuPachakarla/Drug-Recommendation-Sysytem.git
   cd Drug-Recommendation-Sysytem

2.**Create a virtual environment**
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. **Install dependencies**
   pip install -r requirements.txt
4.**Run migrations**
   python manage.py migrate
5. **Start the server**
   python manage.py runserver
6. **Visit**
   http://127.0.0.1:8000/


## 🔮 Future Improvements

🎨 Improve UI with Bootstrap or Tailwind
🤖 Add chatbot interface for drug queries
📊 Visualize review trends over time
🧬 Add filters (age, gender, conditions)
☁️ Full cloud deployment with database support

## 👨‍💻 Author
Subrahmanyam Pachakarla
🔗 https://github.com/SubbuPachakarla

