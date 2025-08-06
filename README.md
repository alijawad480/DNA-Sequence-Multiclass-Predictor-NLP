# 🧬 DNA Sequence Classification with TF-IDF & LinearSVC

This project focuses on predicting the class of a DNA sequence using machine learning techniques. By treating DNA sequences as text data, we apply natural language processing (NLP) methods—specifically TF-IDF vectorization—to extract meaningful patterns and train a classifier.

## 🔍 Overview

DNA sequences contain important biological signals. This project converts these sequences into numerical features using n-gram-based TF-IDF vectorization, and trains a Linear Support Vector Classifier (LinearSVC) to identify their corresponding class.

## 📁 Dataset

The dataset consists of DNA sequences and their corresponding labels (classes). Each row represents a DNA sample with its label:

## 🧠 Model Pipeline

1. **Text Vectorization:**  
   - Using TF-IDF with character-level n-grams (range: 3 to 6).
   - This captures local patterns in DNA sequences.

2. **Classifier:**  
   - LinearSVC (Support Vector Machine for classification).

3. **Training:**  
   - The model is trained on labeled sequences.

4. **Prediction:**  
   - Input DNA sequence → Vectorized → Predicted class.
