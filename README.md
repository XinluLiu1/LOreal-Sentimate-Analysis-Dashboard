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

<img width="1083" height="214" alt="image" src="https://github.com/user-attachments/assets/b9865349-852f-4e8f-a420-62d8076f0ac3" />

### 📊 Output Columns

<img width="722" height="208" alt="image" src="https://github.com/user-attachments/assets/229a4874-f573-4580-a636-2a5cf7418bc8" />


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
