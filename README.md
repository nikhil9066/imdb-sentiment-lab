
# 🎬 imdb-sentiment-lab

A deep dive into movie review sentiment analysis using traditional machine learning and transformer-based models. This project analyzes the IMDb dataset to classify movie reviews as **positive** or **negative**, comparing models from TF-IDF to RoBERTa.

---

## 📌 Features

- ✅ Preprocessing: stopwords, stemming, lemmatization, regex, emoji handling
- ✅ Vectorization: TF-IDF, Word2Vec, RoBERTa
- ✅ ML Models: Logistic Regression, Naive Bayes, SVM, Random Forest, XGBoost
- ✅ Deep Learning: LSTM-based RNN
- ✅ Transformer: RoBERTa contextual embeddings
- ✅ Model Comparison Table
- ✅ Visualizations: Confusion matrix, WordCloud, t-SNE/PCA

---

## 📊 Dataset

- **IMDb Large Movie Review Dataset**  
- [Kaggle Link](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- 50,000 reviews (balanced between positive and negative)

---

## 🤖 Models Used

| Model Type        | Algorithms                               |
|------------------|-------------------------------------------|
| Traditional ML    | Logistic Regression, Naive Bayes, SVM    |
| Ensemble Models   | Random Forest, XGBoost, LightGBM         |
| Neural Networks   | LSTM, Bidirectional LSTM                 |
| Transformers      | RoBERTa (Hugging Face)                   |

---

## 📈 Visualizations

- Accuracy & loss curves
- Confusion matrix
- Classification report
- WordCloud (positive vs negative)
- t-SNE/PCA projection (Word2Vec, RoBERTa)