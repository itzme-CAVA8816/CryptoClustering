# Cryptocurrency Clustering Analysis

## Project Overview
This project is for education and learning purposes. It applies unsupervised learning techniques to analyze and cluster cryptocurrencies based on their performance metrics. Using K-Means clustering and Principal Component Analysis (PCA), the project aims to group cryptocurrencies to understand similarities and performance patterns.

### Prerequisites

The starter files consist of the following files:  
- `Crypto_Clustering.ipynb`
- `crypto_market_data.csv`

## Technologies Used 
- Python
- Pandas
- scikit-learn
- hvPlot
- matplotlib

## Built With
- Visual Studio Code - The source code editor used for development.
- ChatGPT - AI model for generating documentation and guidance.

## Installation
To run this analysis, open the Crypto_Clustering.ipynb notebook in a Jupyter environment and execute the cells sequentially.

## Usage
To run this analysis, open the `Crypto_Clustering.ipynb` notebook in a Jupyter environment and execute the cells sequentially.

## Requirements
Find the Best Value for k Using the Original Scaled DataFrame (15 points)

- Code the elbow method algorithm to find the best value for k. Use a range from 1 to 11. 
- Visually identify the optimal value for k by plotting a line chart of all the inertia values computed with the different values of k. 
- Answer the following question: What’s the best value for k? 

Cluster Cryptocurrencies with K-Means Using the Original Scaled Data (10 points)

- Initialize the K-means model with four clusters by using the best value for k. 
- Fit the K-means model by using the original data.
- Predict the clusters for grouping the cryptocurrencies by using the original data. Review the resulting array of cluster values. 
- Create a copy of the original data, and then add a new column of the predicted clusters. 
- Using pandas’ plot, create a scatter plot by setting x="price_change_percentage_24h" and y="price_change_percentage_7d". 

Optimize the Clusters with Principal Component Analysis (10 points)

- Create a PCA model instance, and set n_components=3. 
- Use the PCA model to reduce the features to three principal components, then review the first five rows of the DataFrame. 
- Get the explained variance to determine how much information can be attributed to each principal component. 
- Answer the following question: What’s the total explained variance of the three principal components? 
- Create a new DataFrame with the PCA data. Be sure to set the coin_id index from the original DataFrame as the index for the new DataFrame. Review the resulting DataFrame.

Find the Best Value for k by Using the PCA Data (10 points)

- Code the elbow method algorithm, and use the PCA data to find the best value for k. Use a range from 1 to 11. 
- Visually identify the optimal value for k by plotting a line chart of all the inertia values computed with the different values of k. 
- Answer the following questions: What’s the best value for k when using the PCA data? Does it differ from the best value for k that you found by using the original data? 

Cluster the Cryptocurrencies with K-Means by Using the PCA Data (10 points)

- Initialize the K-means model with four clusters by using the best value for k. 
- Fit the K-means model by using the PCA data. 
- Predict the clusters for grouping the cryptocurrencies by using the PCA data. Review the resulting array of cluster values. 
- Create a copy of the DataFrame with the PCA data, and then add a new column to store the predicted clusters. 
- Using pandas’ plot, create a scatter plot by setting x="PC1" and y="PC2". 

Determine the Weights of Each Feature on Each Principal Component (15 points)

- Create a DataFrame that shows the weights of each feature (column) for each principal component by using the columns from the original scaled DataFrame as the index. 
- Answer the following question: Which features have the strongest positive or negative influence on each component? 

Coding Conventions and Formatting (10 points)

- Place imports at the top of the file, just after any module comments and docstrings, and before module globals and constants. 
- Name functions and variables with lowercase characters, with words separated by underscores. 
- Follow DRY (Don't Repeat Yourself) principles, creating maintainable and reusable code. 
- Use concise logic and creative engineering where possible. 

Deployment and Submission (10 points)

- Submit a link to a GitHub repository that’s cloned to your local machine and that contains your files. 
- Use the command line to add your files to the repository. 
- Include appropriate commit messages in your files. 

Code Comments (10 points)

- Be well commented with concise, relevant notes that other developers can understand. 

## Methodology
- Data normalization with `StandardScaler`.
- Determination of the optimal number of clusters using the Elbow Method.
- Application of K-Means clustering on both the original scaled data and PCA-reduced data.

## Results
- The optimal number of clusters was determined to be `k` based on the Elbow Method.
- Clusters were visualized to reveal the grouping of cryptocurrencies.
- PCA was used to reduce dimensionality and identify the features with the most significant influence on the dataset.

## Conclusion

This analysis provided valuable insights into cryptocurrency performance and revealed natural groupings based on market data analized.

## Contributing
This project benefits from the contributions of:
- edX Boot Camps LLC 

## Authors
* **edX Boot Camps** - *Initial work* 
* **Chris Alvarez** - *Final work*

## License
This project is not licensed and is available for educational and non-commercial use only.











