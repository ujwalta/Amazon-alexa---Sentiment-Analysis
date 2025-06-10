📌 Amazon Alexa Reviews - Sentiment Analysis
https://img.shields.io/badge/Python-3.8%252B-blue

https://img.shields.io/badge/Scikit--learn-1.0+-orange

https://img.shields.io/badge/Flask-2.0+-lightgrey

https://img.shields.io/badge/Streamlit-1.0+-ff69b4

A machine learning project to classify sentiment (positive/negative) from Amazon Alexa product reviews using NLP and ensemble models.

🚀 Features
Exploratory Data Analysis with interactive visualizations

Text Preprocessing: Stemming, stopword removal, CountVectorizer

ML Models: Random Forest (94.2% accuracy), XGBoost (94.1% accuracy)

Deployment:

Flask API for batch/single predictions

Streamlit web interface

📦 Installation
Clone the repo:

bash
git clone https://github.com/yourusername/Amazon-alexa-review---Sentiment-Analysis.git

cd Amazon-alexa-review---Sentiment-Analysis

Install dependencies:

bash

pip install -r requirements.txt

Download NLTK stopwords:

python

import nltk

nltk.download('stopwords')

🛠️ Usage

Option 1: Flask API

bash

python api.py

Single Prediction: Send POST request with JSON {"text": "your review"}

Bulk Prediction: Upload CSV via /predict endpoint

Option 2: Streamlit UI

bash

streamlit run app.py

https://demo.gif (Add a screenshot/GIF)

📂 Project Structure
text
├── Data/
│   └── amazon_alexa.tsv          # Raw dataset
├── Models/
│   ├── model_xgb.pkl            # Trained XGBoost model
│   └── countVectorizer.pkl      # Fitted CountVectorizer
├── api.py                       # Flask API
├── app.py                       # Streamlit app
└── EDA_Modeling.ipynb           # Google colab with full analysis

📊 Results

Model	Accuracy	Precision	Recall

Random Forest	94.2%	0.94	0.99

XGBoost	94.1%	0.94	0.99

https://confusion_matrix.png (Add image)

🤝 Contributing

Pull requests welcome! For major changes, open an issue first.

📄 License

MIT

🎨 Pro Tips:

Replace placeholder images with actual screenshots/GIFs

Add a "Demo" section with GIF/video

Include badges for Python version, dependencies, etc. (use shields.io)
