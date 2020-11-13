# WineQualityPrediction

### Problem Statement
We take the problem of predicting the quality of wine with the help of a given dataset. The Wine Quality data from UCI’s repository has been used. We implement the KNN classifier using brute force technique. For this binary classification task, we vary various techniques to find an optimal KNN model to fit into the data and make the predictions.

### Introduction
Wine quality has been one of the interesting topics among wine enthusiasts. This can be attributed to quality being primarily a subjective and influenced by extrinsic factors. What is accepted is that wine quality is the result of a complex set of interactions. In this report, classification of wine is done based on physio-chemical composition of different wines.

### Data Summary
The dataset classifies the white wine samples from Portugal. The dataset is obtained from UCI, where the physiochemical properties of white wine are listed. There is a total of 4989 data samples that are used to determine the quality of the wine. The quality of the wine is scored in a scale of 3 to 8. However, for the purpose of binary classification, we convert this scale to represent it in terms of Good and Bad wine. If the quality is greater than 5, it is classified as good wine. On the other hand, if it is less than or equal to 5, it is classified as bad wine. We represent good and bad wine by 1 and 0 respectively.

STEPS:

    1. Data Cleaning
    2. Exploratory Data Analysis - Feature Extraction
    3. Standardization (if required)
    4. K Nearest Neighbors (KNN) Classification
    5. Model Analyis
