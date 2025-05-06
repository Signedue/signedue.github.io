---
layout: default
title: Crime Rates
---

# Crime Rates in Danish Municipalities

This page gives an overview of crime rates in Danish municipalities from 2008 to 2024.

We focus on the five municipalities with the highest average crime rates and the five with the lowest.
The crime rate is calculated for each year by dividing the number of reported crimes by the population of the municipality that year. To allow for fair comparisons, we express this as the number of crimes per 10,000 residents.
The goal is to provide a starting point for exploring how crime varies across the country and over time. 

The visualizations are interactive to make it easier to compare and spot trends. While we don't aim to explain why the differences exist, this page can help highlight where patterns may be worth looking into further.


This chart shows the five municipalities in Denmark with the highest and lowest average crime rates from 2008 to 2024.

- **Top 5**: Lolland, Brøndby, Guldborgsund, Ishøj, and Odense.
- **Bottom 5**: Odder, Skanderborg, Hørsholm, Fanø, and Christiansø.
Crime rates are measured per 10,000 residents.


<iframe src="/crime_rates_plotly.html" width="100%" height="600" frameborder="0"></iframe>

On the graph above we see the Crime rates over time for the five municipalities with the highest average crime levels.
- **Top 5**: Lolland, Brøndby, Guldborgsund, Ishøj, and Odense.

All municipalities seem to spike around year 2012-2013 and then there is a decline. After year 2015 the crime rates in the municipalities varies more, espeacially the top 4 which all viaries with about 10 in the period 2015-2025.
Odense seems to have succesfylly lowered the crimerate after 2015 and we dont see it incline again like the top 4 municipalities. 

<iframe src="/crime_timeseries_top5.html" width="100%" height="650" frameborder="0"></iframe>

The crime trends in the municipalities with the lowest average crime rates we see:
- **Bottom 5**: Odder, Skanderborg, Hørsholm, Fanø, and Christiansø.   
Christiansø remains at the lowest point - zero incidents, throughout the whole period. 
Fanø is the municipality with the most variations as we see that it ranges from 0 to 12 incidents throuout the years
<iframe src="/crime_timeseries_bottom5.html" width="100%" height="650" frameborder="0"></iframe>


## Crime Rate Volatility – Top vs Bottom 5

Some municipalities show more stable crime levels year over year, while others experience larger fluctuations. To measure this, we calculate the **standard deviation** of the crime rate from 2008 to 2024.

A high value indicates greater yearly variation, while a low value means crime levels have been relatively consistent.

<iframe src="/crime_volatility_top_bottom.html" width="100%" height="600" frameborder="0"></iframe>


The visualization reveals that municipalities with **higher average crime rates** (in red) also tend to have **greater volatility**. For example, **Odense** and **Ishøj** show large year-to-year changes, suggesting less stable crime patterns.

In contrast, the municipalities with **low average crime rates** (in green) generally show **more consistent levels** of crime. **Christiansø** stands out with no recorded incidents during the entire period, while others like **Odder** and **Hørsholm** maintain relatively steady trends.

This contrast may reflect underlying differences in population size, social conditions, or law enforcement consistency.
