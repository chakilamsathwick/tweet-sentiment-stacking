\# Tweet Sentiment Analysis using Stacking Ensemble



\## Overview

This project performs sentiment analysis on tweets using a Stacking Ensemble Machine Learning approach. Multiple base models are trained and their predictions are combined using a meta-model to improve classification performance.



\## Features

\- Tweet text preprocessing

\- Data cleaning and normalization

\- TF-IDF feature extraction

\- Logistic Regression

\- Naive Bayes

\- Linear SVM

\- Stacking Ensemble Model

\- Sentiment prediction

\- Performance visualization



\## Project Structure



```

tweet-sentiment-stacking/

│

├── artifacts/

├── data/

├── src/

├── step\_1.ipynb

├── step\_2.ipynb

├── step\_3.ipynb

├── step\_4.ipynb

├── confusion\_matrix\_stacking.png

├── sentiment\_distribution\_stacking.png

├── README.md

└── .gitignore

```



\## Technologies Used



\- Python

\- Pandas

\- NumPy

\- Scikit-Learn

\- Joblib

\- Jupyter Notebook



\## Workflow



1\. Data Collection

2\. Text Preprocessing

3\. TF-IDF Vectorization

4\. Train Base Models

5\. Generate Out-of-Fold Predictions

6\. Train Meta Model

7\. Evaluate Performance

8\. Predict Sentiment



\## Results



The stacking ensemble combines multiple machine learning models to achieve better sentiment classification performance compared to individual models.



\## Author



Chakilam Sathwick

