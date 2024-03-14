# CryptoClustering

* For this analysis on cryptocurrencies, I prepared the data using StandardScaler() from scikit-learn, which allowed me to normalize the data in the csv file on cryptocurrencies.
* The data provided on the cryptocurrencies included price changes over different time periods on cryptocurrency stocks ranging from 24 hrs. to 1 yr.
* The elbow method was used to find the best value for k. The best value for k was identified as 4.
* The original scaled data was clustered using K-means and the best value of (k). The model-fit-predict method was followed, and a scatterplot was created using hvPlot.
* Using Principal Component Analysis (PCA), the clusters were optimized by reducing the features to 3 principal components. Approximately 90% of the variance could be explained by the 3 principal components.
* This method was repeated using the PCA data. The best value of k was found to be 4 again. A scatterplot was created with the predictive clusters, and a visual comparison was made between the plots of the original data and the PCA data.
