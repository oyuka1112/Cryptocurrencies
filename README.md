# Cryptocurrencies
## Overview
Created a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment by processing to fit the machine learning models. Since there is no known output for what we're looking for, I decided to use unsupervised learning: a clustering algorithm. 
Used the followings:
- preprocessing the database,
- reducing the data dimension using Principal Component Analysis,
- clustering cryptocurrencies using K-Means,
- visualizing classification results with 2D and 3D scatter plots. 
## Results
1. Cleaned the dataframe
2. Scaled the data
3. Reduced dimensions using PCA 98 columns to 3 PCA
4. Clustering Cryptocurrencies using k-means
5. Find the best k means by iterating from 1 to 10. The best one is 4.
![](https://user-images.githubusercontent.com/64121596/156303333-334f2d99-a784-4309-80ea-2d32b6f58a1e.png)
6. Predicted the clusters it with 4 clusters
7. Created a 3D-Scatter with the PCA data and the clusters
![](https://user-images.githubusercontent.com/64121596/156303950-449ffee2-a3df-4e9b-a3a4-8fcdbf77f238.png)
8. Clustered Dataframe
![](https://user-images.githubusercontent.com/64121596/156304450-6db935da-bcb8-4c38-80b6-3440703e6c95.png)
10. Created a hvplot.scatter plot using x="TotalCoinsMined" and y="TotalCoinSupply"
![](https://user-images.githubusercontent.com/64121596/156304823-82d80f1c-cbd0-42df-a52c-ac7c878becac.png)

