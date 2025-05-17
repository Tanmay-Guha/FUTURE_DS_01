# 💬 Sentiment Analysis and Trending Keyword Extraction

This project analyzes user-generated text data to classify sentiment (Positive, Negative, Neutral) and extract trending keywords using NLP techniques.

---

## 📄 Description

The script performs the following steps:

1. **Loads text data** from a CSV file.
2. **Cleans the text data** for analysis.
3. **Performs sentiment analysis** using TextBlob.
4. **Extracts and visualizes trending keywords**.
5. **Exports results** for dashboarding or further analysis.

---

## 🛠️ Technologies & Libraries Used

* Python
* Pandas
* Matplotlib
* Seaborn
* NLTK
* TextBlob
* WordCloud
* Google Colab (for development)

---

## 📂 Input

* **CSV File**: `sentimentdataset.csv`

  * Must contain a column named `"Text"` with textual data for analysis.

---

## 🔍 Features

### ✅ Sentiment Analysis

* Uses `TextBlob` to compute polarity scores.
* Labels sentiments as:

  * Positive (polarity > 0)
  * Negative (polarity < 0)
  * Neutral (polarity = 0)

### ✅ Keyword Extraction

* Cleans text and identifies the top 20 most frequent words.
* Visualizes keywords using a **WordCloud**.

### ✅ Visualization

* **Sentiment distribution bar plot** using `seaborn`.
* **Word cloud** of trending topics.

### ✅ Data Export

* `sentiment_analysis_output.csv` – Contains original text, sentiment score, and label.
* `trending_keywords.csv` – Contains top 20 keywords with frequencies.

---

## ▶️ How to Run

1. Upload your dataset as `sentimentdataset.csv`.
2. Make sure the dataset has a column named `Text`.
3. Run the Python script in a Jupyter Notebook or Google Colab.
4. The script will output:

   * Visualizations (sentiment plot, word cloud)
   * Exported CSV files for sentiment results and keyword trends.

---

## 📦 Output Files

* `sentiment_analysis_output.csv`
* `trending_keywords.csv`

---

## ⚠️ Notes

* Ensure `nltk` data is downloaded before running (`punkt`, `averaged_perceptron_tagger`).
* Modify the `text_column_name` variable if your dataset uses a different column name.

---

## ✍️ Author

* **Name**: *TANMAY GUHA*
* **Contact**: *tanmayguha15@gmail.com*
