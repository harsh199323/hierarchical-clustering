# hierarchical-clustering

conducted a comprehensive analysis of a dataset containing information about various countries. This analysis is crucial for making informed decisions and identifying countries that may require special attention or assistance.

Firstly, we imported and organized the data. The dataset covers essential metrics for each country, such as child mortality, exports, health, imports, income, inflation, life expectancy, total fertility, and GDP per capita.

We ensured that the data was complete with no missing values, a crucial step in data preparation. Next, we visualized the distribution of data for each metric using histograms, giving us a better understanding of the data's characteristics.

To uncover relationships between these metrics, we created a pairplot, which allowed us to observe how they correlate with one another. This visual analysis can provide valuable insights into potential patterns within the data.

Identifying outliers is also essential, as these countries may require special attention due to extreme values in certain metrics. For instance, we found that Haiti has an unusually low life expectancy, while Nigeria has an exceptionally high inflation rate.

To reduce the complexity of the data and facilitate further analysis, we performed Principal Component Analysis (PCA). This technique allowed us to reduce the dimensionality of the dataset while preserving its essential information. We retained six principal components that explain a significant portion of the data's variance.

Subsequently, we applied hierarchical clustering using three different methods: ward, average, and complete linkage. This allowed us to group countries with similar characteristics together. We visualized the results on a scatter plot, with each cluster represented by a different color.

To evaluate the quality of these clusters, we calculated the Calinski-Harabasz score, which measures the separation between clusters. The higher the score, the better the separation. Based on this metric, the complete linkage method produced the best clusters, followed by the average linkage method.

Additionally, we calculated the silhouette score for the complete linkage clustering, which measures how well each data point belongs to its assigned cluster. A higher silhouette score indicates that the clusters are well-defined and distinct. In this case, the silhouette score is 0.4081, suggesting that the clusters are reasonably well-separated.

In conclusion, our exploratory data analysis and clustering techniques have provided valuable insights into the dataset, allowing us to identify countries with similar characteristics and potential outliers. These findings can inform future decision-making processes and targeted interventions to address specific country needs.
