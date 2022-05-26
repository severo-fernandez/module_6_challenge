# Single Family homes as investment vehicles - Case Study San Francisco, California.

This study utilizes Housing statistics trend for the City. It also relies on US Census Data as well as neighborhood coordinats to map the data.

### Import the required libraries and dependencies
```import pandas as pd```

```import hvplot.pandas```

```from pathlib import Path```

### Calculate and Plot the Housing Units per Year

For this part of the assignment, use numerical and visual aggregation to calculate the number of housing units per year, and then visualize the results as a bar chart. To do so, complete the following steps:

**Question:** What is the overall trend in housing_units over the period being analyzed?

**Answer:** In this 7 year time period the trend has been modest growth to housing inventory. 2010 = 372,560. 2016 = 382,242 units.

### Calculate and Plot the Average Sale Prices per Square Foot

For this part of the assignment, use numerical and visual aggregation to calculate the average prices per square foot, and then visualize the results as a bar chart. To do so, complete the following steps:

**Question:** Did any year experience a drop in the average sale price per square foot compared to the previous year?

**Answer:** There was a drop from 2010 (369.344) to 2011 (341.903). 
    * If so, did the gross rent increase or decrease during that year?
    
**Question:** If so, did the gross rent increase or decrease during that year?

**Answer:** Gross rent increased substantially during this time period. 

### Compare the Average Sale Prices by Neighborhood

For this part of the assignment, use interactive visualizations and widgets to explore the average sale price per square foot by neighborhood. To do so, complete the following steps:

**Question:** For the Anza Vista neighborhood, is the average sale price per square foot for 2016 more or less than the price that’s listed for 2012? 

**Answer:** The average sale price per square foot in 2012 was **344** dollars. The average sale price in 2016 per square foot was **88** dollars. It dropped over that time period in this neighborhood.

## Build an Interactive Neighborhood Map

For this part of the assignment, explore the geospatial relationships in the data by using interactive visualizations with hvPlot and GeoViews. To build your map, use the `sfo_data_df` DataFrame (created during the initial import), which includes the neighborhood location data with the average prices. To do all this, complete the following steps:

**Question:** Which neighborhood has the highest gross rent, and which has the highest sale price per square foot?

**Answer:** Westwood Park has the highest gross rent at **3959**. Union Square district has the highest sale price psf at **904**.

**Question:**  How does the trend in rental income growth compare to the trend in sales prices? Does this same trend hold true for all the neighborhoods across San Francisco?

**Answer:** Both metrics have a positive trajectory over the timeframe examined. However, the gross rent per square foot increased substantially while the sale price per square foot only increased modestly.

**Question:** What insights can you share with your company about the potential one-click, buy-and-rent strategy that they're pursuing? Do neighborhoods exist that you would suggest for investment, and why?

**Answer:** If you can secure an investment property in this market, the cash flow potential is enormous. The 5 year percent change in gross rent was **202%** and the percent change over all 6 years was **254%**. The caveat being the high cost barrier to entry for buying in this market. While the percent change over all 6 years increased **88%** was not as strong as gross rent, it still represents considerable growth.