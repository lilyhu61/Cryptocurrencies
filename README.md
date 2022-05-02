# Cryptocurrencies
## Overview
The purpose of this project is to use unsupervised machine learning to analyze a database of cryptocurrencies and create a report including the traded cryptocurrencies classified by group according to their features.
This classification report could be used by an investment bank to propose a new cryptocurrency investment portfolio to its clients.
We use the following methods for the analysis:
- Preprocessing the database
- Reducing the data dimension using Principal Component Analysis
- Clustering cryptocurrencies using K-Means
- Visualizing classification results with 2D and 3D scatter plots

## Results
Following the preprocessing and cleaning phase we have a total of 532 tradable cryptocurrencies.

### 1. Clustering Cryptocurrencies using K-Means - Elbow Curve


![Screen Shot 2022-05-01 at 10 15 04 PM](https://user-images.githubusercontent.com/95242493/166183510-6e63526a-32b7-4fe9-bd38-0c36a0bb9b29.png)

### 2. Visualizing Cryptocurrencies Results
  - **3D-Scatter plot with clusters**
  
      This 3-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components.

![Screen Shot 2022-05-01 at 10 18 16 PM](https://user-images.githubusercontent.com/95242493/166183700-797b1253-52f0-425a-99b6-7000dc208459.png)
 
 - **Tradable Cryptocurrencies Table**
 ![Screen Shot 2022-05-01 at 10 24 04 PM](https://user-images.githubusercontent.com/95242493/166184089-71d43442-9208-43c4-8a36-641d2965e2b0.png)


  - **D-Scatter plot with TotalCoinMined vs TotalCoinSupply**
  
    Plotting the scatter plot from two cryptocurrency features directly does not efficiently segregate the different classes. Then using the PCA algorithm is the right method for better visualizations.
![Screen Shot 2022-05-01 at 10 20 49 PM](https://user-images.githubusercontent.com/95242493/166183894-566159db-a960-4b4f-ac5b-dd307efc4481.png)

## Summary
We have identified the classification of 532 cryptocurrencies based on similarities of their features.
Particularities of each group need to be analyzed to determined their performance and potential interest for the investment bank's clients.


