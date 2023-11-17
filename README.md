CryptoClustering Project Overview
This project harnesses the power of Python and unsupervised learning to forecast the impact of 24-hour or 7-day price changes on cryptocurrencies.

Getting Started:

Load and analyze the dataset "crypto_market_data.csv."
Normalize the data using StandardScaler.
Identify the optimal cluster count (k) employing the elbow method for both the original and PCA-transformed data.
Apply K-means clustering to the original dataset.
Utilize Principal Component Analysis (PCA) to condense features into three principal components.
Determine the optimal cluster count (k) for the PCA-transformed data.
Apply K-means clustering to the PCA-transformed dataset.
Key Questions to Answer:

What value of k yields the best results for both the original and PCA-transformed data?
How does the optimal k value for PCA data compare to that of the original dataset?
What are the implications of employing fewer features when using K-means clustering?
