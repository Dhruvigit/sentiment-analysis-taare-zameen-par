# sentiment-analysis-taare-zameen-par

## Overview
This project analyzes audience sentiment for the movie *Taare Zameen Par* using survey-based data and Natural Language Processing (NLP) techniques. The goal is to understand key drivers of audience opinion and evaluate different sentiment classification approaches.

## Dataset
- Survey responses from 30 participants collected via Google Forms
- Includes demographics, ratings, emotional responses, and written reviews

## Methodology
- Exploratory Data Analysis (EDA) for demographic and engagement insights
- Rule-based sentiment classification using overall movie ratings
- Predictive sentiment modeling using:
  - Count Vectorizer + Naive Bayes
  - TF-IDF Vectorizer + Naive Bayes
  - BERT embeddings for contextual understanding

## Results
- Count Vectorizer accuracy: ~62%
- TF-IDF accuracy: ~75%
- BERT-based model accuracy: ~89%
- BERT performed best, highlighting the importance of contextual embeddings in sentiment analysis

## Project Structure
- `TZP_Sentiment_Analysis.ipynb` – Main analysis and modeling notebook
- `Sentiment_Review_TZP.csv` – Survey dataset
- `Sentiment_Analysis_Doc.docx` – Detailed written report (downloadable)
- `Project Overview & Audience Profile.pdf` – Presentation summary

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Transformers (BERT)
- Matplotlib, Seaborn

## Author
Dhruvi Patel
