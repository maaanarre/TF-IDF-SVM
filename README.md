# TF-IDF-SVM
## A Novel Text Mining Approach Based on TF-IDF and Support Vector Machine for News Classification

This project implements a text classification pipeline based on the paper:
**"A Novel Text Mining Approach Based on TF-IDF and Support Vector Machine for News Classification"**.

The system uses a classic Natural Language Processing (NLP) approach to classify BBC news articles into five categories using:
- Text preprocessing
- Feature extraction with TF-IDF
- Classification with Support Vector Machine (SVM)

## 📂 Dataset

The project uses the **BBC News Dataset**, which contains 2225 articles labeled in 5 categories ( available in kaggle, also check the implementation code )
the paper works with two dataset ( BBC & 20 NewsGroup) but i only used bbc i couldnt find the other one )

- Business
- Entertainment
- Politics
- Sport
- Tech

## 🧠 Project Overview

This project replicates the methodology described in the paper using Python and `scikit-learn`. The classification pipeline includes:

![image](https://github.com/user-attachments/assets/5b51d093-5eae-4651-bcc8-65a55cd691ac)


1. **Data Loading**
2. **Text Preprocessing**
3. **TF-IDF Feature Extraction**
4. **Training/Test Split**
5. **Classification using SVM**
6. **Evaluation and Reporting**
