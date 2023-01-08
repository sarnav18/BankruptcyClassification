# Introduction

Firm collapse prediction has been a subject of interest for almost a century and it still ranks high among the hottest topics in economics. The aim of predicting financial distress is to develop a predictive model that combines various econometric measures and allows one to foresee a financial condition of a firm. The purpose of bankruptcy prediction is to assess the financial condition of a company and its future perspectives within the context of longterm operation on the market.

This project aims to apply data mining algorithms covered in the course in a real data competition. We would like to develop a predictive model that combines various econometric measures to predict if a firm will file for bankruptcy.

# Methodology
## Data Preprocessing
I started with splitting the dataset into 80%-20% ratio. For variable selection, a logistic regression with backward variable selection was run based on the criterion of misclassification. 

## Models Used
Two HP neural networks nodes and two gradient boosting nodes were run, and then the average of them was used for the final predictions. The “HP neural networks” and the “Gradient Boosting” nodes were used for this, and an ensemble node was utilized to average the results. 
