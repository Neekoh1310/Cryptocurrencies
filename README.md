# Cryptocurrencies

## Overview

In this project, I was tasked to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment. "Crypto" is an undiscovered wilderness for Accountability Accounting, and they need my analytical skills in order to navigate it. I am going to use my machine learning skills in order to provide some guidance to Accountability Accounting.

## Resources

- Python, Jupyter Notebook, Pandas, Scikit-learn(Kmeans, PCA), hvplot, plotly

## Results

1.) The data provided from the source file "crypto_data" was manipulated in order show the cryptocurrencies that are being traded, and have a working algorithm. Rows that have at least 1 null value were also dropped.
![Data](https://user-images.githubusercontent.com/102476861/181670509-70f0b033-1f5b-4a3b-838a-ccb5d53a9d53.png)

2.) A dataframe was created with 3 principal components. 
![Principal Components](https://user-images.githubusercontent.com/102476861/181670569-bb9f566c-95e1-4d47-8fa5-493fd851a688.png)

3.) Elbow Curve to find the best value for K.
![Elbow Curve](https://user-images.githubusercontent.com/102476861/181670607-256b178b-602a-4fd4-be10-05ff07fca197.png)

4.) A new dataframe was created by merging the original dataframe with the 3 principal components.
![Clustered DF](https://user-images.githubusercontent.com/102476861/181670637-bfa2f8f7-c37e-4604-b4d3-f5e46c8a1f52.png)

5.) The 3D-Scatter plot with the PCA data and the clusters
![3D Scatter](https://user-images.githubusercontent.com/102476861/181670727-f0f1761e-b486-40a8-9a30-85f5377eb00c.png)

6.) The table of tradable cryptocurrencies
![Tradable Crypto](https://user-images.githubusercontent.com/102476861/181670834-c8771123-81cd-4e1c-80b6-ecbe46d5706f.png)

7.)Scatter plot of Total Coins Mined vs. Total Coin Supply
![Plot Scatter TCxTCS](https://user-images.githubusercontent.com/102476861/181670855-132ba98a-c4e6-4e29-92eb-fbbe3d7579d4.png)

## Summary

After running the analysis on the cryptocurrencies data, a total of 532 tradable cryptocurrencies were identified. However, further analysis is required in order to identify which of these cryptocurrencies are worth investing in. 
