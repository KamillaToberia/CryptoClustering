# CryptoClustering Challenge

###Purpose

In this challenge, you’ll use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

###Steps

- Prepare the Data:
  - Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file.
  - Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.

- Find the Best Value for k Using the Original Scaled DataFrame:
  -  Use the elbow method to find the best value for k
  -  Answer the following question in your notebook: What is the best value for k?
    The best value for k is 4.

- Cluster Cryptocurrencies with K-means Using the Original Scaled Data.

- Optimize Clusters with Principal Component Analysis:
  - Using the original scaled DataFrame, perform a PCA and reduce the features to three principal components.
  - What is the total explained variance of the three principal components?
    The total explained variance is 87%.

- Find the Best Value for k Using the PCA Data:
  - Answer the following question in your notebook:
      What is the best value for k when using the PCA data?
      The best value for k using PCA data is 4.
      Does it differ from the best k value found using the original data?
      No.

  - Cluster Cryptocurrencies with K-means Using the PCA Data.
