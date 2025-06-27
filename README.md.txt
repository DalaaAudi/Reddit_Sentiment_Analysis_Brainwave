# 🧠 Reddit Sentiment Analysis

This project explores sentiment dynamics from Reddit posts and comments to uncover insights about user emotions, engagement patterns, and content trends. It was completed as part of a training assignment for **Brainwave Matrix Solutions**.

---

## 📂 Project Structure

```
RedditSentimentAnalysis/
├── data/                # Raw datasets (not included in the repository)
├── notebooks/           # Jupyter Notebooks for EDA and sentiment analysis
├── processed_data/      # Cleaned and transformed CSV files
├── outputs/             # Charts, plots, and visual results
├── src/                 # Utility scripts and future modules (not included)
├── README.md            # Project documentation
└── .gitignore           # Excludes cache and large/raw data files
```

---

## 📁 Dataset

- **Posts and comments** scraped from selected subreddits.
- Sentiment scores computed using **TextBlob**.

> 🔎 *Note: The analysis is based on a sample of only the first 5 Reddit posts. While full data may affect results, the identified patterns remain valuable for insight.*

---

## 🎯 Project Objectives

- Analyze sentiment distributions in posts and comments.
- Track sentiment trends over time.
- Compare engagement levels across sentiment categories.
- Identify top-performing posts and comments.
- Generate word clouds for contrasting sentiment types.

---

## 📊 Key Insights

- **Positive posts** tend to attract more comments and upvotes.
- **Comments** display wider emotional shifts across time than posts.
- Certain **subreddits** exhibit consistent sentiment trends linked to seasonal or topical events.

---

## 📸 Visual Outputs

Located in the `outputs/` folder:
- Sentiment histograms for posts and comments
- Monthly sentiment trend plots
- Sentiment vs. engagement scatter plots
- Positive and negative word clouds

---

## 🧪 Processed Data

Available in `processed_data/`:
- `processed_posts.csv`
- `processed_comments.csv`

These datasets include sentiment scores, cleaned text, timestamps, and key metadata.

---

## 🛠️ Tools & Libraries

- **Python**: pandas, matplotlib, seaborn, plotly, textblob, re, os, shutil
- Developed in **Google Colab** for cloud computing resources. 
- **Git & GitHub** for version control

---

## 🚀 How to Run

1. Clone the repository or download it as a ZIP file.
2. Install dependencies with:
   ```bash
   pip install -r requirements.txt
   ```
3. Navigate to the `notebooks/` folder and run the notebook step-by-step.
4. Processed files and figures will be saved automatically.

---

## 📌 Notes

- This analysis was based on a limited post/comment sample.
- Tools such as ChatGPT were used to assist with code and explanations, with all steps reviewed for full understanding.

---

## 🤝 Acknowledgment

Grateful thanks to **Brainwave Matrix Solutions** for their guidance and support throughout the project.

---

## 🔗 Repository Contents

- 📘 Full notebook: `notebooks/Reddit_Sentiment_Analysis.ipynb`
- 🧹 Clean version: `notebooks/Reddit_Sentiment_Analysis_no_output.ipynb`
