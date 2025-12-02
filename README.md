# Smart Cyberbullying Detector

## Overview  
Smart Cyberbullying Detector is a machine learning based system designed to classify text as bullying or non-bullying. The model uses Natural Language Processing (NLP) techniques such as text cleaning and TF-IDF vectorization, along with a tuned Linear SVC classifier. A Flask-based web interface allows users to analyze text in real time and receive predictions instantly.

---

## Problem Statement  
Cyberbullying has become a serious concern across social media platforms, messaging applications, and online communities. Manual moderation is often slow and cannot keep pace with the volume of content being generated every second.

This project aims to develop an automated cyberbullying detection system that processes input text, applies NLP techniques, and predicts whether the content is bullying or non-bullying. The goal is to support safer online communication by identifying harmful messages early.

---

## Features  
- Real-time cyberbullying detection  
- Text preprocessing with custom stopwords  
- TF-IDF based feature extraction  
- Tuned Linear SVC machine learning model  
- Flask-based web application  
- Modern and responsive HTML/CSS interface  

---

## Technologies Used  
- Python  
- Flask  
- Scikit-learn  
- TF-IDF Vectorizer  
- HTML, CSS (Bootstrap), Jinja2  
- Pickle for model and vectorizer loading  

---

## Project Structure  

```
Smart-Cyberbullying-Detector/
│
├── app.py                                 # Flask application
├── index.html                             # Web UI template
├── dataset.csv                            # Training dataset
├── tfidfvectoizer.pkl                     # Saved TF-IDF vocabulary
├── LinearSVCTuned.pkl                     # Trained ML model
├── stopwords.txt                          # Custom stopword list
├── Cyber Bulling Detection Using Python.ipynb   # Notebook
└── README.md                              # Project documentation
```

---

## How It Works  

1. User enters text in the web application.  
2. The text is transformed using the saved TF-IDF vocabulary.  
3. The machine learning model predicts whether the text is bullying or non-bullying.  
4. The result is displayed on the webpage with visual styling.

---

## Installation and Setup  

### Step 1: Clone the Repository  
```
git clone https://github.com/gauravyadav0322/Smart-Cyberbullying-Detector.git
cd Smart-Cyberbullying-Detector
```

### Step 2: Install Dependencies  
```
pip install -r requirements.txt
```

### Step 3: Run the Application  
```
python app.py
```

### Step 4: Open in Browser  
Open the following link:  
```
http://localhost:5000
```

---

## Model Details  
- Algorithm: Linear SVC  
- Vectorizer: TF-IDF with custom stopwords  
- Labels:  
  - 1 = Bullying  
  - 0 = Non-bullying  

---

## Future Improvements  
- Multi-class bullying type detection  
- Deep learning-based classification  
- API integration for mobile apps or chat monitoring  
- Cloud deployment  
- Real-time streaming detection  

---

## License  
This project is open-source. You may use, modify, or improve it as needed.
