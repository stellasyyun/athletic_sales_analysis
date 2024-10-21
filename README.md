# Athletic Sales Analysis

For this challenge, I showed how to combine datas from different years into one dataframe and aggregate the data by needs. I was able to combine data based on its region and retailer, and add up the sales to figure out which are on the top. I could also resample the data by daily or weekly bins and calculate the total sales based on the dates.

### Data Analysis

During 2020-2021, top 5 cities for total products sold were New York, Houston, San Francisco, Los Angeles, and Miami. However, top 5 for total sales had several changes in its list. Houston and Los Angeles were replaced by Charleston and Orlando when total sales were calculated instead of units sold.

Adding retailer as a new column showed that West Gear in San Francisco made the most sales out of all retailers. It kept its first place for total number of women's athletic footwear sold as well.

Lastly, resampling the data showed how much sales were being made every day or week. The day with most total sales was July 16th 2021 while week with most total sales was from December 19th 2021.

### Conclusion

Modifying data in various ways such as `group_by`, `pivot_table`, `resample` made it easier to read specific informations that I want to get from a large table. By trying to read the data from csv file, it would be impossible to figure out the top selling retailers or regions as well as weekly and daily sales.
