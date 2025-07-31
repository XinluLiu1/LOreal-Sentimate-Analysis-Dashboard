# Sentiment Analysis & Dashboard Project

This project performs sentiment analysis on customer reviews using **TextBlob** in **Google Colab**, then visualizes the insights through a dashboard.

---

## 🔍 Part 1: Sentiment Analysis in Google Colab

We use Python and TextBlob to analyze customer sentiment from review text.  
The notebook includes:

- 📥 Data loading (`reviews.csv`)
- 🧼 Preprocessing
- 🧪 Sentiment scoring (polarity, subjectivity, and sentiment label)
- 📈 Basic visualization of sentiment distribution

### 🛠️ Key Libraries
- `pandas`
- `textblob`
- `matplotlib`

### 📁 Sample Data Format

| brand_name    | review                                      |
|---------------|---------------------------------------------|
| L'Oreal Paris | I love this shampoo, it smells amazing!     |
| Garnier       | Didn't work for me at all.                  |
| L'Oreal Paris | Best conditioner ever!                      |

### 📊 Output Columns

| review                                      | polarity | subjectivity | sentiment |
|---------------------------------------------|----------|--------------|-----------|
| I love this shampoo, it smells amazing!     | 0.50     | 0.60         | Positive  |
| Didn't work for me at all.                  | -1.00    | 1.00         | Negative  |

You can open the full Colab notebook [here](link-to-your-colab).

---

## 📊 Part 2: Interactive Dashboard

The sentiment analysis output is used to build a dashboard that:

- Visualizes sentiment distribution by brand
- Compares positive vs. negative feedback over time
- Filters by brand or product
- Identifies high-subjectivity reviews for deeper insights

### 🧰 Tools Used
- [ ] Power BI or Looker Studio *(example screenshots below)*
- [ ] Optional: Streamlit for web-based app

### 📷 Sample Charts
- Bar chart: Sentiment distribution per brand
- Timeline: Sentiment trend over time
- Table: Filtered reviews with sentiment scores

---

## 🚀 How to Run

### In Colab
1. Clone the repo or upload the notebook to Colab.
2. Install dependencies:
   ```python
   !pip install textblob pandas matplotlib
   !python -m textblob.download_corpora
