**USING CLUSTERING FOR CUSTOMER SEGMENTATION & MARKETING STRATEGY**

**1. THE CHALLENGE**

The client, a smartwatch manufacturer, faced difficulties in effectively segmenting their market to target diverse customer needs and preferences. The primary challenge was identifying distinct customer segments to tailor marketing strategies and create more engaging and relevant content for each group.


**2. THE STRATEGY**

To address this challenge, I decided to use hierarchical clustering to segment the market based on customer data. Understanding these segments would enable us to craft targeted marketing strategies, positioning the smartwatch features to resonate with each segment's specific needs and preferences.



**3. THE PROCESS**

**Data Preparation & Preprocessing**

Basic descriptive statistics and the mode of the dataset were computed to understand the data distribution.
Standardization: The data was standardized using StandardScaler to ensure all variables contribute equally to the clustering process.

**Hierarchical Clustering**

- Euclidean distance matrix was calculated.
- Hierarchical clustering was performed using Ward's method.
- A dendrogram was plotted to visualize the clustering process and determine the optimal threshold for cluster separation.
  
**PCA & Visualization**

- PCA was performed to reduce the dimensionality of the data for visualization purposes.
- A scatter plot of the PCA results was created, with points colored according to their cluster labels.

**Cluster Analysis**

- Cluster labels were added to the original dataframe.
- The size of each cluster was computed as a percentage of the total dataset.
- Mean values of each variable for each cluster were calculated and combined with cluster size information.
  
**Statistical Analysis**

- Chi-square tests were performed to determine the statistical significance of the associations between clusters and categorical variables.
- ANOVA was performed to compare the means of each variable across different clusters.
  


**4. KEY FINDINGS & INSIGHTS**

The analysis revealed 03 distinct clusters with varying behaviors and preferences. The Chi-square and ANOVA tests indicated significant associations between clusters. 
The mean values of each variables and size for each cluster are presented as belows: 

![image](https://github.com/mainguyenwrk/Customer-segmentation-using-Cluster/assets/175161045/26793bc5-fce2-483a-9936-8cb918bf723d)


Based from that, the three clusters are interpreted as three distinctive customer segments as belows: 

**Cluster 1: Elevated Achievers**
This segment values health, fitness, and style. Marketing efforts should highlight the smartwatch’s multifunctional capabilities, stylish design, and premium features

![image](https://github.com/mainguyenwrk/Customer-segmentation-using-Cluster/assets/175161045/7a519a27-8b21-4ed9-b4d0-0d2ebbc593d1)



**Cluster 2: Life Balancers**

Price sensitivity is their key trait. Marketing should focus on affordability and the essential functionalities of the smartwatch, emphasizing value for money.

![image](https://github.com/mainguyenwrk/Customer-segmentation-using-Cluster/assets/175161045/fbc3d01a-2982-4212-9807-560d66f52c3f)


**Cluster 3: Productivity Pros**
This customer group seeks efficiency and practicality. Marketing strategy should stress productivity features like task management,communication tools, and device stability.

![image](https://github.com/mainguyenwrk/Customer-segmentation-using-Cluster/assets/175161045/34dca02d-b21a-4438-904e-f90b741912e9)


Based on the size of the segments as well as the alignments between the segments and the company's internal resources and strategy (derived from 3C analysis and GE matrix), it is recommendated that Cluster 3 - Productivity Pros should be targeted. Accordingly, the positioning that emphasizing robust performance in productivity-related functions is proposed. 


**5. LEARNINGS & WISHES**
- Using Additional Methods to Define the Number of Clusters: Exploring methods such as the Elbow Method or the Silhouette Score could provide more robust and accurate determination of the optimal number of clusters.
- Applying Other Clustering Methods: Experimenting with alternative clustering techniques like K-means or DBSCAN could offer different insights and potentially more meaningful segmentation, enhancing the precision of targeted marketing strategies.

