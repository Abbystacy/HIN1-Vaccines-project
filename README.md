# HIN1-Vaccines-project
**Project Overview**

This project analyzes factors that influence individuals’ decisions to receive the H1N1 flu vaccine during the 2009 pandemic. Using survey data collected , the analysis explores how demographic characteristics, socioeconomic conditions, health status, and personal perceptions about vaccines affect vaccination behavior.

Through exploratory data analysis and machine learning techniques, the project identifies key variables associated with vaccine uptake and builds predictive models to estimate the likelihood of individuals receiving the H1N1 vaccine. The insights generated from this analysis can help inform public health strategies aimed at improving vaccination rates and addressing barriers to vaccine adoption.

**Business Understanding**

This project addresses an important public health challenge by predicting the likelihood that individuals will receive the H1N1 and seasonal flu vaccines based on their demographic characteristics, personal beliefs, and health-related behaviors. By analyzing these factors, the study provides insights into the patterns that influence vaccination decisions.
The findings can support public health authorities, healthcare providers, and policymakers in improving vaccine distribution strategies, designing more effective communication campaigns, and developing targeted interventions aimed at increasing vaccination uptake within communities.

**Data Understanding**
This dataset originates from the National Flu Survey (NHFS) of 2009, a survey conducted to understand public behavior and attitudes regarding influenza vaccination, specifically targeting the H1N1 flu vaccine.

**Modeling**
In the modeling stage, machine learning models were developed to predict whether an individual received the H1N1 vaccine. A Logistic Regression model was first implemented as a baseline . A Random Forest model was then trained to capture more complex relationships in the data. Additionally, an ensemble model combining multiple algorithms was implemented to improve predictive performance. 

**Findings**
Two models were developed to predict H1N1 vaccine uptake: Logistic Regression as the baseline model and Random Forest as a more advanced model. The Logistic Regression model achieved an accuracy of about 77% with an ROC-AUC of 0.82, showing good ability to distinguish between vaccinated and non-vaccinated individuals, though it produced more false positives. The Random Forest model also demonstrated strong predictive performance, correctly identifying a large number of individuals who did not receive the vaccine and reducing false positives. However, it missed more vaccinated individuals. Overall, both models performed well but showed different strengths in predicting vaccination behavior.

**Conclusions**
The findings highlight the need to address people’s health concerns and support better awareness to encourage higher vaccination uptake. Public health authorities can use the factors identified in this analysis to design more effective vaccination campaigns and communication strategies aimed at improving public confidence in vaccines.
