\# Hybrid Amazon item recommender system

Using Amazon item metadata as well as user review data from 2018, this
project will attempt to build a hybrid recommender system with an
unsupervised, collaborative filtering model and a supervised,
content-based filtering model.

\#\# Project Pipeline

\#\#\# Data Acquisition

All data are acquired from this website:

http://jmcauley.ucsd.edu/data/amazon/

\#\#\# Data Processing

-   Getting rid of nulls and duplicates. Turning categorical features
    > into numerical features by using one-hot encoding and Weight of
    > Evidence Encoding.

-   Merging the user reviews together with metadata

\#\#\# Machine Learning attempts

\#\#\#\# Supervised

A preliminary round of selection was done on 6 models:
KNN,LinearRegression, DecisionTree, RandomForest, XGBoost, Naive-Bayes.
XGBoost and RandomForest were the most promising and a gridsearch was
conducted on both of them for hyperparameter tuning.

\#\#\#\# Unsupervised

Surprise package was used to build a basic SVD model based on user,item
and rating.

\#\# Deliverables

\#\#\#\# Notebooks

\[EDA\](/Notebooks/EDA.ipynb)

\[Machine Learning/Visualization\](Pipeline.ipynb)

\#\#\#\# Presentation

\[Amazon\_Recommender.pdf\](/Presentation/Amazon\_Recommender.pdf)

\[Amazon\_Recommender.pptx\](/Presentation/Amazon\_Recommender.pptx)
