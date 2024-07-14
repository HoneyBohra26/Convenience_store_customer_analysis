In this machine learning project, I employ a variety of techniques to analyze customer data, focusing on segmentation, purchase analytics, and predictive modeling.

Customer Segmentation
In Segmentation.ipynb, I perform a comprehensive analysis using correlation estimates and data standardization. I apply segmentation methods such as hierarchical clustering, k-means clustering, and Principal Component Analysis (PCA). The process involves extensive visualizations including heatmaps, clusters, dendrograms, and scatter plots to segment and understand customer behavior. The dataset used for this analysis is segmentation data.csv.

Purchase Analytics Descriptive Analysis
In Purchase Analytics Descriptive Analysis.ipynb, I leverage the segmentation model to divide customers into segments and extract insights about their shopping habits. This notebook involves thorough exploratory data analysis (EDA), addressing questions like shopping frequency, spending patterns, and product purchase frequency relative to store visits. I create dummy variables for essential features and analyze preferences, such as which brands are favored by different segments and the reasons behind their choices. The analysis also includes an examination of revenue across various segments. The data for this analysis is contained in purchase data.csv.I have conducted a detailed analysis to answer several key questions related to customer shopping behavior. These questions include:

1. Shopping Frequency: How often do customers go shopping?
2. Spending Patterns: How much money do customers spend during their visits?
3. Product Purchase Frequency: How often do customers buy a particular product relative to their store visits?

Purchase Analytics Predictive Analysis
In Purchase Analytics Predictive Analysis.ipynb, I delve into the calculation of price elasticity for purchase probability and quantity. This analysis includes evaluating purchase probabilities by segments, with and without promotions, as well as determining own and cross-price elasticities by segment. The analysis helps in understanding brand choices made by different customer segments.

Price elasticity:
1% change in output variable in response to a 1% change in input variable.If value of 'Price elasticity' in absolute terms is less than 1 than it is 'inelastic'. Because, 1% change in price causes less than 1% change in purchase probability. Hence, increase in price will not cause significant decrease in purchase probability.For inelasticity we can increase price, for elasticity we need to decrease price to increase purchase.I have conducted a detailed analysis to answer several key questions related to customer shopping behavior with change in price. These questions include:
