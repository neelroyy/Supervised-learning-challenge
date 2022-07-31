# Supervised-learning-challenge - Predicting Credit Risk

Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. 

I used lending_data.csv data to create machine learning models to classify the risk level of given loans. Specifically, I compared the Logistic Regression model and Random Forest Classifier.

# Retrieve the data
The data is located in the Resources folder.
* `lending_data.csv`
Import the data using Pandas.

# Predicting model’s performance 

In general, a random forest classifier model may perform better than the Logistic Regression model for a working dataset with higher number of features by reducing the risk of overfitting. The given dataset has just eight features. so Therefore, the overfitting may not be an issue in this case and the performances for both models may be similar with random forest model performing a touch better.


# Languages & Techniques
Python (pandas, jupyter notebook)
Supervised learning
Logistic Regression
Random forests classifier


# Results/Discussion
Performances of both the models are very similar, with model scores over 0.99. Less number of features in the working dataset may be the reason behind the similar performances. The Random Forest model showed a little better accuracy score but the difference is too small to choose one model over another.
