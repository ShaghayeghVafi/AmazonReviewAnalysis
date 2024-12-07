# Amazon Review Analysis
## Overview
This project focuses on analyzing Amazon review data using PySpark and machine learning techniques. The dataset is processed and cleaned, and a Naive Bayes model is built to classify reviews as positive or negative based on their content. The goal is to demonstrate efficient handling of large-scale data and applying machine learning for sentiment analysis.

## Key Features
Data Preprocessing: Utilized PySpark to clean and structure unstructured review data from HDFS.
Delta Lake Integration: Used Delta Lake for efficient data storage and processing.
Sentiment Analysis: Built a pipeline with Tokenizer, StopWordsRemover, and HashingTF to prepare data for Naive Bayes classification.
Balanced Sampling: Created an even distribution of reviews for better model performance.
Real-Time Predictions: Tested the model with new reviews for sentiment prediction.
### Technology Stack
PySpark
Delta Lake
Naive Bayes Classifier
HDFS for data storage
## How to Use
Set up the environment with PySpark and Delta Lake.
Place the Amazon review dataset in HDFS.
Run the provided script to process the data, train the model, and make predictions.
Test the model with new reviews by modifying the example inputs in the code.
## Results
The model achieved high accuracy in classifying reviews as positive or negative. Example predictions:

Negative review: "This book had no cohesion, would not recommend. I am disappointed." → Classified as Negative (0)

Positive review: "I loved this book. It lived up to my expectations and WHAT A TWIST!" → Classified as Positive (1)
### Future Improvements
Enhance model performance by experimenting with other classifiers like Random Forest or SVM.
Include additional preprocessing steps for better feature extraction.
