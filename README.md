# 2008-Flight-Delay-and-Cancellation-Analysis
Analysis and visualization of factors contributing to delay and cancellation of flights across airports and carriers in US for 2008.
The following libraries are used in this project:

NumPy
pandas
Matplotlib
Seaborn

Data Gathering:
This dataset reports flights in the United States, including carriers, arrival and departure delays, and reasons for delays, from 1987 to 2008. Link - http://stat-computing.org/dataexpo/2009/the-data.html
Dataset structure - The analysis is performed on 2008 year's data first and then extended to other years. df_2008 has 7009728 entries, 29 columns. 

Data Analysis and Visualization:
ArrDelay (Arrival Delay),DepDelay (Departure Delay),Cancelled,CancellationCode are the main features to be analyzed. The analysis is to understand the following:

1. Do certain origins and destinations, or their combinations have higher cancellation rates and delays in comparison to others.
2. Does month have an impact on cancellation and delay?
3. Do certain carriers have more cancellations and delay?


