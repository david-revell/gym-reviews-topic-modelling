# Topic Modelling of Gym Reviews Using NLP Techniques

This project analyses over 6,000 low-rated customer reviews from Google and Trustpilot to identify key themes and emotional drivers of dissatisfaction. Topic modelling and emotion detection are used to uncover insights into recurring service issues.

---

## Project Overview

The aim is to understand negative sentiment in gym reviews by extracting dominant topics and emotional tones. This helps highlight areas such as equipment complaints, staff behaviour, or cancellation issues using NLP-based techniques.

**Techniques used:**
- Emotion classification (pretrained model)
- Topic modelling with LDA
- Topic modelling with BERTopic (LLM-enhanced)
- Platform comparison (Google vs Trustpilot)

*Full PDF report included in the repo.*

---

## Key Steps

1. Filter reviews for 1–2 star ratings
2. Preprocess text and run emotion detection
3. Apply LDA and BERTopic to extract topics
4. Compare topic structure and frequency across platforms
5. Summarise insights for potential service improvements

---

## Status

All code is contained in a single Jupyter Notebook.

⚠️ **Note:**  
Interactive outputs (e.g. BERTopic visualisations) have been cleared to avoid GitHub rendering issues.  
To view results, please run the notebook locally or in Colab.
