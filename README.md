# Amazon Reviews Sentiment Analysis using VADER & RoBERTa

A Natural Language Processing (NLP) project that compares traditional lexicon-based sentiment analysis (**VADER**) with a transformer-based deep learning model (**RoBERTa**) on Amazon customer reviews. The project explores how effectively each approach captures customer sentiment and evaluates their strengths and limitations using real-world review data.

## Project Overview

Customer reviews provide valuable insights into customer satisfaction, product quality, and purchasing behavior. However, manually analyzing thousands of reviews is impractical.

This project uses:

* **VADER (Valence Aware Dictionary and sEntiment Reasoner)** for rule-based sentiment analysis
* **RoBERTa Transformer Model** from Hugging Face for contextual sentiment understanding
* **Python NLP libraries** for text processing and exploratory analysis

The objective is to compare both approaches and determine how sentiment scores align with actual customer ratings.

## Dataset

Amazon Fine Food Reviews Dataset

**Features Used:**

* Review Text
* Review Rating (Score)
* Review Summary

Dataset Size Used:

* Sample of 500 reviews for model comparison and sentiment analysis

## Workflow

```text
Amazon Reviews Dataset
          │
          ▼
   Data Cleaning
          │
          ▼
Exploratory Data Analysis
          │
          ▼
 NLP Preprocessing
          │
          ├──────────────► VADER Analysis
          │
          └──────────────► RoBERTa Analysis
                               │
                               ▼
                    Sentiment Comparison
                               │
                               ▼
                     Business Insights
```

## Key Findings

* Higher-rated reviews generally produced stronger positive sentiment scores.
* VADER performed well on straightforward reviews.
* RoBERTa captured contextual meaning more effectively.
* Transformer-based models handled nuanced language better than lexicon-based methods.
* Both approaches showed a strong relationship with review ratings, but RoBERTa produced more robust sentiment predictions.

## Future Improvements

* Fine-tune RoBERTa on Amazon review data
* Train supervised sentiment classification models
* Build a Streamlit web application
* Perform aspect-based sentiment analysis
* Scale analysis to the complete Amazon Reviews dataset
