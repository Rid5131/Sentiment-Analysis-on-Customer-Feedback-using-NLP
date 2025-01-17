# Sentiment-Analysis-on-Customer-Feedback-using-NLP

## **Overview**  
This project implements a sentiment analysis model using LSTM (Long Short-Term Memory) to classify text into three categories: *positive*, *neutral*, and *negative*. The project involves data preprocessing, tokenization, model training, and evaluation, with real-time prediction capability.  

## **Features**  
- Downloads a sentiment analysis dataset using KaggleHub.  
- Cleans and preprocesses text data, including removing stop words and non-alphanumeric characters.  
- Tokenizes and pads the sequences to prepare for model input.  
- Builds a Bidirectional LSTM model with an embedding layer for text classification.  
- Provides visualizations of model performance and confusion matrices.  
- Includes real-time sentiment prediction functionality.  

## **Tech Stack**  
- Python  
- TensorFlow / Keras  
- Pandas, NumPy, NLTK  
- Matplotlib, Seaborn  

## **Getting Started**  
### Prerequisites  
1. Install required Python libraries:  
   ```bash
   pip install tensorflow keras pandas numpy nltk matplotlib seaborn kagglehub
