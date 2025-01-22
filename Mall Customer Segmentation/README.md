**Project Title : Mall Customer Segmentation**

**Technologies Used:** Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, scipy --- Languages: Python.

**Project Objective:** The aim of this project is to segment customers into distinct groups based on their spending habits and income levels using clustering techniques. This helps to identify target customers for personalized marketing strategies.

**Table of contents**
1. Dataset Loading
2. Data Exploration
3. Data Preprocessing
4. Exploratory Data Analysis (EDA)
5. Modeling-Clustering Techniques
6. Evaluation Metrics
7. Conclusion

**The project follows a structured pipeline as outlined below:**

  **1. Data Loading:** Loaded the dataset and inspect its structure. The dataset contains information on customer Age, Gender, Annual Income (k$), and Spending Score (1-100).

  **2. Data Exploration:** Understand the dataset by checking distributions, missing values, duplicates, datatypes and key statistics.

Data challenges 

- Gender variable consists of categorical data. So, it need to convert into nurmerical data.

**3. Data Preprocessing:** - By using Encoding technique like LabelEncoder() gender variable is converted into numerical data.

**4. Exploratory Data Analysis (EDA):** performed univariant and bivariant analysis.

- **Observations in univariant analysis** 

The annual income plot shows a near normal distribution with most customers are earning income between 40k and 80k, while very few customers are earning below 30K or above 80K. The Age plot shows slightly right skewed with most of the customers are in between 20 and 40 aged, peaked at the age of 30 years, and less customers below 20 years or above 60 years. Spending Score (1-100) is uniformly distributed, indicating a balanced spread across low, medium, and high spenders, without a dominant spending behavior group. These insights suggest that most customers are middle-income earners and younger people, making them the key demographic for targeted marketing, with spending behavior varying widely and suitable for segmentation.

- **Observations in Bivariant analysis**

customers with Low-income (15k–40k) are widely distributed throughout all spending scores, from low to high. Moderate-income customers (40k–80k) are clustered around high spending scores (60–100) while some low spenders are also included. High-income customers (80k–140k) are mostly in moderate spending scores (40–60), with only a few people in the high range. Both genders have similar spending score distributions, with slightly higher median scores for females. The spending scores of both genders may differ significantly. Younger customers(20-30) having higher spending scores, while spending scores decreases as age increases with older customers (Aged 50+) showing lower scores. Annual Income (k$) and Spending Score (1-100) have a very weak positive correlation (0.01), indicating that income has less impact on spending scores. There is nearly no correlation between age and annual income (-0.01). The relationship between spending score and age is moderately negative (-0.33), meaning younger customers usually spend more.

**Insights**

Customers can be segmented based on income and spending score into potential clusters for targeted marketing. Younger customers tend to have higher spending scores, making them a key demographic for marketing strategies. Both genders exhibit similar spending and income patterns, so gender-specific marketing may not be necessary.

**5. Modeling-Clustering Techniques:** 

**K.Means Clustering:**

- Used the Elbow Method to determine the optimal number of clusters (e.g., 5).
- Formed clusters based on normalized Annual Income and Spending Score.
- Visualized clusters and their centroids.

  **Observations for Clusters of Customers with Centroids**

High-income, high-spending customers (top-right cluster) – These customers have high income and high spending scores, perhaps indicating premium customers. Low-income, low-spending customers (bottom-left cluster) – These customers have low income and low spending scores, possibly indicating budget-conscious customers. High-income, low-spending customers (bottom-right cluster) – These customers have high income but do not spend much, possibly indicating conservative spenders. Low-income, high-spending customers (top-left cluster) – These customers have low income but high spending, which might indicate impulsive or dependant on credit shoppers. Middle-income, moderate-spending customers (center cluster) – These customers have average income and spending scores.

**Hierarchical Clustering:**
- Distance Metric: Used the 'complete' linkage method to compute clusters.
- Dendrogram: Visualize the hierarchical relationships between data points.
- Formed Clusters: To Choose the number of clusters from the dendrogram and assign cluster labels.

**6. Evaluation**
  
- Silhouette Score measured the quality of clusters.
- Analyzed cluster centroids and size distributions to interpret customer groups.

**7. Conclusion:** 

The project successfully segmented customers into actionable groups, enabling targeted business strategies to improve customer satisfaction and profitability.

