### ✅ **Twitter Sentiment Analysis in R**  
This project fetches tweets from Twitter using the Twitter API and analyzes their sentiment (positive, negative, or neutral) using a lexical approach.

---

### 📦 **Pre-requisites**
- **R** (Version **4.0** or higher recommended)
- **Twitter Developer Account** with OAuth 1.0a credentials (API key, API secret, access token, and token secret)

---

### 📚 **Updated Dependencies**
The following R packages are used:
- `rtweet` *(modern Twitter API access)*
- `stringr`
- `ggplot2`
- `reshape2`
- `tm`
- `wordcloud`
- `gridExtra`
- `plyr`
- `dplyr`
- `textclean` *(for better text preprocessing)*
- `tidytext`
- `httr` *(for handling token issues)*
- `sentimentr` *(optional but powerful sentiment engine)*


---

### ⚙️ **Execution Steps**

#### 🔹 Quick Start
All necessary steps are compiled into one file:  
```bash
script_running.R
```

#### 🔹 Modular Version (Step-by-step Learning)
You can explore each step as an individual R script:

1. **01_authentication.R** – Setup and authenticate with Twitter using `rtweet`
2. **02_tweet_extraction.R** – Fetch tweets for a keyword/hashtag
3. **03_word_database.R** – Load custom positive/negative word lists
4. **04_cleaning_data.R** – Clean and normalize tweet text
5. **05_emoticon_handling.R** – Handle emojis/emoticons (optional)
6. **06_score_sentiment.R** – Apply sentiment scoring on tweets
7. **07_func_on_tweet.R** – Define helper functions
8. **08_graphs.R** – Visualize sentiment with bar plots
9. **09_percentage_calc.R** – Calculate sentiment proportions
10. **10_level_of_sentiment.R** – Classify tweet polarity
11. **11_hashtag_analysis.R** – Analyze frequent hashtags
12. **12_top_tweeters.R** – Top contributors and timeline
13. **13_wordcloud.R** – Generate word clouds

---

### 📌 Notes
- Make sure you store your Twitter API credentials securely and **don’t push them to GitHub**.
- This project is a lexical approach, meaning it uses word-matching for sentiment—not machine learning.

---
