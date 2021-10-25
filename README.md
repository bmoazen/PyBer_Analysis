# PyBer_Analysis
## Overview 
In this project, we used the pandas library in python as well as the matplotlib package to analyze the total ride-share fares by day for three city types: rural, suburban, and urban.  Our resource data was individual ride-shares by date, time, city, cost, and city type.

## Results
All figures shown here can be found in the "Analysis" folder of this repository.
<br />
During the roughly 4 months that this study looked at, urban areas had on average, 7 more rides per day than suburban areas, and 18 more rides per day than rural areas.  Shown below is a box and whiskers plot of the number of daily rides for each city type.
<br />
![alt text](https://github.com/bmoazen/PyBer_Analysis/blob/main/Analysis/Fig2.png?raw=true)<br />
<br />
However, while urban areas had more rides per day than suburban or rural (which is to be expected), the average fare was highest for rural areas (see figure below).  This may not be surprising, since fares would likely take into account distance and rural areas tend to be much more sparsely populated.
<br />
![alt text](https://github.com/bmoazen/PyBer_Analysis/blob/main/Analysis/Fig3.png?raw=true)
<br />
Overall, though, urban areas accounted for almost 63 percent of the total fares for the over 4 month period in this analysis (see pie chart below), showing that of the total 'market share' of the three city types, urban areas take in the most money.
<br />
![alt text](https://github.com/bmoazen/PyBer_Analysis/blob/main/Analysis/Fig5.png?raw=true)
<br />
The total weekly fares taken in by city types is shown below.  Given the results above, it is not surprising that the urban areas took in much more in fares each week
.<br />
![alt text](https://github.com/bmoazen/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png?raw=true)
<br />
Obviously, the more rides that are given, the more the need for drivers.  The urban cities have over two times the number of suburban city drivers on average, and over 7 times the number of rural drivers.  This information could prove crucial to deciding on where to focus ride-sharing programs, as more drivers will increase the total salary.
<br />
![alt text](https://github.com/bmoazen/PyBer_Analysis/blob/main/Analysis/Fig4.png?raw=true)
<br />
## Recommendations
When considering where to focus ride-sharing programs, the scale of the investment could be the deciding factor on what city type to choose.  As seen in the figures in the results section, the highest average fare is in rural areas.  However, more rides will comes from urban areas (but with the added cost of more drivers).  For these reasons:
1) If the investment is planned to be small, and not many drivers will be hired, it would most likely be better to invest in rural rise-sharing, where the average fares are much higher and fewer drivers are needed.<br />
2) If the investment is planned to be relatively large, and many drivers will be hired, it would most likely be better to invest in urban rise-sharing, where the volume of rides is at a maximum and the increase in drivers won't run the danger of over-saturation (i.e. having a lot of drivers in the rural areas may lead to a lot of down-time since there are less available customers).<br />
3) Given a medium-sized investment, the suburban areas strike somewhat of a balance between the average fares and the needed number of drivers.




