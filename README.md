# 2008-Flight-Delay-and-Cancellation-Analysis
Analysis and visualization of factors contributing to delay and cancellation of flights across airports and carriers in US for 2008.
The following libraries are used in this project:

NumPy
pandas
Matplotlib
Seaborn

## Dataset

This dataset reports flights in the United States, including carriers, arrival and departure delays, and reasons for delays, for the year 2008. The data can be found here: http://stat-computing.org/dataexpo/2009/the-data.html

The goal of this analysis is to understand the reasons for delay and cancellation in the year 2008 and also look at patterns across carriers and airports. Some of the key questions to answer are

1. Do certain origins and destinations, or their combinations have higher cancellation rates and delays in comparison to others.
2. Does month have an impact on cancellation and delay?
3. Do certain carriers have more cancellations and delay?

Data Prep
	1. Created a new data frame 'cancelled_flights' which has data of cancelled flights recorded for the year 2008 in the data set.
	2. Created a new data frame called 'delayed_flights' which has non-null value for delay reasons (Carrier, Weather,NAS etc.) for the year 2008 in the data set.
	3. Concatenate 'Origin' and 'Dest' to create a new column 'origin-dest'.
	4. Transform Arrival delay and Departure Delay to Log Values.


## Summary of Findings

1. Higher Cancellation in Winter Months.
2. ORD airport has highest number of cancellations and delays.
3. The carrier 'WN' has highest number of delayed flights.
4. The carrier 'NW' has highest delay time for Arrival and Departure.

## Key Insights for Presentation
The presentation is broken into sections of Univariate, Bivariate and Multivariate Analysis. The findings have been visualized using python packages Matplotlib and Seaborn. Distribution plots and Bar charts are used for univariate analysis. Box plots, heat maps and scatter plots are used to describe relationships in bivariate and multivariate analysis.
The visualizations make it easy to understand the correlation between delay reasons, visualize the cancellation reasons for each carrier among other important findings.




