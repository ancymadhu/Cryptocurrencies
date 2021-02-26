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

> ### IV. Visualizing Cryptocurrencies Results

