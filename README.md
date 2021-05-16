# Udacity Data  Science Capston Project: Starbucks Capstone Challenge
This project is a the capstone project of Udacity [Data Science Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025)
## Table of Contents
1. [Project Overview](#overview)
2. [Project Components](#components)
3. [Installation](#installation)
4. [File Descriptions](#descriptions)
5. [Instructions](#instructions)
6. [Results](#results)
7. [Acknowledgements](#acknowledgements)

## 1. Project Overview <a name="overview"></a>
This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks. The task is to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type. This data set is a simplified version of the real Starbucks app because the underlying simulator only has one product whereas Starbucks actually sells dozens of products.

## 2.Project Components <a name="components"></a>
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

## 3. Installation <a name="installation"></a>
- The code are runing on python 3.* 
- Data Processing Libraries: NumPy, Pandas, Math, Json
- Data Visualization Libraries: Matplotlib, Seaborn
- Meachine Learning Library: Sciki-Learn

## 4. File Descriptions <a name="descriptions"></a>
The data is contained in three files:
- portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
- profile.json - demographic data for each customer
- transcript.json - records for transactions, offers received, offers viewed, and offers completed

Here is the schema and explanation of each variable in the files:
### portfolio.json
- id (string) - offer id
- offer_type (string) - type of offer ie BOGO, discount, informational
- difficulty (int) - minimum required spend to complete an offer
- reward (int) - reward given for completing an offer
- duration (int) - time for offer to be open, in days
- channels (list of strings)
### profile.json
- age (int) - age of the customer
- became_member_on (int) - date when customer created an app account
- gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
- id (str) - customer id
- income (float) - customer's income
### transcript.json
- event (str) - record description (ie transaction, offer received, offer viewed, etc.)
- person (str) - customer id
- time (int) - time in hours since start of test. The data begins at time t=0
- value - (dict of strings) - either an offer id or transaction amount depending on the record

## 5. Instructions <a name="instructions"></a>
- The analysis is stored in the Jupyter notebook: [Starbucks_Capstone_notebook.ipynb](https://github.com/jdhuasirui/udacity_data_science_capstone_starbucks/blob/main/Starbucks_Capstone_notebook.ipynb)
- The three json files of the original data sets are in the data folder

## 6. Results <a name="results"></a>
The introduction and main finding of the project can be found at the post available [here](#).

## 7. Acknowledgements <a name="acknowledgements"></a>
This project is a the capstone project of Udacity [Data Science Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025). This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app.
