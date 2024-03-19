# crypto-clustering
## background
In this challenge, you’ll use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

##Instructions
1. Prepare the Data
    - Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file.

    - Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.

2. Find the Best Value for k Using the Original Scaled DataFrame
    - Use the elbow method to find the best value for k

3. Cluster Cryptocurrencies with K-means Using the Original Scaled Data

4. Optimize Clusters with Principal Component Analysis
    - Using the original scaled DataFrame, perform a PCA and reduce the features to three principal components.

5. Find the Best Value for k Using the PCA Data
    - Use the elbow method on the PCA data to find the best value for k

6. Cluster Cryptocurrencies with K-means Using the PCA Data
