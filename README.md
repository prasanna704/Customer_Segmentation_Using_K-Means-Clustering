# Customer Segmentation Using K-Means Clustering

## Overview

This project involves the preprocessing, visualization, and clustering of customer data from a mall dataset. The primary goal is to enhance customer segmentation and support targeted marketing strategies by identifying key patterns in customer attributes such as Age, Spending Score, and Annual Income.

## Project Description

In this project, I preprocessed and visualized customer data to identify key patterns in Age, Spending Score, and Annual Income. I applied K-means clustering to form four clusters based on Age and Spending Score and five clusters based on Annual Income and Spending Score. Utilizing Python libraries (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn), I enhanced customer segmentation and supported targeted marketing strategies.

## Key Steps

1. **Data Import and Initial Exploration**
   - Imported necessary libraries: Pandas, NumPy, Matplotlib, Seaborn.
   - Loaded the mall customer dataset.
   - Displayed the first few rows to understand the structure of the data.

2. **Data Analysis**
   - Checked the dimensions of the dataset.
   - Performed basic statistical analysis on the columns.
   - Verified the data types of each column.

3. **Data Cleaning**
   - Checked for null values in the dataset.

4. **Data Visualization**
   - Created histograms to visualize the distribution of Age, Annual Income, and Spending Score.
   - Generated a pie chart to display the gender distribution of the customers.

5. **K-Means Clustering**
   - **Clustering by Age and Spending Score:**
     - Selected the columns for Age and Spending Score.
     - Used the Elbow method to determine the optimal number of clusters.
     - Applied K-means clustering to segment customers into four clusters.
   - **Clustering by Annual Income and Spending Score:**
     - Selected the columns for Annual Income and Spending Score.
     - Used the Elbow method to determine the optimal number of clusters.
     - Applied K-means clustering to segment customers into five clusters.

## Libraries Used

- **Pandas:** For data manipulation and analysis.
- **NumPy:** For numerical computations.
- **Matplotlib:** For data visualization.
- **Seaborn:** For statistical data visualization.
- **Scikit-Learn:** For implementing the K-means clustering algorithm.

## Results and Insights

- Identified distinct clusters of customers based on their Age and Spending Score, as well as their Annual Income and Spending Score.
- Provided insights into customer segmentation that can be leveraged for targeted marketing campaigns.

## Usage

To run this project, ensure you have the required libraries installed. You can install them using the following commands:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Load the notebook `KMeans Clustering.ipynb` and `Mall_Customers.csv` to view the full analysis and visualizations.

## Conclusion

This project demonstrates the application of K-means clustering for customer segmentation. By understanding the key patterns in customer data, businesses can develop more effective marketing strategies and improve customer satisfaction.

---

You can view the full project in the [Jupyter Notebook](https://github.com/SreeNihaar/Clustering-the-Customers-using-KMeans/blob/main/KMeans%20Clustering.ipynb).
