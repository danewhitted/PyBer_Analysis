# PyBer_Analysis

Purpose: The CEO, V. Isiulize requested a summry dataframe containing the key metrics: total rides, total drivers, total fares, average fare per ride, and average fare per driver, all by city type. You can see how the data distribution in the image. The rural areas had fewer rides, but larger fares compared to suburban and urban cities.

![](Pyber_Analysis/Pyber_Analysis/Images/pybersummary.PNG)

Pyber gave me two data files to analyze. One file contained metrics pertaining to each city, the	driver count, and the city type (rural, urban, suburban). The other contained the metrics city,	date,	fare,	and rides. In order to provide the summary requested these files had to be merged into one dataframe (pyber_data_df). Then I extracted: Total Rides,	Total Driver,	Total Fares	Average, Fare per Ride, and	Average Fare per Driver. With each new piece of data calculated I produced the summary dataframe (pyber_summary_df).

From the pyber_data_df dataframe I pulled the data(weekly fares by city type) needed to produce the line graph. 

![](Pyber_Analysis/Pyber_Analysis/Images/PyberFaresLineGraph.png)

It is worth noting the last week of February there is spike in fares in all three city types. This may require precautions like hiring seasonal drivers, etc. The rural area saw its best week the 1st of April and its worst week the second week of January. The Suburban area saw it's best week the last week of February and it's worst week in January. The urban area's best weeks were between the last week of Febraury and the first week of march, and it's worst week was the beginning of Janaury. 

I did not run into any major technical difficulties that I am aware of. I do not have enough experience to recommend any obstacles to look out for. Whenever I did run into an issue I could not solve quickly, a patient google search would reveal the answer.

I would recommend analyzing in more how many drivers are needed per city type. It doesn't seem to be apparent those numbers are being optimzed for profit at all times. The urban cities may have too many drivers. I could produce a dataframe that could compare slow and busy seasons with number of drivers and average fares. 


