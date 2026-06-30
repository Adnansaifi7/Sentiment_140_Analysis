# Sentiment_140_Analysis
**GitHub Description (under 350 characters):**  Sentiment analysis on the Sentiment140 dataset using Logistic Regression, Naive Bayes, LSTM, and BERT. Compares the performance of traditional ML, deep learning, and transformer models, with BERT achieving the highest accuracy for tweet sentiment classification.





# Sentiment140 Sentiment Analysis

A comparative sentiment analysis project on the **Sentiment140** dataset using traditional machine learning, deep learning, and transformer-based models. This project evaluates the performance of **Logistic Regression**, **Naive Bayes**, **LSTM**, and **BERT** for tweet sentiment classification.

## 📌 Overview

The goal of this project is to compare different approaches for sentiment analysis and determine which model performs best on the Sentiment140 dataset.

**Models Implemented:**
- Logistic Regression
- Naive Bayes
- LSTM (Long Short-Term Memory)
- BERT (Bidirectional Encoder Representations from Transformers)

## 📂 Dataset

- **Dataset:** Sentiment140
- **Source:** https://www.kaggle.com/datasets/kazanova/sentiment140
- **Classes:**
  - Positive
  - Negative

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Hugging Face Transformers
- Matplotlib
- Seaborn

## 🚀 Workflow

1. Data preprocessing and cleaning
2. Text tokenization
3. Feature extraction
4. Model training
5. Model evaluation
6. Performance comparison

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## 🏆 Results

| Model | Performance |
|-------|-------------|
| Naive Bayes | Baseline model |
| Logistic Regression | Strong traditional ML performance |
| LSTM | Better contextual learning than traditional models |
| **BERT** | **Highest accuracy and best overall performance** |

BERT outperformed all other models by leveraging contextual embeddings, making it the most effective model for tweet sentiment classification.

## 📁 Project Structure

```
├── data/
├── notebooks/
├── models/
├── results/
├── requirements.txt
└── README.md
```

## 📈 Future Improvements

- Hyperparameter tuning
- RoBERTa and DistilBERT comparison
- Multi-class sentiment analysis
- Model deployment with Flask or FastAPI

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

## 📜 License

This project is licensed under the MIT License.
