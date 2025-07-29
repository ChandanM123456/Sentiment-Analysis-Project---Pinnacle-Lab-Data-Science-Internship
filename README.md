# 📊 Sentiment Analysis Project - Pinnacle Lab Data Science Internship

This project is built as part of the **Pinnacle Lab Data Science Internship** and focuses on binary sentiment classification using product/movie reviews.

## 🧠 Objective

The main goal is to build a sentiment classification model that can determine whether a given review sentence has a **positive (1)** or **negative (0)** sentiment.

---

## 📂 Dataset Description

The dataset is sourced from the paper:  
**"From Group to Individual Labels using Deep Features" — Kotzias et al., KDD 2015**

Files used:

- `amazon_cells_labelled.txt` (Product reviews)
- `imdb_labelled.txt` (Movie reviews)

Each file contains:
Label:
- 1 → Positive Sentiment  
- 0 → Negative Sentiment

Each file contains 500 positive and 500 negative samples.

---

## 🛠️ Project Workflow

1. **Data Loading**
   - Load data using `pandas` and combine both datasets.
2. **Data Preprocessing**
   - Lowercasing
   - Removing punctuation
   - Tokenization (optional)
   - TF-IDF Vectorization
3. **Model Building**
   - Train-test split
   - Logistic Regression classifier
4. **Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
5. **Visualization**
   - Heatmap of confusion matrix

---
# Clone the repo
git clone https://github.com/ChandanM123456/Sentiment-Analysis-Project-Pinnacle-Lab-Data-Science-Internship

# Navigate
cd sentiment-analysis

# Run the notebook
jupyter notebook sentiment_analysis_project.ipynb

