# HIN1-Vaccines-project
**Project Overview**

This project analyzes factors that influence individuals’ decisions to receive the H1N1 flu vaccine during the 2009 pandemic. Using survey data collected , the analysis explores how demographic characteristics, socioeconomic conditions, health status, and personal perceptions about vaccines affect vaccination behavior.

Through exploratory data analysis and machine learning techniques, the project identifies key variables associated with vaccine uptake and builds predictive models to estimate the likelihood of individuals receiving the H1N1 vaccine. The insights generated from this analysis can help inform public health strategies aimed at improving vaccination rates and addressing barriers to vaccine adoption.

**Business problem**

Vaccine reluctance remains a major obstacle to public health initiatives, as it can reduce vaccination rates and increase the risk of disease outbreaks. Gaining insight into the factors that influence individuals’ decisions to accept or decline vaccines is essential for developing strategies that encourage higher vaccination uptake. This project aims to use machine learning methods to predict whether individuals are likely to receive the H1N1 flu vaccine, using data collected from the National Flu Survey (NHFS 2009).

**Data Understanding**

This dataset originates from the National Flu Survey (NHFS) of 2009, a survey conducted to understand public behavior and attitudes regarding influenza vaccination, specifically targeting the H1N1 flu vaccine. The data includes perception-based variables such as:

Perceived risk of H1N1 infection, Beliefs about vaccine effectiveness ,Concerns about vaccine safety
and the target variable H1N1 vaccine.

**EDA data analysis**

EDA was conducted to understand data distribution and relationships between variables.

Key insights explored:

Vaccine uptake distribution ,Effects of doctor's recommendation ,perception of vaccine effectiveness,risk perception and demographic factors.

**Data cleaning and processing**

Data preprocessing was implemented using a pipeline to ensure consistency and avoid data leakage.
Key steps included:

1.Handling missing values:

   Median imputation for numerical features

   Most frequent imputation for categorical features

2.Scaling numerical variables using StandardScaler

3.Encoding categorical variables using OneHotEncoder

4.Applying transformations using a ColumnTransformer


**Modeling**

In the modeling stage, machine learning models were developed to predict whether an individual received the H1N1 vaccine. A Logistic Regression model was first implemented as a baseline . A Random Forest model was then trained to capture more complex relationships in the data. Additionally, an ensemble model combining multiple algorithms was implemented to improve predictive performance. 

**Findings**

Two models were developed to predict H1N1 vaccine uptake: Logistic Regression as the baseline model and Random Forest as a more advanced model. The Random forest model achieved an accuracy of about 83% with an ROC-AUC of 0.82, showing good ability to distinguish between vaccinated and non-vaccinated individuals. 

**Conclusions**

The findings highlight the need to address people’s health concerns and support better awareness to encourage higher vaccination uptake. Public health authorities can use the factors identified in this analysis to design more effective vaccination campaigns and communication strategies aimed at improving public confidence in vaccines.
