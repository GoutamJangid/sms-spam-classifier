# SMS Spam Classifier Web App

A machine learning application built with Python to classify messages as spam or not spam. This project includes a Jupyter Notebook (`sms-spam-classifier.ipynb`) for analysis and a Python app (`app.py`) to serve the model.

### Project Features

* **End-to-End ML Pipeline:** Complete workflow from data cleaning and text preprocessing (tokenization, stemming) to feature extraction (TF-IDF).

* **High-Precision Model:** The baseline model (Multinomial Naive Bayes + TF-IDF) achieved **100% Precision**, ensuring no legitimate messages are incorrectly flagged as spam.

* **Web Application:** `app.py` file (ready for Streamlit/Flask) that loads the saved `model.pkl` and `vectorizer.pkl` to make live predictions.

### Model Experiments

To find the best model, several experiments were conducted. The baseline model provided perfect precision, which is ideal for a spam filter.

| Method | Accuracy | Precision | 
 | ----- | ----- | ----- | 
| **Baseline (MNB + TF-IDF Unigrams)** | **0.9758** | **1.0000** | 
| Experiment A (MNB + CountVectorizer) | 0.9826 | 0.9412 | 
| Experiment B (Voting Classifier) | 0.9836 | 0.9764 | 
| Experiment C (MNB + TF-IDF with N-grams) | 0.9720 | 1.0000 | 
<!--
### Tech Stack

* **Core:** Python

* **Data Science:** Pandas, NumPy, Scikit-learn, Matplotlib

* **Web App:** \[Specify here, e.g., Streamlit or Flask\]

* **Analysis:** Jupyter Notebook

### How to Run This Project

**1. Run the Jupyter Notebook**
You can view the `sms-spam-classifier.ipynb` file to see the full analysis, model training, and evaluation.

**2. Run the Web Application (Locally)**

First, install the required libraries: -->
