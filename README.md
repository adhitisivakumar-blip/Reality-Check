# 🛡️ Reality Check: A Real-Time Cloud-Based Big Data Analytics Framework for Detecting Fake News, Misinformation, and Soft Misinformation

Reality Check is an intelligent web-based misinformation detection system designed to identify and classify **Fake News**, **Misinformation**, **Soft Misinformation**, and **Real Content** from social media posts and reel captions. The system combines **Machine Learning**, **Natural Language Processing (NLP)**, and **rule-based contextual analysis** to provide users with explainable predictions, highlighted trigger words, confidence scores, and corrective information to promote responsible digital content consumption.

---

# 📖 Project Overview

With the exponential growth of social media, false and misleading information spreads faster than ever before. Traditional manual fact-checking methods struggle to keep pace with the volume and speed of online content.

Reality Check addresses this challenge by developing a **real-time cloud-ready misinformation detection framework** capable of analyzing user-generated content instantly. Unlike conventional systems that focus only on fake news, this project also detects **soft misinformation**—content that appears motivational or harmless but subtly promotes unrealistic expectations or misleading narratives.

The application not only classifies content but also explains *why* it was flagged, highlights suspicious keywords, and provides users with a healthier or factually correct perspective.

---

# ✨ Features

- 🔍 Detects Fake News, Misinformation, Soft Misinformation, and Real Content
- 🧠 Machine Learning-based text classification using Logistic Regression
- 📄 TF-IDF vectorization for feature extraction
- 🎯 Rule-based detection for Soft Misinformation
- 🚨 Trigger keyword highlighting
- 📊 Confidence score prediction
- 💡 Corrective and healthier perspectives for flagged content
- 🎥 Separate analysis for Social Media Posts and Reel Captions
- 📈 Detection Dashboard with analytics and visualizations
- ☁️ Cloud-ready scalable architecture
- 🖥️ Modern responsive web interface built with Flask

---

# 💻 Tech Stack

### Programming Language
- Python

### Backend
- Flask

### Machine Learning
- Scikit-learn
- Logistic Regression
- TF-IDF Vectorizer

### Data Processing
- Pandas
- Regular Expressions (re)

### Model Storage
- Pickle

### Frontend
- HTML5
- CSS3
- JavaScript

### Data Visualization
- Chart.js
- Chart.js Word Cloud Plugin

### Dataset
- Kaggle Fake and Real News Dataset

---

# 📂 Project Structure

```text
RealityCheck/
│
├── model/
│   ├── model.pkl
│   └── vectorizer.pkl
│
├── preprocessing/
│   └── clean_text.py
│
├── static/
│   ├── style.css
│   └── images/
│
├── templates/
│   ├── index.html
│   ├── reel.html
│   ├── trends.html
│   └── about.html
│
├── app.py
├── requirements.txt
└── README.md
```

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/RealityCheck.git
```

Move into the project directory:

```bash
cd RealityCheck
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# ▶️ How to Run

Start the Flask server:

```bash
python app.py
```

Open your browser and navigate to:

```
http://127.0.0.1:5000
```

You can now:

- Analyze social media posts
- Analyze reel captions
- View the detection dashboard
- Learn more about the project through the About page

---

# 📸 Screenshots

> Add screenshots of the following pages:

- 🏠 Home Page
- 📝 Analyze Post
- 🎥 Analyze Reel
- 📊 Detection Dashboard
- ℹ️ About Page

---

# 🚀 Future Enhancements

- Real-time social media API integration (X/Twitter, Instagram, Reddit)
- Deep Learning models such as BERT or RoBERTa
- Multilingual misinformation detection
- Image and video misinformation detection
- Explainable AI (XAI) visual explanations
- Live fact-checking using trusted news APIs
- User reporting and community moderation
- Cloud deployment on AWS, Azure, or Google Cloud
- Personalized misinformation awareness recommendations
- Mobile application support

---

# 👩‍💻 Author

**Adhiti Sivakumar**

Bachelor of Engineering (Computer Science and Engineering)

SIMATS Engineering

Capstone Project

---

## ⭐ Project Highlights

- ✅ Real-Time Fake News Detection
- ✅ Misinformation Classification
- ✅ Soft Misinformation Detection
- ✅ Explainable AI-Based Predictions
- ✅ Confidence Score Generation
- ✅ Trigger Keyword Highlighting
- ✅ Cloud-Ready Architecture
- ✅ Interactive Detection Dashboard
- ✅ User-Centric Corrective Guidance

---

### ⭐ If you found this project interesting, consider giving it a star on GitHub!
