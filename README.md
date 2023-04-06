# Regression

Video Link - https://youtu.be/WWp5DsZDZEc

CSV file - https://drive.google.com/drive/folders/1jX69dDqy-FHKJLC5xBGv_YAs9-CWonuX?usp=sharing

![1_9pnItU2ZbID4PdnTVt2FzQ](https://user-images.githubusercontent.com/111626329/229420468-265e51f4-130d-4f34-bcdb-26e8f7627aef.png)

Problem Description <br>
Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store
managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are
influenced by many factors, including promotions, competition, school and state holidays, seasonality,
and locality. With thousands of individual managers predicting sales based on their unique
circumstances, the accuracy of results can be quite varied. You are provided with historical sales data
for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. Note that some
stores in the dataset were temporarily closed for refurbishment.


Observation <br>
This dataset is a live dataset of Rossmann Stores. On analysing this problem we observe that
rossmann problem is a regression problem and our primarily goal is to predict the sales figures of
Rossmann problem. In this Notebook we work on following topics Analysing the dataset by using
Exploratory Data Analysis using exponential moving averages analyse trends and seasonality in
Rossmann dataset Analyse Regression using following prediction analysis.
After Performing different Analysis, we got the following results,  <br>
A) Linear Regression Analysis = 82.553157, 82.417202 <br>
B) Elastic Regression <br>
Ridge Regression = 82.565288, 82.430543 <br>
Lasso REgression = 82.565283, 82.430356 <br>
C) Dession tree Regression = 93.930798, 92.915127 BEST <br>
D) Random Forest Regressor = 87.404635, 87.30734 <br>
