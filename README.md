# AI-Powered WhatsApp Chat Analysis using NLP and Toxic Message Detection

## Overview

This project is an advanced WhatsApp Chat Analysis system developed using Python, Natural Language Processing (NLP), and Data Visualization techniques.

The system analyzes exported WhatsApp chats and provides detailed insights including sentiment analysis, toxic message detection, emoji analysis, heatmaps, word clouds, user activity tracking, and timeline visualization.

---

# Features

## Chat Analysis

* Total messages count
* User-wise message statistics
* Media message count
* Link sharing analysis
* Word count analysis

## NLP Features

* Sentiment Analysis

  * Positive
  * Negative
  * Neutral

* Toxic Message Detection

  * Toxic messages
  * Non-toxic messages
  * User-wise toxicity analysis

## Visualization Features

* Word Clouds
* Emoji Frequency Analysis
* Daily Timeline Graphs
* Activity Heatmaps
* User-wise Sentiment Heatmaps
* Toxicity Heatmaps

## Advanced Analytics

* Most active users
* Most toxic users
* Most used emojis
* Daily sentiment trends

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* NLP
* TextBlob
* Detoxify
* WordCloud
* Regex

---

# Installation

## Install Required Libraries

```bash id="h1x9ls"
pip install pandas numpy matplotlib seaborn wordcloud emoji regex textblob detoxify
```

---

# How to Export WhatsApp Chat

1. Open WhatsApp
2. Open the group or personal chat
3. Click on:

   * Three Dots
   * More
   * Export Chat
4. Select:

   * Without Media
5. Save the `.txt` file

---

# How to Run the Project

## Step 1

Clone the repository:



## Step 2

Open the notebook or Python file in Google Colab or Jupyter Notebook.

## Step 3

Run all cells.

## Step 4

Upload the exported WhatsApp chat file when prompted.
sample file :-   https://drive.google.com/file/d/1I9FcmrqV9JC5FI96qpCS4Te6OrrKzXU5/view?usp=sharing
---

# Project Workflow

1. Upload WhatsApp chat file
2. Parse chat messages
3. Clean and preprocess text
4. Perform sentiment analysis
5. Detect toxic messages
6. Generate visualizations
7. Export cleaned dataset

---

# Sentiment Analysis

The project uses TextBlob for sentiment analysis.

Output categories:

* Positive
* Negative
* Neutral

---

# Toxic Message Detection

The project uses Detoxify for toxicity classification.

Output categories:

* Toxic
* Non-Toxic

---

# Visualizations Included

* Word Clouds
* Activity Heatmaps
* Sentiment Graphs
* Toxicity Charts
* Daily Timelines
* Emoji Statistics

---

# Future Improvements

* Streamlit Dashboard
* Real-time Chat Monitoring
* AI Chat Summarization
* Topic Modeling
* Language Detection
* Response Time Analysis

---

# Output

The project generates:

* Detailed console analysis
* Multiple charts and heatmaps
* Cleaned CSV dataset export

---

# Author

Rushil Dileep Pawar

BE Artificial Intelligence and Data Science

Mumbai University

---

# License

This project is developed for educational and research purposes.
