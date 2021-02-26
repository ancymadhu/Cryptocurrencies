# Cryptocurrencies

![1](https://user-images.githubusercontent.com/73450637/109252304-319e9c00-77bb-11eb-96d8-6811d49c37c6.jpg)

## Analysis Overview

Purpose of this project is creating a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment. The following has to be achieved:

> 1: Preprocessing the Data for PCA

>2: Reducing Data Dimensions Using PCA

>3: Clustering Cryptocurrencies Using K-means

>4: Visualizing Cryptocurrencies Results


## Resources

* Data Source: crypto_data.csv
* Software: Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3

## Summary

> ### I. Preprocessing the Data for PCA

Dataset is preprocessed inorder to perfrom PCA. The following dataframe is generated at the end:

![2](https://user-images.githubusercontent.com/73450637/109267875-42113f80-77d8-11eb-8ea8-39553798b3fb.png)

> ### II. Reducing Data Dimensions Using PCA

Using the knowledge of how to apply the Principal Component Analysis (PCA) algorithm, the dimensions of the X DataFrame is reduced to three principal components and placed these dimensions in a new DataFrame.

![3](https://user-images.githubusercontent.com/73450637/109268128-a207e600-77d8-11eb-9ad4-e6fdcaf6585a.png)

> ### III. Clustering Cryptocurrencies Using K-means

Using the knowledge of K-means algorithm, an elbow curve is created using hvPlot to find the best value for K from the pcs_df DataFrame created in Step II. 

![4](https://user-images.githubusercontent.com/73450637/109268378-fca14200-77d8-11eb-87b7-427294b16091.png)

Then, the K-means algorithm is ran to predict the K clusters for the cryptocurrencies’ data.

![5](https://user-images.githubusercontent.com/73450637/109268548-3a9e6600-77d9-11eb-9bbd-9747118f75e8.png)

> ### IV. Visualizing Cryptocurrencies Results

Using the knowledge of creating scatter plots with Plotly Express and hvplot, the distinct groups that correspond to the three principal components are visualized.

![6](https://user-images.githubusercontent.com/73450637/109268738-818c5b80-77d9-11eb-9e15-898933d619dc.png)

A table with all the currently tradable cryptocurrencies using the hvplot.table() function is created. 

![7](https://user-images.githubusercontent.com/73450637/109268989-daf48a80-77d9-11eb-9f3c-2cb90e686179.png)

A scatter plot is created that show the CoinName when you hover over the the data point.

![8](https://user-images.githubusercontent.com/73450637/109269238-358de680-77da-11eb-9f91-a9c3a2dce1a0.png)
