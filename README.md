# Analysis on 2011 US Agricultural Export by States

## Introduction:
The data visualization covers U.S. agricultural exports by state in 2011, including detailed statistics for various categories like poultry, vegetables, fruits, cotton, wheat, corn, and meat products. Below are insights, forecasts, and actionable recommendations based on the cleaned dataset:

## Problem Statement:
The United States' agricultural export industry exhibits significant variability across states and product categories, with a few states dominating production in certain areas like poultry, fruits, and vegetables. This uneven distribution raises critical questions about the efficiency and inclusivity of agricultural practices nationwide. To foster growth and equitable contributions, there is a need to analyze state-wise export data to:

- Identify key contributors and lagging states.

- Understand trends across categories (e.g., raw vs. processed products).

- Evaluate factors driving export disparities.

- Provide actionable insights for enhancing export capabilities, particularly in underperforming regions.

The goal of this analysis is to enable data-driven decision-making to optimize resource allocation, promote diversification, and sustain U.S. leadership in global agricultural exports.

## Skills and concept demonstrated:
* data cleaning using microsoft excel by removing duplicates,blanks by filtering and putting columns in the proper data types.
* Cleaned data was then transformed into power query for column quality check then performed EDA such as descriptive statistical analysis in Microsoft excel.
* Transformed dataset are summarized into pivot tables for further analysis using data Visualization such as charts and graphs,KPIs in Ms excel.
* Data modelling using Python library such as panda for data manipulation, matplotlib for creating scatter plots.
* PowerPoint slides was used to put together all the data visualization using AI tool.

## Data Interpretation and Insights:
## KPIs:
### Total Exports: 1
### Product Categories: 5
### Total Veggies: 1600
### Total Fruits: 6007
### Total States: 5
### Sum of cottons: 483
### Sum of corns: 2521
### Sum of fresh veggies: 8829
### Sum of processed veggies: 961
### Sum of dairies: 1269
### Sum of porks: 388
### Sum of poultries: 69
### Sum of beefs: 22926
### Sum of fresh fruits: 1043
### Sum of processed fruits: 2821


## Data Analysis:  
1. ### Top Performing States:
States like Arkansas (poultry) and California (fruits and vegetables) dominate due to their favorable climate, resources, or established infrastructure.

2. ### Average Exports:
The average export values for categories like poultry (13.82 units) and dairy indicate a strong but skewed production, with some states producing disproportionately higher quantities.

3. ### Disparities:
The standard deviation in poultry exports (10.79 units) highlights significant variability, suggesting that some states are highly specialized while others barely contribute.

4. ### Median vs. Mean:
For categories like poultry, the median (11.1) is lower than the mean, indicating that a few states with high outputs (e.g., Arkansas) skew the average.

5. ### Poultry Exports:
Arkansas leads in poultry production with 29.4 units, while Alaska contributes the least non-zero value (0.1 units).
The median value (11.1) suggests a skewed distribution, with several states producing significantly above average.

6. ### Processed Vegetables and Fruits:
High variation in exports by state indicates regional specialization. States with significant processed goods may have stronger food processing industries.

7. ### Crop Exports:
Cotton, wheat, and corn exhibit significant differences across states, which likely relate to geographical and climatic suitability.

8. ### Meat and Dairy:
The variations in beef, pork, and dairy production may hint at differing state policies, consumer preferences, or export infrastructure.

9. ### Total Exports:
Aggregating these categories highlights disparities among states in their contributions to agricultural exports.

## The visualizations generated for this data analysis are used to generate more insights for the dataset.
## The visuals are attached as PowerPoint slides along side this report.

![here](2011_US_Agricultural_Exports_b_20241206_002340.pptx)

## Correlation pattern between Products:
Dataset was modelled  to check for the relationships pattern between food categories (like beef, pork, poultry, and dairy) themselves.  

### scatter plots of the categories against one another to observe patterns and relationships. I generated visualizations for each pair of food categories:

. [Beef vs Pork](./beef_vs_pork.html)

 [Beef vs Poultry](./beef_vs_poultry.html)
 
  [Beef vs Dairy](./beef_vs_dairy.html)
  
   [Pork vs Poultry](./pork_vs_poultry.html)
   
  [Pork vs Dairy](./pork_vs_dairy.html)
    
  [Poultry vs Dairy](./poultry_vs_dairy.html)

## Forecasting:
1. ### Market Leaders:
States already excelling in particular categories (e.g., Arkansas in poultry) will likely continue their dominance if current trends persist.
Investment in infrastructure and technology can amplify output in underperforming states.

2. ### Growth Potential:
With demand for processed foods rising globally, states focusing on processed fruits and vegetables may see higher growth.
Climate and sustainability trends may impact wheat and cotton yields in sensitive regions.

## Actionable recommendations:
1. ### Diversification:
States with lower overall exports should explore diversifying into high-demand categories such as poultry or processed foods.
Promote research and development in adaptive crops for less productive regions.

2. ### Value Addition:
Emphasize increasing the share of processed products (vegetables and fruits) in states that produce mainly raw goods.

3. ### Infrastructure Investment:
Improve storage and transportation for perishable goods like dairy and fresh fruits to reduce losses and expand market reach.

4. ### Marketing Support:
Offer subsidies or export incentives to low-performing states to encourage agricultural growth and participation in international trade.






