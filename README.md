BerkeleyX: CS190.1x Scalable Machine Learning

WEEK 0: Setup Course Software Environment 
Topics: Step-by-step instructions for installing / using the course software environment, and submitting assignments to the course autograder. 

WEEK 1: Course Overview and Introduction to Machine Learning - Launches June 29 at 16:00 UTC
Topics: Course goals, Apache Spark overview, basic machine learning concepts, steps of typical supervised learning pipelines, linear algebra review, computational complexity / big O notation review.
Lab 1: NumPy, Linear Algebra, and Lambda Function Review. Gain hands on experience using Python's scientific computing library to manipulate matrices and vectors, and learn about lambda functions which will be used throughout the course. 

WEEK 2: Introduction to Apache Spark 
Topics: Big data and hardware trends, history of Apache Spark, Spark's Resilient Distributed Datasets (RDDs), transformations, and actions. 
Lab 2: Learning Apache Spark. Perform your first course lab where you will learn about the Spark data model, transformations, and actions, and write a word counting program to count the words in all of Shakespeare's plays.  
Note to CS100.1x students: This material is identical to Week 2 of BerkeleyX CS100.1x, and if you've already completed Lab 1 of CS100.1x you can simply submit your completed notebook to receive credit.

WEEK 3: Linear Regression and Distributed Machine Learning Principles 
Topics: Linear regression formulation and closed-form solution, distributed machine learning principles (related to computation, storage, and communication), gradient descent, quadratic features, grid search.
Lab 3: Millionsong Regression Pipeline. Develop an end-to-end linear regression pipeline to predict the release year of a song given a set of audio features. You will implement a gradient descent solver for linear regression, use Spark's machine Learning library ( mllib) to train additional models, tune models via grid search, improve accuracy using quadratic features, and visualize various intermediate results to build intuition. 

WEEK 4: Logistic Regression and Click-through Rate Prediction  
Topics: Online advertising, linear classification, logistic regression, working with probabilistic predictions, categorical data and one-hot-encoding, feature hashing for dimensionality reduction.
Lab 4: Click-through Rate Prediction Pipeline. Construct a logistic regression pipeline to predict click-through rate using data from a recent Kaggle competition. You will extract numerical features from the raw categorical data using one-hot-encoding, reduce the dimensionality of these features via hashing, train logistic regression models using mllib, tune hyperparameter via grid search, and interpret probabilistic predictions via a ROC plot.

WEEK 5: Principal Component Analysis and Neuroimaging 
Topics: Introduction to neuroscience and neuroimaging data, exploratory data analysis, principal component analysis (PCA) formulations and solution, distributed PCA.
Lab 5: Neuroimaging Analysis via PCA - Identify patterns of brain activity in larval zebrafish. You will work with time-varying images (generated using a technique called light-sheet microscopy) that capture a zebrafish's neural activity as it is presented with a moving visual pattern. After implementing distributed PCA from scratch and gaining intuition by working with synthetic data, you will use PCA to identify distinct patterns across the zebrafish brain that are induced by different types of stimuli. 
