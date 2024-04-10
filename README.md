# Blood Donation Prediction with Logistic Regression using TPOT  

This repository contains a Jupyter notebook and a .csv file containing a dataset from a mobile blood donation vehicle in Taiwan. The Blood Transfusion Service Center drives to different universities and collects blood as part of a blood drive. We want to predict whether or not a donor will give blood the next time the vehicle comes to campus.  
 
The data is stored in datasets/transfusion.data and it is structured according to RFMTC marketing model (a variation of RFM).

## About the Dataset

RFM stands for Recency, Frequency and Monetary Value and it is commonly used in marketing for identifying your best customers. In our case, our customers are blood donors.

RFMTC is a variation of the RFM model. Below is a description of what each column means in our dataset:

- R (Recency - months since the last donation)
- F (Frequency - total number of donation)
- M (Monetary - total blood donated in c.c.)
- T (Time - months since the first donation)
- a binary variable representing whether he/she donated blood in March 2007 (1 stands for donating blood; 0 stands for not donating blood)

## Project Overview

The goal of this project is to experience and utilize TPOT, an automated machine learning tool that optimizes machine learning pipelines using genetic programming.  

For further information about TPOT, you can visit [https://epistasislab.github.io/tpot/](https://epistasislab.github.io/tpot/)   

The stages of the project are as follows:
- Importing Libraries
- Loading the Dataset
- Initial Exploration
- Data Preprocessing
- Data Visualization
- Model Selection with TPOT
- Scaling Data using StandardScaler 
- Model Training and Prediction
- Calculating AUC Score

## Libraries Used

- NumPy
- Pandas
- MatplotLib
- Seaborn
- Scikit-learn



