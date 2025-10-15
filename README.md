# 🧠 NLP Project – Emotion and Sentiment Classification

This project focuses on **Natural Language Processing (NLP)** to classify text into different emotions and sentiments.  
The goal is to understand the emotional context behind text data — whether it expresses joy, anger, sadness, love, or other feelings — and categorize it using both **Machine Learning (ML)** and **Deep Learning (DL)** approaches.

---

## 📋 Project Overview

Human communication is full of emotions, and analyzing text to detect emotional intent can power many applications — such as social media analysis, chatbot empathy, mental health monitoring, and customer feedback insights.  

In this project, I built models that can classify textual data into **emotional** and **sentimental** categories using classical ML and deep learning algorithms.

---

## 🎯 Objectives

- Develop a text classification pipeline for **emotion detection** and **sentiment analysis**  
- Compare multiple **Machine Learning** and **Deep Learning** models  
- Preprocess, vectorize, and clean raw text data for optimal performance  
- Evaluate model accuracy using various metrics and visualization tools  

---

## 💡 Problem Statements

### 1. Emotion Classification
- **6 Emotions:** `['sadness', 'anger', 'love', 'surprise', 'fear', 'joy']` approximately **16,000 samples**

- **13 Emotions:** `['empty', 'sadness', 'enthusiasm', 'neutral', 'worry', 'surprise', 'love', 'fun', 'hate', 'happiness', 'boredom', 'relief', 'anger']` approximately **40,000 samples**


### 2. Sentiment Classification
- Binary classification of sentences: **Positive vs Negative**
- Dataset size: approximately **5,000 samples**

---

## ⚙️ Technologies & Tools

**Languages & Libraries:**
- Python, NumPy, Pandas, Matplotlib, Seaborn, Wordcloud
- Scikit-learn, TensorFlow, Keras  

**Techniques:**
- Text Preprocessing (cleaning, tokenizing, stopword removal)
- Feature Extraction using **TF-IDF Vectorization**
- Feature Scaling using **StandardScaler**
- Train-test splitting and Label Encoding
- Visualization using WordClouds

---

## 🧹 Data Preprocessing Steps

1. Text cleaning (lowercasing, punctuation and number removal, URL filtering)  
2. Tokenization  
3. Stopword removal  
4. Lemmatization or stemming  
5. TF-IDF vectorization  
6. Feature scaling using `StandardScaler`  
7. Generating WordClouds for each sentiment  
8. Splitting dataset into training and testing sets  

---

## 🤖 Machine Learning Models

Several algorithms were applied and compared:

- **Logistic Regression (LR)**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Classifier (SVC)**
- **Random Forest Classifier (RFC)**
- **Decision Tree Classifier (DTC)**
- **Multi-Layer Perceptron (MLP)**  
- **Ensemble Learning** for combined model performance  
- **Grid Search** for hyperparameter optimization  

**Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, Confusion Matrix  

---

## 🔬 Deep Learning Approach

For the deep learning part, an **LSTM (Long Short-Term Memory)** network was implemented using **Keras/TensorFlow**.

### Features:
- Used **Embedding layers** for sequence representation  
- Applied **EarlyStopping** to prevent overfitting  
- Trained and validated models for emotion classification  
- Achieved improved generalization for multi-emotion datasets  

---

## 🧩 Model Prediction Examples

Below are sample predictions from the trained **LSTM emotion classification model**.  
Each prediction includes the detected emotion and its confidence score.

| Input Text | Predicted Emotion | Confidence |
|-------------|------------------|-------------|
| I feel strong and good overall | **Joy** | 0.9940 |
| I'm grabbing a minute to post, I feel greedy wrong | **Anger** | 0.9840 |
| He was speechless when he found out he was accepted to this new job | **Anger** | 0.3248 |
| This is outrageous, how can you talk like that? | **Anger** | 0.8089 |
| I feel like I'm all alone in this world | **Sadness** | 0.9740 |
| He is really sweet and caring | **Love** | 0.8944 |
| You made me very crazy | **Anger** | 0.5553 |
| I am ever feeling nostalgic about the fireplace... | **Surprise** | 0.8373 |
| I am feeling grouchy | **Anger** | 0.9770 |
| He hates you | **Anger** | 0.7756 |

> 💬 The model demonstrates strong confidence in detecting clear emotional tones like *joy*, *anger*, and *sadness*, while also recognizing subtler expressions such as *love* and *surprise*.

---

## 📊 Results

- Machine Learning models provided good baseline accuracy.  
- The **LSTM model** outperformed ML models for emotion classification with better understanding of text sequences.  
- Achieved high precision and recall for emotions like *joy, anger, sadness,* and *surprise.*  

---

## 🔭 Future Scope

- Integrate **Transformer models (BERT, RoBERTa)** for better accuracy  
- Deploy the model using **Flask** or **FastAPI** for real-time prediction  
- Extend dataset with multilingual emotion data  
- Add visualization dashboard using **Streamlit**  

---

## 🧑‍💻 Author
**Anuj Singh**  
Full Stack Developer | AI & Data Science Enthusiast  
📧 your.email@example.com  
🌐 [LinkedIn Profile or GitHub Link]

---

## 🏁 Summary

This project successfully demonstrates how **NLP and deep learning** can be applied to **understand human emotions from text**.  
It combines traditional ML techniques with modern LSTM networks to deliver accurate emotion and sentiment predictions — paving the way for real-world applications like intelligent chatbots, feedback systems, and social sentiment tracking.
