# Overview
This project aims to analyze customer data and segment them into distinct groups based on their shopping behavior and preferences. By leveraging demographic information such as age, gender, and location, clustering techniques like K-means are employed to identify meaningful customer segments. The analysis provides insights that can inform targeted marketing strategies and personalized recommendations.

# Introduction 
In today's competitive market, understanding customer behavior is crucial for businesses to tailor their strategies effectively. Customer segmentation allows businesses to group customers with similar characteristics and preferences, enabling personalized marketing efforts and enhanced customer satisfaction.

# Data Description 
The dataset used for this analysis contains demographic information, purchase history, and other relevant variables. Here's a brief overview of the dataset:

Customer ID: Unique identifier for each customer.
Age: Age of the customer.
Gender: Gender identification of the customer.
Item Purchased: Specific product or item selected by the customer.
Purchase Amount (USD): Monetary value of the transaction.
Location: Geographical location of the purchase.
Size, Color, Season: Product specifications.
Review Rating: Customer satisfaction rating.
Previous Purchases: Number of prior purchases made by the customer.
Payment Method: Mode of payment.
Frequency of Purchases: How often the customer engages in purchasing activities.

# Methodology
1. Data Preprocessing: Clean and preprocess the dataset and handle missing values.
2. Exploratory Data Analysis (EDA): Explore the dataset to understand the distribution of variables and identify any patterns.
3. Clustering (K-means): Apply K-means clustering algorithm to segment customers into distinct groups based on their features.
4. Interpretation: Analyze the characteristics of each cluster and assign meaningful labels to them.

# Clustering Analysis Results
### Cluster Characteristics

| Cluster | Age (Mean) | Purchase Amount (Mean) | Review Rating (Mean) | Previous Purchases (Mean) |
|---------|------------|------------------------|----------------------|---------------------------|
| 0       | 53.51      | 37.37                  | 4.3                  | 25.57                     |
| 1       | 28.22      | 60.78                  | 4.4                  | 24.99                     |
| 2       | 54.14      | 81.88                  | 4.4                  | 25.57                     |


<img width="509" alt="Screen Shot 2024-03-05 at 10 51 08 PM" src="https://github.com/rimchristian/Customer-Segmentation-Analysis/assets/74616874/7766170e-8891-465b-94b3-e2185b453711">

<img width="863" alt="Screen Shot 2024-03-05 at 10 52 03 PM" src="https://github.com/rimchristian/Customer-Segmentation-Analysis/assets/74616874/1fbdad75-601a-4952-a425-736d1b4cdb7e">


# Conclusion 
The clustering analysis revealed distinct customer segments with varying demographics and shopping behavior. Businesses can use these insights to tailor marketing strategies and recommendations for each segment, ultimately enhancing customer satisfaction and loyalty.












