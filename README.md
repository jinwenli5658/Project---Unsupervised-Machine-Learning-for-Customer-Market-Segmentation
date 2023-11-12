# Project: Unsupervised Machine Learning-for Customer Market Segmentation

## Problem
Apply unsupervised machine learning algorithm to perform bank customer segmentation.

## Data Columns
CUSTID: Identification of Credit Card holder <br />
BALANCE: Balance amount left in customer's account to make purchases <br />
BALANCE_FREQUENCY: How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated) <br />
PURCHASES: Amount of purchases made from account <br />
ONEOFFPURCHASES: Maximum purchase amount done in one-go <br />
INSTALLMENTS_PURCHASES: Amount of purchase done in installment <br />
CASH_ADVANCE: Cash in advance given by the user <br />
PURCHASES_FREQUENCY: How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased) <br />
ONEOFF_PURCHASES_FREQUENCY: How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased) <br />
PURCHASES_INSTALLMENTS_FREQUENCY: How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done) <br />
CASH_ADVANCE_FREQUENCY: How frequently the cash in advance being paid <br />
CASH_ADVANCE_TRX: Number of Transactions made with "Cash in Advance" <br />
PURCHASES_TRX: Number of purchase transactions made <br />
CREDIT_LIMIT: Limit of Credit Card for user <br />
PAYMENTS: Amount of Payment done by user <br />
MINIMUM_PAYMENTS: Minimum amount of payments made by user  <br />
PRC_FULL_PAYMENT: Percent of full payment paid by user <br />
TENURE: Tenure of credit card service for user <br />

## Tasks:
(1) Understand the problem statement and business case <br />
(2) Import libraries and datasets <br />
(3) Visualize and explore datasets <br /> 
(4) Understand the theory and intuition behind k-means clustering machine learning algorithm <br />
(5) Learn how to obtain the optimal number of clusters using the elbow method <br />
(6) Use Scikit-Learn library to find the optimal number of clusters using elbow method <br />
(7) Apply k-means using Scikit-Learn to perform customer segmentation <br />
(8) Apply Principal Component Analysis (PCA) technique to perform dimensionality reduction and data visualization. <br />
