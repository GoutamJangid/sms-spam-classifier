# SMS Spam Classifier Web App

A machine learning application built with Python to classify messages as spam or not spam. This project includes a Jupyter Notebook (`sms-spam-classifier.ipynb`) for analysis and a Python app (`app.py`) to serve the model.

### Project Features

* **End-to-End ML Pipeline:** Complete workflow from data cleaning and text preprocessing (tokenization, stemming) to feature extraction (TF-IDF).

* **High-Performance Model:** Achieved **98.36% Accuracy** and **97.64% Precision** using a Voting Classifier, outperforming several baseline models.

<!--* **Web Application:** `app.py` file (ready for Streamlit/Flask) that loads the saved `model.pkl` and `vectorizer.pkl` to make live predictions.-->

### Model Experiments

To find the best model, several experiments were conducted. The Voting Classifier provided the best balance of accuracy and precision.

| Method | Accuracy | Precision | 
| :--- | :--- | :--- | 
| Baseline (MNB + TF-IDF Unigrams) | 0.9758 | 1.0000 | 
| Experiment A (MNB + CountVectorizer) | 0.9826 | 0.9412 | 
| **Experiment B (Voting Classifier)** | **0.9836** | **0.9764** | 
| Experiment C (MNB + TF-IDF with N-grams) | 0.9720 | 1.0000 | 
