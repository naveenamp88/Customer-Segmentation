# Customer-Segmentation_Palanichamy Naveen
Customer Segmentation using K-Means Clustering

This project uses K-Means clustering to segment customers into different groups based on their purchasing behavior. The goal is to help businesses tailor their marketing strategies to different customer segments.

## Dataset

We use a synthetic dataset that includes the following columns:
- **CustomerID**: Unique identifier for each customer
- **Age**: Age of the customer
- **Annual Income (k$)**: Annual income of the customer in thousands of dollars
- **Spending Score (1-100)**: Score assigned by the mall based on customer behavior and spending nature

## Steps

1. **Generating the Dataset**: We generate a synthetic dataset of customer transactions.
2. **Preprocessing the Data**: We scale the features for clustering using `StandardScaler`.
3. **Applying K-Means Clustering**: We determine the optimal number of clusters using the Elbow method and apply K-Means clustering.
4. **Visualizing the Clusters**: We visualize the customer segments using a 3D scatter plot.

## Installation

To run this project, you need Python installed along with the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install these libraries using pip:

```sh
pip install pandas numpy matplotlib seaborn scikit-learn
