# Fake-news-detection
Fake news detection using Machine Learning & Logistic Regression 
This project demonstrates how to build a simple Fake new Classifier using TF-IDF  vectorization and Logistic Regression in Python with scikit-learn.This model predicts whether a given news article is real or fake based on its textual content.
# Dataset
The dataset ued in this project is publicly available from: [ Fake or real news] (https://raw.githubuser.content.com/lutzhamel/fake-news/mater/data/fake_or_real_news.csv)
# Installation Instruction
1. Clone the repository:
 '''bash
git clone
https://github.com/HepzibaJ/fake-news-detector.git
      cd fake-news-detector
 # Create and activate a virtual environment:
 python -m venv venv
  source venv/bin/activate
On mac0s/Linu
venv\Scripts\activate
   On windows
# Install required packages:
   pip install -r requirements.txt
  # How to Run the Code:
   * Run the python script
   * python fake_news_classifier.py
   * Or Open the jupyter notebook (Jupyter notebook fake_news_classifier.ipynb)
   * The Script will Download and preprocess the dataset,Train a logistic Regression model using TF-IDF features and Evaluate and print the accuracy and classification report.
# Model and Evaluation info
   * Vectorization : TF-IDF (stopwords removed,max_df = 0.7)
   * Model : Logistic Regression ( default parameters)
   * Data Split : 80% training and 20% test
   * Metrics : Accuracy and Precision,  Recall,F1-Score (via Classification_report)
# Example Output
   Accuracy : 0.928
   Classification Report :Precision recall f1-score support
   FAKE : 0.93 587 REAL :0.93 587
   accuracy : 0.93 1174
   macro avg :0.93 1174
   weighted avg : 0.93 1174
 # License
   This project is lincensed under the MIT License - See the License file for detail.
   Notebook used : Jupyter Notebook
  
