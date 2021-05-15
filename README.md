# Udacity Data  Science Capston Project: Starbucks Capstone Challenge
This project is a the capstone project of Udacity [Data Science Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025)
## Table of Contents
1. Project Overview
2. Project Components
3. Installation
4. File Descriptions
5. Instructions
6. Results
7. Acknowledgements

## 1. Project Overview
This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks. The task is to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type. This data set is a simplified version of the real Starbucks app because the underlying simulator only has one product whereas Starbucks actually sells dozens of products.

## 2.Project Components
The problem I chose to solve is to build a machine learning model that can predict if customers will respond to certain type of offer. The steps of the project are as following:
- Cleaning the three data sets.
- Exploratory data analysis. Questions I explored:
  1. How many customers received offers in this dataset? What kind of offers did they recieve?
  2. Customer Analysis: What do the customers look like (age, gender, income, etc.)? 
  3. Offer Analysis: How effective are the offers? What kind of offer are more effective to drive order?
- Merge the three cleaned datasets and prepare data for model training
- Build machine learning models to predict the offer usage:
  1. Define features & target and create train and test datasets
  2. Train Classifier
  3. Model Refinement
  4. Feature importance
  5. Predict test tata and draw confusion matrix
- Conclusion
- Improvements
