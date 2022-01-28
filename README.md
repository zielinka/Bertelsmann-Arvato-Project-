# Bertelsmann-Arvato-Project


### Table of Contents

1. [Installation](#installation)
2. [Project Overview](#motivation)
3. [File Descriptions](#files)
4. [Licensing, Authors, and Acknowledgements](#licensing)


## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.


## Project Overview<a name="motivation"></a>

There are three components completed for this project:

1. the customer segmentation report, 
2. the supervised learning model,
3. the Kaggle Competition.

I started the project using unsupervised learning techniques to analyse customer features and the general population in order to create customer segments. The goal is to perform a customer segmentation to predict which part of the general population should be targeted as future customers.
Having response information (target) from mail campaign, I used supervised learning methods to build a machine learning model that predicts if each individual will respond to the marketing campaign. A model with the best accuracy I used to make predictions on the mail campaign dataset as part of the Kaggle Competition. Model ranks the individuals and predicts the response of a person in a future campaign. It provides us with insight how likely the individual is to become customer.

Please find detailed overview of the project in blog post:

## File Descriptions<a name="files"></a>

There are four data files associated with this project:

    • Udacity_AZDIAS_052018.csv: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
    • Udacity_CUSTOMERS_052018.csv: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
    • Udacity_MAILOUT_052018_TRAIN.csv: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
    • Udacity_MAILOUT_052018_TEST.csv: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).
    • DIAS Information Levels - Attributes 2017.xlsx: A top-level list of attributes and descriptions.
    • DIAS Attributes - Values 2017.xlsx: A mapping of data values for features.


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Bertelsmann/Arvato for the data. Data Scientist NanoDegree content has been used to create the project. They provided the data from Bertelsmann/Arvato.

