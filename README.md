# Algorithmic trading bot
This repo contains a combination of Python programming and machine learning to create an algorithmic trading bot that learns and adapts to new data and evolving markets.

---

## Summary

The Jupyter notebook, contains the following:

* Implementing an algorithmic trading strategy that uses machine learning to automate the trade decisions.

* Adjusting the input parameters to optimize the trading algorithm.

* Training a new machine learning model and compare its performance to that of a baseline model.

### *SVM:*
Support Vector Machine (SVM) is a relatively simple Supervised Machine Learning Algorithm used for classification and/or regression.

![SVM](/Resources/Screenshot%201.1.png)

*Classification Report.*

![SVM](/Resources/Screenshot%201.png)

*Actual returns versus the SVM returns*


SVM accuracy score: 0.55

### *Logistic Regression:*
In this model, the probabilities describing the possible outcomes of a single trial are modeled using a logistic function.

![LR](/Resources/Screenshot%202.1.png)

*Classification Report.*

![LR](/Resources/Screenshot%202.png)

*Actual returns versus the LR returns.*

LR accuracy score: 0.52

We can see that the accuracy of SVM is higher than the one for Logistic regression, therefore, and based on the plots, we can conclude than the SVM model performs better than the Logistic regression.

---

## Libraries

* Pandas
* Numpy
* Pathlib
* Hvplot
* Matplotlib.pyplot
* Sklearn -> SVM, StandardScaler, LogisticRegression
* DateOffset
* Sklearn.metrics -> classification_report

---

## License

[MIT](/license.txt)

