# **Customer Segmentation using K-means Clustering**
## Overview
This project applies K-means clustering, an unsupervised learning technique, to segment customers based on their transactional behaviors represented by Recency, Frequency, and Monetary value (RFM). The goal was to identify distinct groups of customers without predefined labels, allowing us to uncover meaningful patterns and insights from the data. This unsupervised approach enables organizations to categorize customers into clusters based on similarities in their purchasing habits, aiding in targeted marketing strategies and personalized customer engagement efforts.

## Project Structure
- **Setup and Load Data**: Initial setup and data loading from a CSV file containing bank transaction data.
- **Preprocess Data**: Data cleaning and preprocessing steps including handling missing values and converting dates to datetime format.
- **RFM Analysis**: Compute RFM (Recency, Frequency, Monetary) metrics for each customer.
- **K-means Clustering**: Apply K-means clustering to segment customers into distinct groups based on RFM metrics.
- **Visualize Clusters**: Visualize customer segments using various plots to understand their distribution in the RFM space.
- **Required Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn
 
## Installation
Clone the repository and install dependencies:
```python
git clone https://github.com/your_username/customer-segmentation.git
cd customer-segmentation
```

## Usage
1. Ensure your data is formatted similarly to `bank_transactions.csv`.
2. Run the Jupyter notebook `customer_segmentation.ipynb` to execute the analysis steps.
3. Explore the results and visualizations in the notebook to understand customer segments.
 
## Results
The project identifies distinct customer segments based on RFM metrics:

- **Cluster 0**: Low Frequency, Low Monetary Value, Recently Active
- **Cluster 1**: Low Frequency, Low Monetary Value, Less Recently Active
- **Cluster 2**: Moderate Frequency, High Monetary Value
- **Cluster 3**: High Frequency, Moderate Monetary Value

## Conclusion
In this project, K-means clustering was utilized to segment customers based on RFM (Recency, Frequency, Monetary) metrics derived from bank transaction data. The analysis identified four distinct customer segments with varying transaction behaviors and monetary values. These segments provide actionable insights for targeted marketing strategies, operational efficiency improvements, and proactive customer retention efforts. Moving forward, refining the clustering model, incorporating additional customer attributes, and deploying it in real-time environments will further enhance its utility in optimizing business strategies and improving customer engagement.


For any questions or further assistance, please feel free to contact me.

Dhananjaya Mudunkotuwa  
dhananjayamudunkotuwa1998@gmail.com
