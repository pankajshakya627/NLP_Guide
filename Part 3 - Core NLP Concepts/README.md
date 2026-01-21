# Part 3: Core NLP Concepts

This section covers the mathematical and theoretical building blocks of NLP. Before training complex models, one must understand how to represent text numerically and calculate probabilities.

## 🎯 Learning Objectives
By the end of this section, you will be able to:
*   Preprocess raw text to make it suitable for machine learning.
*   Calculate the edit distance between two strings mathematically.
*   Convert text into numerical vectors using Bag-of-Words and TF-IDF.
*   Understand the probability theory behind N-gram language models.

## 📂 Section Contents

### [3.1 Text Preprocessing](3.1_Text_Preprocessing.md)
Detailed techniques for cleaning text:
*   **Noise Removal:** Regex for HTML tags, URLs.
*   **Normalization:** Handling contractions and punctuation.
*   **Math Spotlight:** **Levenshtein Distance** (Edit Distance) with a full matrix calculation example.

### [3.2 Feature Engineering](3.2_Feature_Engineering.md)
How to turn text into numbers:
*   **Bag-of-Words (BoW):** Simple counting vectors.
*   **TF-IDF:** Weighing terms by importance. Includes detailed mathematical formulas and a solved example.

### [3.3 Language Modeling](3.3_Language_Modeling.md)
Predicting the next word in a sequence:
*   **N-gram Models:** Bigrams, Trigrams.
*   **Probability Calculation:** Maximum Likelihood Estimation (MLE). Includes a step-by-step solved example for calculating sentence probability.