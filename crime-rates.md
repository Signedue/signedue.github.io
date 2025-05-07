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



## Gender Differences in Crime Rates Across Danish Municipalities

To better understand how gender affects criminal activity, the following bar charts display the average crime rate per 10,000 residents from 2008 to 2024, split by gender (Men and Women) for the Top 5 and Bottom 5 municipalities based on overall crime rates.

This visualization builds on the previous analysis by showing how men and women contribute differently to the crime statistics in high- and low-crime areas.
<iframe src="/crime_gender_top.html" width="100%" height="600" frameborder="0"></iframe>

The first chart illustrates the average crime rate per 10,000 residents for men and women across the five municipalities with the highest overall crime rates: **Brøndby, Guldborgsund, Ishøj, Lolland, and Odense**. Across the board, men are responsible for the vast majority of recorded crimes, with rates ranging from around 18 to 24 per 10,000 residents. In contrast, women’s crime rates remain consistently low, typically between 1 and 2 per 10,000. **Lolland** stands out with the highest male crime rate, while **Odense** has the smallest gender gap, though the difference is still substantial. This pattern reinforces the significant gender disparity in crime involvement, particularly in high-crime areas.


<iframe src="/crime_gender_bottom.html" width="100%" height="600" frameborder="0"></iframe>

The second chart presents the same gender-based comparison for the five municipalities with the lowest average crime rates: **Christiansø, Fanø, Hørsholm, Odder, and Skanderborg**. While the overall crime levels are much lower here, the gender gap remains pronounced. Men still commit far more crimes per capita than women, though the rates are typically between 4 and 4.5 for men and under 0.5 for women. **Skanderborg** and **Odder** have slightly higher male crime rates than the rest, but the general trend of minimal female crime persists. This consistency across different crime environments suggests that the gender divide is a robust feature of local crime patterns.



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



## Types of Crime – Top vs Bottom 5 Municipalities

While earlier sections focused on overall crime rates, it's also important to understand *what kinds* of crimes are being committed. In this section, we break down total offences from 2007 to 2024 by major crime categories.

We focus on the five municipalities with the **highest** and **lowest** average crime rates and examine how their crime profiles differ. The goal is not to explain why these differences exist, but to provide a clearer picture of the nature of crime in different areas.

<iframe src="/crime_offence_top.html" width="100%" height="600" frameborder="0"></iframe>

In the Top 5 municipalities, crimes of violence are the most prominent category across the board — particularly in Lolland and Guldborgsund. Odense and Brøndby also show high levels of property crimes and violations of special acts. Lolland stands out with notably high values in almost every category.

<iframe src="/crime_offence_bottom.html" width="100%" height="600" frameborder="0"></iframe>


By contrast, in the Bottom 5 municipalities, crime levels are much lower across all categories. The most common offences here are sexual offences and traffic law violations, with only small variation between municipalities. Christiansø, being a very small municipality, shows extremely low or even zero incidents in most categories.

The contrast highlights not only differences in crime volume, but also variation in the types of crimes that are most prevalent in each area.



## Crime Distribution by Gender – Top vs Bottom 5 Municipalities
To better understand the gender dynamics behind different crime types, we separate crime rates by gender across the top 5 and bottom 5 municipalities. The values shown are standardized by population, expressed as crimes per 10,000 residents over the period 2007–2024.

This breakdown allows us to see whether men and women contribute differently to overall crime levels — and whether these differences vary by crime category or municipality.

<iframe src="/crime_offence_gender_top.html" width="100%" height="600" frameborder="0"></iframe>

Men consistently exhibit higher crime rates across all municipalities and crime types — especially in violent offences and property-related crimes.

In top 5 municipalities, male crime rates are significantly higher in categories like Crimes of violence and Other offences.

<iframe src="/crime_offence_gender_bottom.html" width="100%" height="600" frameborder="0"></iframe>

Gender gaps are narrower in the bottom 5 municipalities due to overall lower crime levels, but male rates still dominate, particularly in traffic-related and property offences.

Notably, female crime rates are most visible in Offences against property and Special acts, although still markedly lower than those of males.

---

## Conclusion

This analysis has shown significant variation in crime rates across Danish municipalities over time, between genders, and by type of offence. Municipalities such as Lolland and Guldborgsund consistently experience higher crime rates, particularly driven by violent and property crimes, whereas municipalities like Christiansø and Fanø show minimal criminal activity overall. A strong and consistent gender gap is evident: men commit significantly more crimes than women across all offence types and locations. This pattern is robust even in low-crime areas, indicating that gender is a key determinant in crime data.

Furthermore, high-crime municipalities also tend to exhibit greater volatility in yearly crime rates, suggesting more unstable or dynamic crime environments. On the other hand, municipalities with lower crime rates demonstrate more consistent patterns year over year.


---


## Next Step: Modeling Crime Rates

Based on these insights, we propose building a machine learning model to **predict crime rates** using municipality-level data. Given the consistent gender disparities, it makes sense to start by focusing on **male crime data only**, as including women — whose crime rates are much lower and more stable — may reduce the model’s ability to detect meaningful patterns.

By training a model specifically on male crime rates, we aim to explore how demographic, spatial, and temporal features (such as year, population size, and municipality) influence crime levels — and to assess how well we can forecast future crime trends.

To understand and predict crime patterns, we trained a Random Forest regression model on male crime rate data from Danish municipalities. The model uses year, municipality, and population size as input features to predict crime rates per 10,000 residents.


<iframe src="/crime_predicted1.png" width="100%" height="600" frameborder="0"></iframe>


The chart above compares the predicted crime rates against the actual observed values. Each dot represents a municipality-year combination. The closer the points are to the red dashed line, the more accurate the model’s predictions.

With an R² score of 0.781 and RMSE of 2.55, the model demonstrates good predictive power. While some under- and overestimations exist, the overall fit indicates that temporal, spatial, and demographic features are meaningful predictors of male crime rates across Denmark

