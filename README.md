# Instagram Spam Detection using NLP

## 📌 Project Overview
This project focuses on building an AI-based system to detect spam comments on Instagram posts. Since labeled Instagram spam datasets are not publicly available, the model is trained using the YouTube Spam Collection Dataset, as spam patterns are similar across social media platforms.

## 📂 Dataset
- YouTube Spam Collection Dataset (Kaggle)
- Includes spam and non-spam comments from multiple YouTube videos

## 🛠 Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Natural Language Processing (NLP)
- TF-IDF with N-grams
- Logistic Regression

## ⚙️ Methodology
1. Combined multiple YouTube spam datasets into a single dataset
2. Performed text preprocessing and cleaning
3. Applied TF-IDF vectorization with N-grams
4. Trained a Logistic Regression classifier
5. Evaluated the model using accuracy and classification metrics
6. Tested the model on Instagram-like comments

## 📈 Results
- Achieved over **90% accuracy**
- Successfully classified spam and legitimate comments

## 📌 Use Case
The trained model can be used to detect spam comments on Instagram or similar social media platforms.

## 🚀 Future Improvements
- Integration with Instagram API for real-time comment analysis
- Use of advanced models like BERT or ALBERT
- Deployment as a web application

## 👤 Author
- **Bhavin Sangani**
