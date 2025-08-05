# Marketing-Campaign-Analysis
## Campaign Analysis using Microsoft Excel

![Dashboard](https://github.com/EEmilyA/Marketing-Campaign-Analysis/blob/main/Campaign%20Dashboard.png)

### Overview
This report aims to provide a comprehensive analysis of the marketing Campaign dataset of a store, I will be analyzing customer responses to 5 different marketing campaigns (campaign 1- 5) with a focus on Campaign 1 (Targeted response).The responses aim to provide a significant boost to the efficiency of a marketing campaign by increasing responses or reducing expenses.

### Data Source
The primary source use for this analyis was gotten from Kaggle an open source which contains information on consumer behaviour and demograph for the period being analysed.

### Objectives
To track key Key Performance Indicators (KPIs)for each campaign (especially Campaign 1). The primary goal is to understand customer behavior and identify factors that influence their response to marketing campaigns. This includes:
1. Segmenting customers based on demographics and purchasing behavior.
2. Identifying key drivers of campaign success (e.g., income, education, spending habits).
3. Providing actionable insights to optimize future marketing strategies.

### Tools Used
- Microsoft Excel- Data cleaning and preparation, Power Query Editor for feature engineering,  Pivot Tables for visualization.

### Data cleaning and preparation.
#### Data Cleaning:

1. Handle missing values (e.g., impute missing Income).
2. Check for duplicates or inconsistencies.
3. Removed all conditional formatting from the dataset.
4. Additional calculated columns for Age, Age range, Total number of household children, Classification of Income base on earnings.
5. Deleted blank cells on Income column, which constituted a small portion of the dataset (2%) of the data without disrupting the integrity of the data
6. Unpivot Campaign columns with multiple rows into single column, to enable proper analysis and side by side comparison 

#### Exploratory Data Analysis (EDA):

1. Visualize distributions of key variables.
2. Analyze correlations between variables (e.g., spending vs. income).
3. Understand the characteristics of customers who responded positively to campaigns (Response = 1)
4. Analyse which features are most predictive of campaign response (Response).


### Results, Findings and Conclusion.
The Marketing Campaign Analysis provides a comprehensive view of the campaign performance, customer engagement, and demographic insights. It highlights a total of 661 campaign responses with an overall acceptance rate of 5.97%. Among all campaigns, Campaign 4 stands out with the highest response rate of 24.81%, while Campaign 2 significantly underperforms at 4.54%. Despite similar participation rates across campaigns, response effectiveness varies, indicating differences in message impact or audience alignment.

In conclusion, This analysis highlights key trends in campaign performance and customer engagement, revealing clear opportunities to optimize targeting and messaging. While certain segments and campaigns performed strongly, others require strategic refinement. For a detailed breakdown of insights, metrics, and recommendations, please refer to the full documentation [here](https://medium.com/@eventus31/marketing-campaign-analysis-4a8100b83da0)




