# Machine Learning - Unsupervised Learning
Using Unsupervised Machine Learning Clustering techniques of K-Means and Hierarchical with dimensionality reduction technique of Principal Component Analysis.

## Data Set
The data set for this project is the "Wholesale Data" dataset containing information about various products sold by a grocery store.

## Project Outcomes
The project involves four main parts: 
- Exploratory data analysis and pre-processing,
- KMeans clustering, 
- Hierarchical clustering and
- PCA.

## Tasks accomplished

-   Exploratory data analysis and pre-processing: Importing and cleaned the data sets, analyze and visualize the relationships between the different variables, handle missing values and outliers, and perform feature engineering as needed.
-	Unsupervised learning: Used the Wholesale Data dataset to perform k-means clustering, hierarchical clustering, and principal component analysis (PCA) to identify patterns and group similar data points together.
-	Determined the optimal number of clusters and communicate the insights gained through data visualization.

<p align="center" width="70%" margin-top:'20px' margin-bottom:'20px'>
<img src="https://github.com/hrmn-preet/unsupervised-learning/blob/main/pca-variance.png" alt="pca-variance-explained" >
</img>
</p>

## Key Findings
***Based on the Exploratory Data Analysis (EDA) and the models developed, here are the key findings:***

### **1. Hierarchical Clustering Performance:**

Hierarchical clustering explains the dataset better and provides more meaningful clustering results compared to K-means clustering. This is likely due to the ability of hierarchical clustering to capture nested clusters and its flexibility in choosing the number of clusters through dendrogram analysis.

### **2.  Top Three Features:**
    
These features contribute significantly to the variance observed in the data, making them crucial for clustering.The top three features that explain the variance of 82% in total in this dataset are:
- ***Milk***
- ***Grocery***
- ***Fresh***

### **3. Feature Correlation:**

- **Milk and Grocery:** These two features have a high correlation of 0.69. This suggests that customers who purchase milk are also likely to purchase groceries and vice versa.
- **Grocery and Detergents_Paper:** These features also exhibit a high correlation of 0.74. This indicates that customers buying groceries are also likely to buy detergents and paper products.

### **4.  Conclusion on Clustering:**

Hierarchical clustering is better at explaining the relationships between data points. It provides more insight into how different features and clusters are related, offering a more nuanced understanding of customer purchasing behavior compared to K-means clustering.

