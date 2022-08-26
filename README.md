# Making Items More Visible Increases Sales  
## Performed data visualizations and machine learning to analyze sales of various outlets 
#### Anthony Gravink
### Business Problem
Help the retailer understand understand the properties of products and outlets that play crucial roles in increasing sales
## Data
https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/  
8523 observations
## Methods
- Dropped item identifier and outlet identifier columns in final analysis because each value in those columns was unique, ultimately adding nothing relevant to the analysis  
- Imputed values based on frequency for categorical columns because the most frequent value would skew the data less  
- Imputed values based on mean for numerical columns because there were no large outliers effecting the data  
## Results
- The most important metrics are item visibility, item type, and item MRP  
- Foods with a higher MRP were often given more visibility and contributed significantly to sales  
- Certain foods has a low item count within their type, but were given significsnt visibility contributing to overall sales  
## Limitations/Recommendations  
- Overall very little significant info was given on the grocery store/supermarket itself  
- The vast majority of outlets were of the same size and type providing little findings other than a bigger store will produce more sales overall  
- Perhaps creating more characteristics to identify outlets could help improve that aspect of the analysis
