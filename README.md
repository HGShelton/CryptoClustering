# CryptoClustering
In this challenge, cryptocurrency data is used to determine the impact of using fewer features to cluster the data using K-means.

To do this, I used Python and Unsupervised Learning to normalize the data using the StandardScaler() to improve model performance. The elbow method was used with the scaled data to find the best value for K, 4. A scatter-plot was created with hvPlot using the best K value, of 4, to visualize the cryptocurrency clusters. 

Principal Component Anaylsis (PCA) was performed on the original scaled data with features reduced to three components. The analysis discovered approximately 89.5% of the total variance is condensed into the 3 PCA variables. The elbow method was also used to determine the best K value for the PCA data resulting in a value of 4, the same as the K value for the original data. As with the original data, a scatter-plot was created with hvPlot using the PCA best K value to visualize the PCA data clusters.

After visually analyzing both cluster analysis results, I was able to conclude that using fewer features to cluster the data will provide a similar performance to the original model as four seperate clusters can easily be identified within the PCA plot, as was seen with the original data.
