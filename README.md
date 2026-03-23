# Fake News Detection 📰

##  Project Overview
This project detects whether a news article is Fake or Real using Machine Learning.

##  Dataset
Fake.csv → Contains fake news articles
True.csv → Contains real news articles

##  Technologies Used
Python
Pandas, NumPy
Scikit-learn
NLP (NLTK, TF-IDF)
Matplotlib, Seaborn

##  Methodology
- Data Collection Loaded Fake and Real datasets Combined and shuffled data
- Data Preprocessing Converted text to lowercase Removed special characters Removed stopwords using NLP
- Feature Engineering Used TF-IDF Vectorization to convert text → numerical features
- Model Building Applied Logistic Regression
- Model Evaluation Evaluated using: Accuracy,Precision,Recall,F1-score

##  Model
- Logistic Regression

##  Results
Metric	Score
Accuracy	~95%
Precision	High
Recall	High

##  Example Prediction

Input:

"Breaking: Government announces new policy changes"

Output:

Real News 

##  Output
<img width="1412" height="919" alt="Screenshot 2026-03-22 203944" src="https://github.com/user-attachments/assets/f7f13372-4737-4692-8df5-f46214638dd8" />
<img width="1016" height="346" alt="Screenshot 2026-03-22 203954" src="https://github.com/user-attachments/assets/312cfd45-f17f-4d9b-88f5-49a0d3f28ee5" />
<img width="871" height="212" alt="Screenshot 2026-03-22 204003" src="https://github.com/user-attachments/assets/83c9caaf-9c5d-4a8f-84d0-a3a7ae681c11" />

##  Future Improvements
🔹 Implement Deep Learning models (LSTM, BERT)
🔹 Deploy as a web app using Streamlit
🔹 Improve accuracy with advanced NLP techniques
🔹 Add real-time news API integration

##  Author
surisetty deepika
