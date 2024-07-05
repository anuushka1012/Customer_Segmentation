# Customer_Segmentation
aimed to enhance customer understanding through segmentation and targeting by analyzing transactional data from an e-commerce dataset. 

Data Collection and Preprocessing Dataset: Online retail data containing transactional information such as InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, and Country.

Preprocessing: Handled missing values by removing rows without CustomerID and transactions with non-positive quantities or unit prices. Converted InvoiceDate to datetime format and calculated TotalSpend for each transaction.

Feature Engineering Frequency: Number of transactions per customer. Recency: Number of days since the last transaction. Average Spend: Average spend per transaction. Total Spend: Total spend across all transactions.

Clustering and Analysis Algorithm: Applied K-Means clustering to segment customers. Optimal Clusters: Determined the optimal number of clusters using the Elbow Method and Silhouette Scores, identifying three distinct customer segments. Visualization: Created pair plots and box plots to visualize the distribution and relationships of features within each cluster.

Insights and Interpretation Cluster 0: High-frequency buyers with moderate spending. Cluster 1: Infrequent buyers with high average spending. Cluster 2: Recent buyers with moderate frequency and spending.

Conclusion This project provided valuable insights into customer behavior, enabling more personalized marketing strategies. The analysis revealed clear customer segments, each with distinct characteristics and purchasing patterns, facilitating targeted engagement and improved customer retention.
