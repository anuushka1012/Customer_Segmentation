# Customer_Segmentation
aimed to enhance customer understanding through segmentation and targeting by analyzing transactional data from an e-commerce dataset. 

Data Collection and Preprocessing Dataset: Online retail data containing transactional information such as InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, and Country.

Preprocessing: Handled missing values by removing rows without CustomerID and transactions with non-positive quantities or unit prices. Converted InvoiceDate to datetime format and calculated TotalSpend for each transaction.

Feature Engineering Frequency: Number of transactions per customer. Recency: Number of days since the last transaction. Average Spend: Average spend per transaction. Total Spend: Total spend across all transactions.

Clustering and Analysis Algorithm: Applied K-Means clustering to segment customers. Optimal Clusters: Determined the optimal number of clusters using the Elbow Method and Silhouette Scores, identifying three distinct customer segments. Visualization: Created pair plots and box plots to visualize the distribution and relationships of features within each cluster.

Insights and Interpretation Cluster 0: High-frequency buyers with moderate spending. Cluster 1: Infrequent buyers with high average spending. Cluster 2: Recent buyers with moderate frequency and spending.

Segment Analysis and Strategies

Cluster 0: High-Frequency Buyers with Moderate Spending

Strategies:
1. Loyalty Programs: Implement loyalty rewards and points systems to encourage continued frequent purchases.
2. Personalized Offers: Send personalized discounts and promotions to encourage higher spending per transaction.
3.Early Access: Provide early access to new products and exclusive sales events to reward their loyalty.

 Cluster 1: Infrequent Buyers with High Average Spending

Strategies:
1. Exclusive Offers: Offer exclusive discounts and special deals on high-end products to entice more frequent purchases.
2. Subscription Services: Introduce subscription-based services for premium products or services.

Cluster 2: Recent Buyers with Moderate Frequency and Spending

strategies:
1. Welcome Campaigns: Implement welcome email campaigns with introductory offers and discounts to encourage repeat purchases.
2. Incentivize Repeat Purchases: Use coupons and limited-time offers to motivate another purchase soon after their initial one.




Conclusion This project provided valuable insights into customer behavior, enabling more personalized marketing strategies. The analysis revealed clear customer segments, each with distinct characteristics and purchasing patterns, facilitating targeted engagement and improved customer retention.
