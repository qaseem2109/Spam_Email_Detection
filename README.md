# Spam Email Detection using Machine Learning

## Overview

This project implements a machine learning–based spam email classifier using Natural Language Processing (NLP). The system predicts whether an email is **Spam** or **Ham** based on its subject and body text. The project follows a complete ML pipeline from data preprocessing to model evaluation and comparison.

---

## Objective

To build and evaluate supervised learning models capable of accurately classifying emails as spam or non-spam using textual features.

---

## Dataset
The dataset consists of labeled email records with the following columns:
- **title**: Email subject
- **text**: Email body
- **type**: Target label (`spam`, `ham`)

The subject and body text are combined for feature extraction.

---

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- TF-IDF Vectorization
- Matplotlib / Seaborn

---

## Preprocessing & Feature Engineering
- Text normalization (lowercasing, punctuation removal)
- Stopword removal
- Text vectorization using **TF-IDF**
- Train-test split for evaluation

---

## Models Implemented
- Logistic Regression
- Multinomial Naive Bayes
- Support Vector Machine (SVM)

---

## Evaluation Metrics
Model performance is assessed using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## Results
Logistic Regression demonstrated the best balance between precision and recall, making it the most reliable model for spam classification in this dataset.

## Future Enhancements

-) Hyperparameter optimization
-) Deep learning models (LSTM, Transformers)
-) Web-based deployment (Streamlit / Django)
-) Real-time email classification using APIs

🙌 Contribution
Pull requests are welcome. For major changes, open an issue first to discuss your ideas.

📄 License
This project is licensed under the MIT License.

📧 Contact
For inquiries or collaboration:

Muhammad Qaseem
Email: qaseem2109@gmail.com GitHub: https://github.com/qaseem2109
