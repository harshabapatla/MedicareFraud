# MedicareFraud

# Introduction
In the United States, there is a sizable healthcare business with both private and public
organizations. The cost of medical services keeps rising, in part as a result of the aging
population growth. Between 2012 and 2014, U.S. health insurance spending increased by 6.7%
to reach $3 trillion, while Medicare spending, at nearly $600 billion, accounts for 20% of all
human services spending in the country. Due to the growing older population and the rising
expenditures of Medicare, cost-cutting measures are required. Reducing fraud is one way to
assist cover costs and lower overall payments. The goal of this project is to develop big data
solutions that have significant applicability at the intersection of the health care and protection
sectors.
# Organisational Benefits

1. Identify if a particular case is a potential fraud or not?
2. Identifying the region with most frauds in the medicare industry?
3. Which is the best model used that gives higher accuracy value based on the comparison
of different models tested on a given dataset?
4. Which age group has committed the most number of fraudulent cases?
5. Identify the top providers with fraudulent cases.
# Business Understanding
Under this section, we are trying to understand the different models that we are using
here. The first step is to visualize the data in various forms. These include Data exploration,
cleansing and preparation. Then we are building a simple data model to join all datasets. Here,
we plan to use feature engineering to choose the effective feature sets for the different fraud
patterns. Later we are building a machine learning model to detect the different fraud patterns.
# Data Understanding
This step involves understanding the raw data that will be used to solve the problem. This
means understanding the data attributes and problems as well as the relationship between data
attributes and the problem. That is the one main reason we do data pre-processing to eliminate
unwanted fields and null values from the dataset. The pre-processing steps include cleaning the
data by removing duplicates, removal of outliers, factoring the categorical data, removing the
data based on general information only needed for analysis and performing data sampling. The
dataset looks more imbalanced and so in terms of fraud detection context the dataset is very
skewed with 99% no fraudulent cases and less than 1% fraudulent cases.
# Data Preparation
After understanding the business and data, the next step is data preparation. In this step,
some classification codes are run on the data set using machine learning or data mining library.
For data mining activities, each library provides functions that take data from files and require
the data set to be saved in a specific format (CSV). In order to use machine learning or a data
mining library, we have identified the data for our project and will store it in CSV format.
# Modeling
This step involves applying data mining methods, running actual code, building models
to solve the data mining task. In this step, we have performed logistic regression for machine
learning modeling and Gaussian naive bayes classifier. We will ensure that these patterns
represent the true regularities in the data and not some anomalies that do not generalize beyond
the data used for mining. Standardscaler is used for the main task when performing feature
engineering. Random forest classifier and Gradient boosting classifier are two main concepts we
use for analyzing the data after feature engineering is performed.
# Evaluation
After running the code and performing the required tasks, the results are obtained based
on the modeling we performed with the data. We evaluate the dataset based on the results we
obtained. We are making sure that these patterns reflect the data's genuine regularities rather than
some anomalies that are specific to the data utilized for mining. We check if all types of fraud
patterns are detected and we figure out the best resulting model considering all the factors used
for ML and analysis.
# Deployment
This is the concluding stage for the data analysis and the machine learning process we
have performed to be brought into execution. In order to get some return on investment, it
includes applying the data mining results in decision-making. To automate the decision-making
process, more data is gathered and we use the data mining techniques to make better
visualizations and perform better analysis. At the end, we see that a random forest classifier
gives an accuracy rate of 72%.
# TECHNOLOGIES EMPLOYED:
## Python: 
      We have used pandas to read and check the column number using a shape function, a data frame that drops the column that has the most frequently repeating or common values.
## Exploratory Data Analysis: 
      EDA is used in our 1st question where we check the beneficiary data and deduce that most of the beneficiaries are from the years - 1919 to 1943.
## Feature engineering:
      An example of using feature engineering is when we see that there is no difference in the distribution of Claim Duration for Potentially Fraud and Non-Fraud Providers.
Here, we reach the conclusion that Claim Duration alone might not be useful in segregating the Fraud cases.


