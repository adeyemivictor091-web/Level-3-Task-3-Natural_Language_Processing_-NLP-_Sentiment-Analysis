# Level-3-Task-3-Natural_Language_Processing_-NLP-_Sentiment-Analysis
Perform sentiment analysis on textual data (e.g., customer reviews, social media comments) to classify text as positive, negative, or neutral.
# NLP Sentiment Analysis Using Machine Learning

## Project Overview

This project focuses on developing a Natural Language Processing (NLP) machine learning model to classify text data into three sentiment categories:

* Negative
* Neutral
* Positive

The objective was to build an automated sentiment analysis pipeline capable of extracting insights from user-generated text and supporting data-driven decision-making.

---

# Business Problem

With the increasing volume of customer reviews, social media comments, and online feedback, organisations require automated solutions to understand public sentiment.

Manual analysis of large amounts of text is time-consuming and inconsistent.

This project addresses this challenge by developing a machine learning model that automatically identifies sentiment patterns from textual data.

---

# Dataset Description

The dataset contains **732 records with 21 features**, including:

| Feature   | Description                 |
| --------- | --------------------------- |
| Text      | User-generated text content |
| Sentiment | Target classification label |
| Timestamp | Date and time information   |
| User      | User identifier             |
| Platform  | Source platform             |
| Hashtags  | Associated hashtags         |
| Retweets  | Engagement metric           |
| Likes     | Engagement metric           |
| Country   | Geographic information      |

---

# Project Workflow

## 1. Data Understanding

* Loaded and inspected dataset structure
* Reviewed missing values
* Analysed sentiment distribution
* Examined text characteristics

---

## 2. Data Preprocessing

Applied NLP preprocessing techniques:

* Text cleaning
* Lowercase conversion
* Removal of unwanted characters
* Tokenization
* Stop-word removal
* TF-IDF vectorisation

---

## 3. Exploratory Data Analysis

Performed analysis including:

* Sentiment distribution analysis
* Text length analysis
* Word frequency analysis
* Visualisation of sentiment patterns

---

## 4. Machine Learning Model

### Algorithm Used

**Support Vector Machine (SVM)**

SVM was selected because it performs effectively for high-dimensional text classification problems and works well with TF-IDF feature representations.

---

# Model Performance

## Classification Results

| Sentiment | Precision | Recall | F1-score |
| --------- | --------: | -----: | -------: |
| Negative  |      0.89 |   0.89 |     0.89 |
| Neutral   |      0.83 |   0.85 |     0.84 |
| Positive  |      0.67 |   0.62 |     0.64 |

### Overall Accuracy

**79%**

---

# Key Findings

* The model successfully classified sentiment categories with strong overall performance.
* Negative sentiment detection achieved the highest reliability.
* Neutral sentiment classification benefited from having the largest number of examples.
* Positive sentiment requires further improvement due to class imbalance and overlapping language patterns.

---

# Technologies Used

## Programming Language

* Python

## Libraries

* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* NLTK

---

# Project Structure

```
NLP-Sentiment-Analysis/
│
├── Dataset/
│   └── sentiment_data.csv
│
├── Notebook/
│   └── NLP_Sentiment_Analysis.ipynb
│
├── Images/
│   ├── sentiment_distribution.png
│   ├── confusion_matrix.png
│
├── README.md
└── requirements.txt
```

---

# Future Improvements

Potential improvements include:

* Applying SMOTE for class balancing
* Testing Logistic Regression, Random Forest, and XGBoost models
* Implementing BERT transformer models
* Performing hyperparameter tuning
* Deploying the model using Flask or Streamlit

---

# Business Applications

This solution can support:

* Customer feedback analysis
* Social media monitoring
* Brand reputation tracking
* Customer experience analytics
* Market research

---

# Author

Adeyemi Victor

Data Analytics | Machine Learning | NLP Projects

---

# License

This project is created for educational and portfolio demonstration purposes.
