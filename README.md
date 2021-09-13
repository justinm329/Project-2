# Home Credit Risk Model

## Description
* The purpose of this project is to show how automating loans can be cost effective for financial institutions, and to prove that having a credit score does not have to used. The data we used was from Kaggle helped predict home loan applications approval or deny. We used four models to do this, Logistic Regression, Random Forest, Neural Networks and Gradient Boosting. We combined and cleaned all the datasets that were provided and ran each model. Since there is alot of data to train some of these models are best if run on google colab.

## Odjective 
* We determined that since data was unbalanced Logistic Regression was not a good model to use. We also ran into difficulties when combining the data because the csv files were overlapping causing overfitting. Once we figured this out it was determined that the Gradient Boosting Model was the most accurate. The Random Forest Classifier once it was tuned the right was able to make ok predictions however it was not a model that would work in the real world. If more techniques were used like hyper parameter, it could possibly produce better results. Neural Network is a possible however the data was not cleaned properly so the score is off a bit, once it is fixed, we predict this could be a great model to use. If any model was used to predict whether a person would default or not on a home loan this could save financial institutions a lot of money. It could save clients time and make more money for the company by eliminating jobs, and create a positive customer experience by approving loans in a timely manner.

## Data Files

* The data that was used is in the link below:
https://drive.google.com/drive/folders/12lt73pCd-lLwWxNR5AOnZlYwsGznHPAf

## Libraries and Dependencies
- [numpy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [tensorflow](https://www.tensorflow.org/)
- [keras](https://keras.io/)
- [sklearn](https://scikit-learn.org/stable/)
- [garbage collector](https://docs.python.org/3/library/gc.html)
- [LightGBM](https://lightgbm.readthedocs.io/en/latest/Python-Intro.html)
- [eli5](https://eli5.readthedocs.io/en/latest/overview.html)

## Installations

`pip install pandas`

`pip install numpy`

`pip install hvplot`

`pip install --upgrade tensorflow`

`pip install keras`

`pip install -U scikit-learn`

`pip install eli5`

`pip install lightgbm`

`pip install gc-python-utils`

## Contact Informtion
- **Justin Farnan**
- **Email**: justinm329@yahoo.com
- **LinkedIn**: [LinkedIn](https://www.linkedin.com/in/justin-farnan/)
- **Medium**: [Medium](https://medium.com/@justinfarnan)
