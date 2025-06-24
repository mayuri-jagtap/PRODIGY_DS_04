#  Twitter Brand Sentiment Analysis

Analyze and visualize Twitter sentiment data to explore public opinion toward major brands and topics.


##  Project Overview

This project aims to uncover public sentiment trends on Twitter related to various well-known brands and topics using a labeled dataset. It uses data analysis and visualization techniques to identify how users feel (Positive, Neutral, or Negative) about different entities such as **Amazon**, **Facebook**, **Cyberpunk 2077**, etc.



##  Dataset

- **Source**: [Kaggle - Twitter Entity Sentiment Analysis](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)
- **Files Used**:
  - `twitter_training.csv`
  - `twitter_validation.csv`
- **Columns**: `id`, `entity`, `sentiment`, `text`



##  Tools & Libraries

- Python 
- Pandas
- Matplotlib
- Seaborn
- NLTK (Stopwords)
- WordCloud
- Regex (`re`)



##  Features & Analysis Performed

-  Loaded and merged training & validation datasets  
-  Cleaned tweet text (URLs, mentions, hashtags, punctuation)  
-  Visualized overall sentiment distribution  
-  Generated WordClouds for each sentiment (Positive, Neutral, Negative)  
-  Analyzed sentiment per brand/entity  
-  Visualized top 10 brands with most positive and most negative mentions  



## Learnings

- How to preprocess and clean real-world Twitter data  
- Visualizing sentiment data using count plots and bar charts  
- Generating WordClouds to highlight frequently used words  
- Grouping and analyzing categorical data using `groupby()`  
- Exploring public opinion trends based on entities (brands)  
- Handling plot formatting and warning resolution in Seaborn  



