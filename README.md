# 🎥 IMDB Sentiment Analysis


## 📜 Description

A machine learning project to analyze and classify IMDB movie reviews as **Positive** or **Negative** using Natural Language Processing (NLP) techniques.


## 🚀 Features  

1. **Data Preprocessing**  
   - Counts **words**, **characters**, and **stopwords**.  
   - Removes **HTML tags** and **stopwords** from text reviews.  

2. **Visualization**  
   - Generates insightful plots for data exploration using **Seaborn**.  

3. **Model Development**  
   - Uses a **TF-IDF Vectorizer** and **LinearSVC** pipeline for sentiment classification.  

4. **Web App**  
   - A user-friendly **Streamlit app** for real-time sentiment analysis of reviews.
  

## 📊 Data Insights
Key Preprocessing Steps:

- Word counts, character counts, and stopword analysis.
- Average word length calculation.

Visualizations:

- Plots for understanding word count, character count, stopword frequency, and average word lengths across sentiments.

## 📈 Model Performance

The model was trained using:

- TF-IDF Vectorizer for feature extraction.
- Linear Support Vector Classifier (LinearSVC) for classification.

Metrics:

- Classification Report: Precision, Recall, F1-Score.
- Confusion Matrix: Performance evaluation.


## 🖥️ Running the Project
- Running the Streamlit App
- Enter a movie review in the text box to predict sentiment.

    - ✅ Positive Review: Green success message.
    - ⚠️ Negative Review: Yellow warning message.
