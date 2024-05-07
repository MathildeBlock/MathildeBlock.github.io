 ---
layout: page
title: Evolution of Motherhood in Denmark
permalink: /Project/
---

## Babydoom
During the 2020’s the media has had a huge focus on the declining birth rate in Denmark as well as the ascent in the average age of birth giving women. In this project we will investigate this trend and delve into the regional patterns of child birth over time. We will look at data from the Danish statistics repository, Danmarks Statistik, with the aim of trying to find out if there are any patterns or correlations that can explain the declining birth rate. We will also look at the consequences of and reasons for the declining birth rate and discuss this downward trend.


# Data
The data we will use in this project is from Statistics Denmark. We will use data from the last 17 years to see if we can find any patterns or correlations that can explain the declining birth rate. The data includes age of the mother, area of residence and year.


# How bad is it really?
For a start let's look at the number of births in Denmark over the last 17 years. To see how the actual situation concerning birth rates really is, we have made a plot showing the total number of births for each year. The plot can be seen below. Notice that the plot is zoomed in on the y-axis to make it easier to see the differences between the years.
![Total Births](total_births+fit.png)


From the plot we can see that the number of births fluctuate over the years, and we see the least amount of births is in 2013. Such a stark decline is very interesting to look into as it was not something that we had heard about in the media. We found that a likely explanation for this drop in 2012, 2013 and 2014 is that there were less women born in the 80's, which is now the women in a childbearing age. This is according to [Folkeskolen.dk: Fødselstallet bølger op og ned](https://www.folkeskolen.dk/folkeskolen-nr-13-2019-kommunal-okonomi-skolen-i-samfundet/fodselstallet-bolger-op-og-ned/1387193)
Another explanation is that financial conditions for families worsened due to political regulations.
[TV2.dk Børnetal i Danmark falder fortsat](https://nyheder.tv2.dk/sundhed/2012-07-10-boernetal-i-danmark-falder-fortsat)



We also see a slight increase in the number of births in 2021, which we expect is due to the corona pandemic - couples are more home and have the opportunity to work from home and therefore decide to get a baby as the possibility to take care of it is larger. The decrease in births in 2009 we suspect is due to the financial crisis, making it less likely to have children, due to the associated expenses.
We chose to fit a line to the data to see the trend over the years. We see that the trend is declining, which is what we expected, based on headlines in the media. The number of births in Denmark has generally been very inconsistent, with some years 195000 births and then with years such as 2013 where less than 170000 children were born. Such inconsistent and declining birth rates, especially combined with a higher and growing lifespan, gives many people concerns about the population: who will take care of the many elders if there are no young people? Many elders come with a high cost to society, so who will pay for this if no young people are earning money? The elders in the Danish welfare system depend on their own tax money, however they also depend a lot on the tax paid by the coming generations, which have to keep the sails of the welfare system flowing.
For this the young population is questioned continuously and even called traitors by right wing politicians. [Thomsen W. D. C., Wulf A. S., Andersen J. L.,  Information.dk, 2024](https://www.information.dk/debat/2024/04/slags-stille-landsforraederi-naar-ressourcestaerke-danskere-fravaelger-faa-boern)


To further investigate we wanted to see if the pattern was the same for all parts of Denmark, so we made a plot showing the number of births for each region. The plot can be seen below.
![Births per region](regions_births+fit.png)


Here we see that the general tendency for Copenhagen actually is inclining instead of the expected decline, which is what is happening in all other regions. 
This is an example of Simpson’s paradox, which is a phenomenon, where a trend appears in several groups of data but disappears or reverses when the groups are combined.
This can be due to more people living in Copenhagen now, with many who have moved here from the other regions these last couple of years.
Generally there is also a clear tendency that the bigger the city, the higher the educational level and with this, a higher age for motherhood. This is not surprising as the largest cities have the most opportunities in regards to jobs after studies, studies and it is also in these larger cities that cultural movements typically reside, which leads to better awareness of social issues. (https://www.tv2kosmopol.dk/lorryland/kobenhavnerne-er-mere-bekymrede-klimaet-end-resten-af-danmark)


To look more closely at the different municipalites, we have made an choropleth map over the different municipalities in Denmark. The map can be seen below. The map shows the number of births for each municipality in 2020. The map is interactive, so you can click on the different municipalities to see the number of births for each municipality.

![Births per municipality](birthsindk.png)



# Age of the mothers
Another aspect we wanted to investigate was the age of the mothers. As one of the arguments we hear often is that women wait too long to have children, which makes it harder to get pregnant naturally. We have made an interactive plot, where you can see the number of births for each age group - where the year can be changed. This plot can be seen below.


<div style="width: 1250px; margin-left:-100px; margin-bottom:-100px;">
<iframe src="/births_vs_age.html" width="1000px" height="800px"></iframe>
</div>

One thing that has stayed consistent is the age distribution of the birthing parent. Nicely, normally distributed around the age of 30, which makes sense when looking at what age most women are done with their education. In this day and age, many don't want to mix their studies with having children. For the first time in many years, the opportunities for women in the labor market are very lucrative and it is no longer frowned upon for a woman to choose to go for a higher level of education. This is an opportunity taken by many and this could result in the falling number of births. Together with the rise in awareness of how babies affect the climate and with so much uncertainty on what the future holds in regards to climate and war, many women are either waiting longer or choosing to be childfree altogether.(https://www.sciencedaily.com/releases/2021/04/210421160016.htm)
Not to even mention the fall in sperm count and quality in men. This combined with all mentioned previously could also be a reason for the higher age of mothers.


When looking at the data we can see that women in the 2000's generally are younger than now, when giving birth. We also see that in the start of the 2010's women around 30 had fewer children than other years, this might be because there are less women born in the 80's as we discussed previously.


This is also shown in the plot below, where we have calculated the mean age of the mothers for each year. The plot shows that the mean age of the mothers has increased over the years. The problem with this is that the older the mother is, the harder it is to get pregnant naturally. This might be one of the reasons why the birth rate is declining.


![Mean age](mean_age.png)


We wanted to explore the age of the mothers in the different municipalities, so we made a plot showing how many children are born to mothers of different ages in the different municipalities. The plot is interactive, so you can click on the different ages to see the number of births for each municipality. The plot can be seen below.

<div style="width: 1200px; margin-left:-150px;">
<iframe src="/birth_count_map.html" width="1200px" height="800px"></iframe>
</div>

We find that the age of the mothers is generally higher in the larger cities, which is not surprising as the largest cities have the most opportunities in regards to jobs after studies, studies and population density. We observe that women generally are younger moms in Jutland. Please explore the map, to find out more about the age of the mothers in the different municipalities. Notice that when municipalities are white, it is because there are no births for that municipality in that age group.

# Income
As an addition to the previously addressed subjects related to birth rates, we chose to dive into income related data in the Danish Municipalities, to gain insight into the incomes for couples with and without children based on education levels. As the plot of Income Comparison between different municipalities suggest, there is a higher income in the larger cities, which can both indicate that more men and women earn more money due to better and more available jobs, as well as the fact that salaries are usually higher in bigger cities. However, the higher income levels in municipalities should also correlate with increased birth rates, as observed in larger cities. This may, however, also be associated with the population density.


![Income](income.png)


# Interventions on Reverting the Downward Trend
During recent years the women of modern societies have tried to break up the traditional roles and view of the women, as being a housekeeping wife and mother only being present to take care of the household tasks and giving birth to children. Times have evolved, and especially young women strive more towards financial freedom and stability as well as closing the gender gap between men and women. Hence, women educate themselves into their mid-/late twenties, which is also where their fertility starts becoming worse, and decreases the monthly chance of conceiving. To conclude on the trends seen in birth rates, it would be necessary for politicians to come up with interventions that make the society fit to the fertility, to avoid the descending birth rate going out of control.






This is our final project for 02806 - Social data analysis and visualization, written by:


**Authors**
* s183624
* s204201
* s194666