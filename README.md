
# 📝 Sentiment Analysis Project – Shopee App Reviews

This project focuses on **sentiment analysis** of user reviews for the **Shopee** application collected from the **Google Play Store**, utilizing deep learning models including **LSTM, CNN, and GRU**.

## 📂 Project Overview
This notebook includes:
- **Web scraping** user reviews from the Shopee app using a Google Play Store scraping library
- Text preprocessing (cleaning, tokenization, padding)
- Converting text to numeric sequences using a tokenizer
- Building and training deep learning models (LSTM, CNN, GRU)
- Evaluating model performance in classifying sentiment

## 📊 Dataset
The dataset consists of user reviews of the Shopee application, scraped from the **Google Play Store** using a library such as `google-play-scraper`. Each review is labeled with one of the following sentiment classes:
- ✅ **Positive**
- ❌ **Negative**
- 😐 **Neutral**

> This dataset is publicly available data, used solely for educational and research purposes.

## 🛠️ Tools & Technologies
- Python
- `google-play-scraper` (for scraping)
- TensorFlow / Keras
- Pandas & NumPy
- Matplotlib & Seaborn (visualization)
- Scikit-learn (model evaluation)

## 🤖 Algorithms Used
Deep learning models implemented:
- 🧠 **LSTM** – Long Short-Term Memory
- 🔍 **CNN** – Convolutional Neural Network
- 🔁 **GRU** – Gated Recurrent Unit

## 📈 Model Evaluation
The models are evaluated using:
- Accuracy
- Precision, Recall, and F1-Score
- Confusion Matrix
- Visualization of prediction results

## 🚀 How to Run the Project
1. Clone this repository
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run the notebook `sentiment_analysis_deep_learning.ipynb` using Jupyter Notebook or Google Colab

## 👩‍💻 Contributor
- **Makiatul Musyaropah** 


