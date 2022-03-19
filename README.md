# SF_fire_department

In this project I worked with three of my classmates to visualize San Francisco's fire department response time against different factors in order for us to see what factors are important.

We used pyspark to be able to query information, do data dusion, and create dataframes and graphs from this data set that had over 5.5 million rows and 34 columns.

The process of this project:
1. We first put the data up on aws s3 buckets and used spark to read them in.
2. We found another data on funding of deparments in SF to merge in with our main dataset for us to explore the possibility of funding being an important factor for the repsonse time of the fire department.
3. We then used pyspark to preporcess our data and make sure is all ready for us to create data frames and graphs.
4. We then used spark to creat spark dataframes and then by using spark dataframes we were able to create graphs to visualize average response time against year, budget, unit type, and by neighborhood.
