# Cryptocurrencies and Unsupervised Machine Learning

## Overview
This project utilized a cryptocurrency trading database to explore unsupervised machine learning algorithms to identify clustered patterns and model variables using scatter plots and 3-D visualizations. The aim was to grant clarification out of the complexity of the cryptocurrency market, to show opportunites for forming an investment portfolio.

## Results
Clustering using the K-Means Elbow Curve measuring k values iterating from 1 through 10, against inertia, shows a best k value of 4 clusters:
<img width="702" alt="Screen Shot 2022-02-19 at 10 50 04 PM" src="https://user-images.githubusercontent.com/91562577/154827733-44e58e50-42c1-4bb3-873f-f0b0d3924fd2.png">

3-D Visualization using Principal Component Analysis shows 4 identifiable classes:
<img width="725" alt="Screen Shot 2022-02-19 at 10 55 03 PM" src="https://user-images.githubusercontent.com/91562577/154827831-1d2b0c4f-54dd-4e11-854f-2e60941fc161.png">

Interactive table showing a total of 532 tradable cryptocurrencies:
<img width="713" alt="Screen Shot 2022-02-19 at 10 56 46 PM" src="https://user-images.githubusercontent.com/91562577/154827869-23815ccb-2ea9-46a9-a0d7-dc9b2fba1470.png">

Interactive 2-D scatter plot showing concentration and outliers of cryptocurrencies with total number of coins mined against total coin supply:
<img width="700" alt="Screen Shot 2022-02-19 at 10 58 51 PM" src="https://user-images.githubusercontent.com/91562577/154827906-936dc76c-9440-499a-834d-b9b6a33633cc.png">

## Summary
Data selection, processing, and transformation steps were undertaken to classify and organize the data. This enabled the identification of groups classified by feature. By reducing dimensions and reducing the principal components with PCA, the analysis provided insight into the most salient patterns in the market, for example by reducing the noise of cryptocurriencies lacking a working algorithm or not being actively traded. Using the K-Means model, the analysis identified tradable currencies and enabled visualization of  classes for investment.
