This project is an end-to-end AI-powered web application that intelligently detects whether a news article is real or fake using Natural Language Processing (NLP) and a machine learning model. Built using Python (Flask) and enhanced with interactive features, it offers an intuitive experience for users to analyze text or uploaded documents in real time.

## 🔍 Key Features

* ✅ Real vs Fake news classification using ML (PassiveAggressiveClassifier)
* 📁 Supports .txt and .pdf file upload for predictions
* 🎙 Voice-to-text input using Web Speech API
* 👤 User login/registration system with session management
* 🌗 Dark/light mode with persistent theme toggle
* 📱 Fully responsive, modern UI using HTML5, CSS3

## 💡 Tech Stack

* *Frontend*: HTML, CSS, JavaScript
* *Backend*: Python, Flask
* *ML/NLP*: Scikit-learn, TfidfVectorizer
* *Database*: SQLite
* *Extras*: Speech Recognition, File Handling, Secure Login

## 🚀 How It Works

1. User logs in or registers.
2. Enters news content or uploads a .txt/.pdf file.
3. The content is processed through a TF-IDF vectorizer and ML model.
4. The app returns a *prediction* (Fake ✅ or Real ❌) with *confidence*
