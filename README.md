# **Supermarket Customer Analysis**
## **Introduction**
A company operating in the retail sector aims to enhance its promotional strategies for its customers. The company has conducted a campaign targeting all members and has collected data on customers who have either received the campaign or not. With this data in hand, the company has engaged the Data Analyst team to further analyze the conducted campaign. The insights derived from this analysis will serve as valuable input for shaping future campaigns.

## **Problem Statement**
The primary goal of this analysis is to identify which customer segments are more likely to accept the campaign and which segments are not. This segmentation will enable the company to maximize its benefits and craft strategies that enhance the effectiveness of future campaigns.

To address this objective, the Data Analyst team will focus on answering the following key questions:

1. **Campaign Effectiveness**: Can the campaign be considered effective? The effectiveness of the campaign is assessed based on the total amount spent by customers. This assumption is made due to the lack of data on campaign costs and the revenue generated from each campaign.

2. **Impact of Customer Demographics**: How do customer demographics influence campaign acceptance? This question aims to uncover the segmentation of customers based on various demographic factors.

3. **Popular Products**: What products are most frequently purchased by customers in each segment?

4. **Purchase Channels**: Through which channels do customers make their purchases?

## **Data Analysis Approach**
The analysis will involve the following steps:

1. **Data Preparation**: Load and preprocess the dataset, ensuring all relevant columns are available and properly formatted. This includes calculating new columns such as customer age and grouping customers into age categories.

2. **Campaign Acceptance Analysis**: Analyze the campaign acceptance by different customer segments (e.g., age groups, marital status, child status, education level, and spending category).

3. **Product Purchase Analysis**: Identify the total amount spent on various product categories by different customer segments.

4. **Purchase Channels Analysis**: Determine the total number of purchases made through different channels (e.g., deals, web, catalog, store).

## **Methodology**
1. **Data Preparation**
Load the dataset from the provided CSV file.

Calculate new columns such as customer_age and categorize customers into age groups: 'young adults', 'mid adults', and 'old adults'.

Ensure the dataset includes columns for marital status, child status, education level, and spending category.

2. **Campaign Acceptance Analysis**
Determine which customer segments are more likely to accept the campaign or not based on various demographic factors.

Visualize the data using bar graphs and heatmaps to show the distribution of campaign acceptance among different segments.

3. **Product Purchase Analysis**
Calculate the total amount spent on different product categories such as 'MntWines', 'MntFruits', 'MntMeatProducts', 'MntFishProducts', 'MntSweetProducts', and 'MntGoldProds'.

Filter the data based on specific customer segments and visualize the total amount spent on each product category.

4. **Purchase Channels Analysis**
Calculate the total number of purchases made through different channels: 'NumDealsPurchases', 'NumWebPurchases', 'NumCatalogPurchases', and 'NumStorePurchases'.

Visualize the total number of purchases through each channel using bar graphs.
