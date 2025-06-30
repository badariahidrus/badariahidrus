I’m Badariah Idrus, a data analyst and technical consultant with 15+ years of experience across oil & gas, petrochemical, and industrial energy sectors. I bring a unique mix of chemical engineering expertise and data science capabilities, currently enhanced by a Master’s in Data Science from Sunway University.I help organizations transform raw data into meaningful insights — whether that’s through predictive models, interactive dashboards, or technically sound documentation.

- 📫 How to reach me badariah.idrus@gmail.com

# 📊 Sentiment Analysis of Financial News to Predict FBM KLCI Trends

This project uses sentiment analysis on Malaysian financial news — specifically from **Google News Malaysia** — to evaluate and potentially forecast movements of the **FTSE Bursa Malaysia KLCI (FBM KLCI)** index. The model integrates textual sentiment with historical stock data and technical indicators.

---

## 📌 Project Objectives

- Scrape and process news headlines and articles from *Google News Malaysia*.
- Perform sentiment analysis using NLP models (VADER and TextBlob).
- Aggregate daily sentiment scores.
- Merge sentiment with historical KLCI data and technical indicators.
- Train models to detect patterns or predict trends in the FBM KLCI index.

---

## 🧠 Methodology

1. **Data Collection**  
   - Web scraping of Google News articles (title + content).
   - Historical KLCI index from Yahoo Finance or Bursa Malaysia.
   - Historical data from Jan 2019 until Jan 2025
   - The data included pre-COVID, COVID period and post-COVID 

2. **Text Preprocessing**  
   - Tokenization, stopword removal, and lemmatization.
   - Custom financial keyword tagging (e.g., “OPR hike”, “fiscal deficit”).

3. **Sentiment Analysis**  
   - Polarity scoring using TextBlob / VADER.
   - Aggregation of sentiment scores by day.

4. **Feature Engineering**  
   - Merge sentiment with:
     - Technical indicators (e.g., EMA, RSI)
     - Lagged KLCI values

5. **Modeling & Prediction**  
   - Train regression or time-series models (e.g., LSTM, ARIMA, XGBoost).
   - Evaluate impact of sentiment on price movement.

---

## 🛠️ Technologies Used

- **Python 3.11**
- `pandas`, `numpy`, `scikit-learn`, `beautifulsoup4`, `requests`
- `TextBlob`, `transformers` (VADER for finance-specific sentiment)
- `matplotlib`, `seaborn`, `plotly`
- `TensorFlow` / `PyTorch` (for deep learning models)

---

## 🔑 Key Insights

- Certain keywords like `"interest rate hike"` or `"fiscal stimulus"` significantly correlate with KLCI movement.
- News sentiment can provide early warning signals of potential market dips or rallies.
- The hybrid model (technical + sentiment) improved prediction accuracy over baseline models.

---

## 📝 To-Do

- [ ] Expand scraping to cover 5+ years of articles
- [ ] Implement real-time sentiment updates
- [ ] Add explainability using SHAP or LIME
- [ ] Deploy as a dashboard using Streamlit

---

## 🤝 Contributions

Feel free to fork the repository, open issues, or submit pull requests.

---

## 🙋‍♀️ Author

**Badariah Idrus**  
Master's in Data Science | Process Engineer  
[LinkedIn](https://www.linkedin.com/badariah-idrus) | [GitHub](https://github.com/)

---



