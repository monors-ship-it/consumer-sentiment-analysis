# consumer-sentiment-analysis
Sentiment analysis of local vs global retail brands using Google Reviews and X data (VADER, Python)
# Consumer Sentiment Analysis of Local vs Global Retail Brands
## Project Overview
This project analyses consumer sentiment towards **local and global retail brands** using data collected from:
* Google Reviews
* X (Twitter)
The analysis applies Natural Language Processing (NLP) techniques to understand customer perceptions and compare brand performance.
## Objectives
* Analyse consumer sentiment using VADER sentiment analysis
* Compare sentiment across platforms (Google vs X)
* Evaluate brand-level sentiment performance
* Compare local vs global brand perception
## Tools & Technologies
* Python (Google Colab)
* Pandas (data processing)
* Seaborn & Matplotlib (visualisation)
* VADER Sentiment Analysis (NLP)
## Dataset
The dataset consists of:
* Google Reviews data
* X (Twitter) scraped data
After cleaning and merging:
* Total observations: **1268**
* Platforms: Google (1147), X (121)
## Key Analysis Performed
* Sentiment classification (Positive, Neutral, Negative)
* Platform-wise sentiment comparison
* Brand-wise sentiment analysis
* Local vs Global brand comparison
## Results Summary
### Platform Insights
* Google reviews dominate the dataset
* X provides more varied and opinion-driven content
### Brand Insights
* Brands such as M&S and Tesco show strong positive sentiment
* Some brands show higher negative sentiment, indicating customer dissatisfaction
### Origin Insights
* Local brands received higher positive sentiment compared to global brands
* Suggests stronger consumer trust and satisfaction with local retailers
## Files Included
* `consumer_sentiment_local_vs_global.ipynb` → Main analysis notebook
* `final_dataset.csv` → Cleaned dataset
* `platform_summary.csv` → Platform-level summary
* `brand_summary.csv` → Brand-level summary
* `origin_summary.csv` → Local vs Global summary
* Visualisations (.png files)
## Conclusion
The analysis shows that local brands tend to perform better in terms of customer sentiment, while global brands receive relatively mixed feedback. Platform differences also highlight how customer expression varies across sources.
## Author
The author of this project is Kartikey Verma and this project was developed as part of an academic assignment in Business Analytics.
