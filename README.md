# Cryptocurrencies

## Overview
Purpose of this is to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment. Since there are no known output, I've decided to use unsupervised machine learning and to group the cryptocurrencies, the clustering algorithm is used. 

## Results:
- The Elbow Curve with K-means = 4
<img width="850" alt="Elbow_Curve" src="https://user-images.githubusercontent.com/33046642/158102985-5c4baebd-7ede-4554-a56e-d4227bd76a78.png">

- K-Means Clustering 3D Scatterplot
<img width="828" alt="scatterplot_3d" src="https://user-images.githubusercontent.com/33046642/158102991-57c8341c-6b0d-4619-a50d-778b5306b165.png">

- Table of Tradable Cryptocurrencies
<img width="873" alt="tradable_table" src="https://user-images.githubusercontent.com/33046642/158103000-1e882713-4cd8-4006-a569-fbac50695e97.png">

- Scaled Tradable Cryptocurrencies 2D Scatterplot
<img width="873" alt="scatterplot_2d" src="https://user-images.githubusercontent.com/33046642/158103006-bf5008f3-eb39-4f5b-a071-e829b33dc0ee.png">


## Summary
The following was accomplished in this report: 
- preprocess the data for PCA (Principal component analysis) 
- reduce the dimensions using PCA
- clustering cryptocurrencies using K-means and 
- visualizing the cryptocurrencies results in 2D and 3D hvplot.
