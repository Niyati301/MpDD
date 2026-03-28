# 🧠 Depression Detection AI (MpDD)

A production-level Streamlit application that detects signs of depression from user-input text using both Machine Learning and Transformer-based models.

This system combines a traditional ML pipeline with a fine-tuned DistilBERT model to provide fast and accurate predictions.

---

## 🚀 Features

- 🧠 Detects depression from textual input  
- ⚡ Dual model system:
  - ML Model (Fast)
  - Transformer Model - DistilBERT (Accurate)
- 🔍 Text preprocessing using NLP techniques  
- 📊 Confidence score and probability display  
- 📈 Interactive UI using Streamlit  
- ⚙️ Model selection from sidebar  
- 📌 Detailed analysis mode  

---

## 🏗️ How It Works

1. User inputs text  
2. Text is preprocessed (cleaning, removing links & symbols)  
3. Two pipelines available:

### 🔹 ML Pipeline
- TF-IDF Vectorization  
- Classification Model → Prediction  

### 🔹 Transformer Pipeline
- Tokenization using HuggingFace tokenizer  
- DistilBERT model processes text  
- Softmax applied → Probability output  

---

## 🛠️ Tech Stack

- **Frontend/UI:** Streamlit  
- **Languages:** Python  
- **Libraries:**  
  - scikit-learn  
  - NLTK  
  - PyTorch  
  - HuggingFace Transformers  
  - Joblib  

---

## 📊 Models Used

### 1. Machine Learning Model
- Vectorizer: TF-IDF  
- Model: (Specify your model here e.g., Logistic Regression / Naive Bayes)

### 2. Transformer Model
- Model: DistilBERT (fine-tuned)  
- Framework: HuggingFace Transformers  

---

## ▶️ How to Run

```bash
git clone https://github.com/Niyati301/MpDD.git
cd MpDD
pip install -r requirements.txt
streamlit run app.py
