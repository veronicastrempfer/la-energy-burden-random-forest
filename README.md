# la-energy-burden-random-forest
## Research Question: 
Does the inclusion of environmental features (ie. greenspace and water body presence) improve the classification of energy burden levels of residents’ across different LA County cities? 

* Energy burden refers to the percentage of household income spent on energy costs. A “low” energy burden is defined as spending less than 6% of income on energy, “high” as 6–10%, and “severe” as over 10%.
 
## Data
For this project a combination of city related data including city names, FIPs, and zip codes were used to identify specific cities in LA. Environmental features were captured using lake presence in different cities of California. Tree data was used to capture the number of trees per city. For greenspace park access was recorded by looking at the number of parks in that city as well as the average acreage of these parks.

## Methods
Used R studio for whole process. Went through data processing of removing NA values as well as maintaining consistency across variables such as capitalization across different city names. For presence of lakes converted variable to binary formatting. Applied random forest, using decision trees we aim to improve the classification of household energy burden. 
3 hyperparameters 
  - Number of trees = 500 
  - Number of features randomly sampled as candidates at each split was = 2 & 3 
  - Node size was varied between  = 10 & 25 (default 1)
## Results
- Environmental features (tree, parks, water, acreage matter BUT not strong predictors on their own)
- Energy burden may depend on factors beyond those included in this analysis, such as building characteristics and other demographics
- Environmental effects (shade, temperature) help but are still limited
- Must go beyond environmental changes to address financial disparities
## Limitations 
- Water features had limited representation, which may have reduced the model’s ability to capture their impact on energy consumption
- Some environmental data may have been inaccurate or underestimated, such as tree counts, which could affect model reliability and results

