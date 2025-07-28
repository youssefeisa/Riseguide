# 📊 Riseguide Reviews — Web Scraping & Sentiment Analysis

This project scrapes the **latest 923 reviews** from the last **3 months** on [Trustpilot](https://www.trustpilot.com/) for an online educational platform called **Riseguide**, then performs **sentiment analysis** to classify reviews into **positive, negative,** or **neutral**.

## 🛠️ Workflow Summary

1. **Scraping Reviews**
   - Fetches all pages up to 923 reviews
   - Filters reviews based on the last 3 months only

2. **Sentiment Analysis**
   - Uses rule-based or ML-based NLP tools (e.g. TextBlob or VADER)
   - Labels each review as `Positive`, `Negative`, or `Neutral`

3. **Data Visualization**
   - Plots sentiment distribution
   - Exports CSV for further use

## 📊 Sample Output

| Sentiment | Count |
|-----------|-------|
| Positive  |  648  |
| Neutral   |  242  |
| Negative  |  33   |
| Total     |  923  |

## 📈 Sample Chart

The notebook generates:

- A **Pie chart** for sentiment distribution


## 🧰 Libraries Used

beautifulsoup4  
requests    
matplotlib  
time  
textblob  
nltk
pandas  

## 📦 How to Run

1. Clone the repo or download the notebook.  
2. Install dependencies:

```bash
pip install beautifulsoup4 requests matplotlib time textblob nltk pandas
```

3. Run the notebook in Jupyter or VS Code:

```bash
jupyter notebook Web_Scraping_and_Sentimental_analysis.ipynb
```

## ⚠️ Notes

- Avoid scraping too fast to bypass Trustpilot rate limits.  
- HTML structure of Trustpilot may change — manual adjustment might be needed.  
- Ensure the review content is UTF-8 encoded to avoid parsing errors.  

## 📌 Future Enhancements

- Use transformer-based sentiment classifier (e.g. BERT)  
- Build a dashboard (Streamlit/Gradio)  
- Track sentiment trend over time  

## 🧠 Author

**Youssef Eissa**  
[LinkedIn](https://www.linkedin.com/in/youssef-ahmed-1b2207317?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)  
