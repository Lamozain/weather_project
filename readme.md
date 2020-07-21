# EXPLORE WEATHER TRENDS
## by  AMOS MOSES OMOFAIYE (UDACITY DAND SCHOLAR)


## Dataset Processing

> This dataset is on world temperature averages across prominent cities.

> I took some time out to read on the choice of moving averages for temperature data and I
decided to settle on moving average of 30 years and 5 years to be plotted in different charts.
Thereafter I created an excel sheet to house all the data that I will use in creating the line chart.
This file I titled tempdata.xlsx. And then I calculated the moving averages using 30 and 5 years
respectively for global and city average temperature data.
> Because the data for Abuja started from 1856, I used global data starting from 1856 also so as to
have equal data points.
> Abuja has no data for 1863-1872 and 2014-2015. But I am certain that temperature is not
zero(0) in those years, therefore I substituted the average data for the years before them for
those years. In general, as a result, I have 160 data points to compare for both variables.
> Using a moving average of 30 years (this is due to climate definition), I end up having 130 equal
data sets for both variables. I made sure that I left all data points to four decimal places. This
dataset was then used to draw the line chart.

#### Research Question
> I  explored based on the folowing broad research question:
<ol> 
    <li>Is the temperature in Abuja changing?</li>
    <li>Is the temperature in the neighbouring cities changing?</li>
    <li>Is the temperature of the world changing?</li>
</ol>


## Summary of Findings
> These are the main findings:
- Abuja is on the average hotter than the global average. This is understandable because
Abuja is in the tropical region of the world.
- The difference has been consistent overtime. It is normal that a tropical city like Abuja
should be hotter than the global average consistently.
- Abuja’s temperature trend greatly mimics global temperature trend. According to the graph,
between 1890 and 1896 the city’s temperature dropped and so is the world temperature.
Between 1932 and 1950, the city’s temperature greatly increased and so does the world
temperature. The only difference is that the global temperature does not rise as much.
- From 1986 to 2013, Abuja’s temperature kept increasing. The global temperature also kept
increasing. Although the graph shows a slight dip in 2014 and 2015, this does not accurately
mirror reality because the data for the two years were derived from the average of 2012
and 2013 because they were originally not available. To understand this better, the global
graph should be studied. It does not show any dip in increase from 1986 to 2015 and the
data used were the accurate (original) one.
- To show the relationship between Abuja’s temperature and global temperature, the
correlation coefficient was calculated and this gave a strong correlation of 0.8759.
- The overall trend shows that the world is getting hotter. This has been greatly consistently
since 1986.
- These observations are also true for Accra and Abidjan.