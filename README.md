# 📊 Reddit Sentiment Analysis using BERT

## 🚀 Overview
This project performs sentiment analysis on Reddit posts using a pre-trained BERT (Bidirectional Encoder Representations from Transformers) model. It processes real-world textual data and classifies each post into **Positive**, **Neutral**, or **Negative** sentiments.

The system is designed to handle noisy and unstructured data such as emojis, mixed text, and missing values, making it suitable for real-world social media analysis.

---

## 🎯 Objective
- Analyze public opinion from Reddit posts  
- Automatically classify sentiments using deep learning  
- Provide statistical insights through visualization  
- Enable comparison between different subreddit datasets  

---

## 🧠 Model Used
- **BERT (nlptown/bert-base-multilingual-uncased-sentiment)**
- Pre-trained transformer model for sentiment classification  
- Uses contextual embeddings and attention mechanism  
- No need for heavy manual preprocessing  

---

## ⚙️ Methodology
1. Load pre-trained BERT model and tokenizer  
2. Accept dataset (.csv / .xlsx)  
3. Automatically detect text column  
4. Handle missing values and convert data to string  
5. Tokenize input text  
6. Perform inference using BERT  
7. Map predictions to:
   - Positive  
   - Neutral  
   - Negative  
8. Compute:
   - Sentiment counts  
   - Percentage distribution  
9. Visualize results using bar charts  

---

## ✨ Features
- ✅ Works with real-world Reddit datasets  
- ✅ Handles emojis, URLs, and mixed text  
- ✅ Automatic text column detection  
- ✅ No manual preprocessing required  
- ✅ Sentiment distribution visualization  
- ✅ Subreddit comparison analysis  
- ✅ Interactive web interface using Streamlit  

---

## 🔄 Subreddit Comparison
The project supports comparison between two subreddit datasets.

It analyzes both datasets separately and provides:
- Sentiment percentage comparison  
- Side-by-side analytics  
- Visualization of differences  

This helps in understanding how sentiment varies across different communities.

---

## 📊 Sample Output
- Sentiment classification (Positive / Neutral / Negative)  
- Sentiment counts  
- Percentage distribution  
- Graphical representation  
- Dominant sentiment insight  

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- PyTorch  
- Hugging Face Transformers  
- Matplotlib  
- Streamlit  

---


## 📌 Future Enhancements
- Live Reddit data fetching using API  
- Real-time sentiment dashboard  
- Advanced visualization (pie charts, trends)  
- Model fine-tuning for higher accuracy  
- Deployment on cloud platforms  

---

## 📚 References
- Hugging Face Transformers  
- BERT Research Paper  
- PyTorch Documentation  
- Streamlit Documentation  
- Reddit datasets (Kaggle / API)  
