# Customer Segmentation Project

## Overview
This project aims to segment customers based on their annual income, spending score and age using clustering technique. The segmentation helps in identifying different customer groups to enable targeted marketing strategies and improve business decision-making. The dataset used for this project was obtained from Kaggle.

## Tools and Libraries Used
- **Python**
- **Seaborn**
- **Matplotlib**
- **Plotly**

## Dataset
The dataset used for this project is sourced from Kaggle. You can find it [here](<https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python>).The dataset used in this project is sourced from Kaggle. It contains the following key attributes:
- **CustomerID**: Unique identifier for each customer.
- **Gender**: Gender of the customer.
- **Age**: Age of the customer.
- **Annual Income (k$)**: Annual income of the customer in thousands of dollars.
- **Spending Score (1-100)**: A score assigned by the mall based on customer spending behavior and loyalty.

## Project Workflow
1. **Data Preprocessing**:
   - Load the dataset and check for missing or duplicate values.
   - Perform exploratory data analysis (EDA) to understand the features and their relationships.

2. **Data Visualization**:
   - Use Seaborn and Matplotlib to visualize relationships between features.
   - Generate interactive plots using Plotly for in-depth analysis.

3. **Clustering**:
   - Apply the K-Means clustering algorithm to segment customers.
   - Determine the optimal number of clusters using the Elbow method.
   - Visualize the resulting clusters based on annual income and spending score.

4. **Insights and Conclusion**:
   - Analyze each cluster to understand customer behavior and characteristics.
   - Provide actionable insights for targeted marketing strategies.

## Key Results
The clustering process identified distinct groups of customers:
1. High-income and high-spending customers.
2. Low-income and high-spending customers.
3. Moderate-income and average-spending customers.
4. High-income and low-spending customers.
5. Low-income and low-spending customers.

These insights can help businesses tailor their marketing campaigns to suit the specific needs and behaviors of each customer group.


