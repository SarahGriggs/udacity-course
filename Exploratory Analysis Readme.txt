Data Source: http://stat-computing.org/dataexpo/2009/the-data.html

My analysis of Flight data was done using data from years 2002 through 2008. Multiple years were chosen in order to use year as a variable in addition to month and day of week. 
To organize the data I made a date variable in DateTime format from the day, month, and year. I also created a delay Boolean variable that indicated if any of the five types of delays were present on the given date. 
A large correlation chart showed bivariate, positive correlations between delays and date as well as air craft carrier and delay. Leading me to look further into date associations and carrier associations.  
When exploring delays by carrier I chose to look at delays per year as a percentage of total flights per year.  This would allow me to determine which carrier had the most delays in proportion to their flight load. I found that some carriers were consistently the ‘worst’ with delays. It was also interesting to see that the number of flight carriers declined as years progressed. This makes sense as there were some airline mergers within this time. 
I also explored the relationship between day of week and total delays. This relationship proved to be interesting. I found that the most delays were on Fridays. I see that there is an association between the most amount of flights on a week day and the most amount of delays on a week day.
I further created a Boolean for each type of delay to see how delay amount by type of delay changed per year. The most delays were seen in 2007 (both in total and as a percentage). We see that NAS Delays are the most common and Security delays are the least. NAS are the most general delay with weather, airport ops, traffic control, and gate delays all falling in this category. This seems to make sense. 
I was curious if there was seasonality to the delays. First I looked at total delays. This table shows that December has the most delays (394K) and the graph shows that it has the highest percentage of delayed flights. This chart will need to be cleaned and have months follow an order.  I also made a chart that showed individual types of delays with seasonality. This will need to be ordered for the Explanatory. 

Sources:
https://pandas.pydata.org/pandas-docs/stable/user_guide/merging.html
https://stackoverflow.com/questions/18171739/unicodedecodeerror-when-reading-csv-file-in-pandas-with-python
https://stackoverflow.com/questions/29432629/correlation-matrix-using-pandas
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.where.html
https://stackoverflow.com/questions/20375561/joining-pandas-dataframes-by-column-names
https://python-graph-gallery.com/122-multiple-lines-chart/
https://stackoverflow.com/questions/45747589/copying-a-column-from-one-dataframe-to-another-gives-nan-values
https://medium.com/@mjspeck/presenting-code-using-jupyter-notebook-slides-a8a3c3b59d67
