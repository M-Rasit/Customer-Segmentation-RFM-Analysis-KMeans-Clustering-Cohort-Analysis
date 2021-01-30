Hello :wave:,

In this repository determines are sing the Online Retail dataset from the UCI Machine Learning Repository for exploratory data analysis, Customer Segmentation, RFM Analysis, K-Means Clustering and Cohort Analysis.

:pen: Dataset:

![DataFrame](https://github.com/M-Rasit/Customer-Segmentation-RFM-Analysis-KMeans-Clustering-Cohort-Analysis/blob/main/images/df.png?raw=true)

:pen: After Exploratory Data Analysis and Data Cleaning I discovered that most of the customers are from UK and limiting customers with them can give better results. Therefore, in this dataset I focused on customers from UK. 

![UK](https://github.com/M-Rasit/Customer-Segmentation-RFM-Analysis-KMeans-Clustering-Cohort-Analysis/blob/main/images/total_customer.png?raw=true)

:pen: I focused on Recency, Frequency, Monetary for RFM Analysis. I divided dataset into 5 labels.

![RFM](https://github.com/M-Rasit/Customer-Segmentation-RFM-Analysis-KMeans-Clustering-Cohort-Analysis/blob/main/images/rfm_level.png?raw=true)

:pen: For KMeans clustering I tried three scaling method.(StandardScaler, MinMaxScaler, Log Normalization). I specified cluster number using Yellowbick library and I corrected cluster numbers with Silhouette scores. Then using boxplots give label for every cluster.

![3D](https://github.com/M-Rasit/Customer-Segmentation-RFM-Analysis-KMeans-Clustering-Cohort-Analysis/blob/main/images/KMeans_clustering.png?raw=true)

![Kmeans](https://github.com/M-Rasit/Customer-Segmentation-RFM-Analysis-KMeans-Clustering-Cohort-Analysis/blob/main/images/cluster_labels.png?raw=true)

:pen: Then I compared results and found the differences.

![Compare](https://github.com/M-Rasit/Customer-Segmentation-RFM-Analysis-KMeans-Clustering-Cohort-Analysis/blob/main/images/compare.png?raw=true)

:pen: I applied Cohort Analysis for Retention Rate, Cost and Quantity. 

![Cohort Analysis](https://github.com/M-Rasit/Customer-Segmentation-RFM-Analysis-KMeans-Clustering-Cohort-Analysis/blob/main/images/Retention_rate&Cohort_index.png?raw=true)

Thank you:tulip:
