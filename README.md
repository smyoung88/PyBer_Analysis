# PyBer_Analysis

## Overview
In this project, we role-played as a second week data analyst at PyBer, a ride-sharing app company valued at $2.3 billion. Our task was to analyze all the rideshare data from January to early May of 2019 and create compelling visualizations for the CEO at PyBer. CEO, V. Isualize, is interested to see the summary of the ride-sharing data by city type; specifically, the total weekly fares for each city type and the differences between them so decision-makers at PyBer can better their business. Those differences are summarized below.

## Results
The differences in ride-sharing data among the different city types is summarized below:

### Ride-Share Analysis by City Type
Ride-share analysis was calculated for total rides, total drivers, total fares, average fare per ride, average fare per driver by city type and is summarized in the following table:
<br>
<p align="center">
<img src="https://github.com/smyoung88/PyBer_Analysis/blob/main/analysis/city_type_analysis.png" title="Ride-Share Analysis by City Type">
</p>
<br>
There are both positive correlations and inverse correlations with this dataset. The first three columns show a positive correlation relative to assumed population for each city type and the latter two columns show an inverse relationship and is summarized below:
<br><br>
<b>Positive Correlation</b>
Population is assumed to be highest in the city (urban), followed by suburbia and rural. Because of this, there will be more rides, more drivers to give those rides, and a higher total dollar amount in fares due to the increased ride total.
<br><br>
<b>Inverse Correlation</b>
Assuming the same population trends as described in the positive correlation, there are a couple different reasons why the average fares per ride and average fares per driver will be higher in smaller population areas and cheaper in the city. There is a possibility that PyBer charges more for rides in areas with less people due to simple supply and demand. Another posibility that comes to mind is people in suburban and rural areas may need to travel further to get to their destination as those areas are much more spread out compared to navigating around the city which is much more compact. These destinations would cost less for the quicker commute time.

### Total Fare by City Type
<p align="center">
<img src="https://github.com/smyoung88/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png" title="Total Fare by City Type">
</p>
<br>
The total fares per month by city type analysis follows the positive correlation described above. Total fares per month for the most part stayed in the ranges of $2,000 - $2,500 for urban, $1,000 - $1,500 for suburban, and $0 - $500 for rural city types.


## Summary 

<b> Business Recommendations for Addressing Disparities Among City Types</b>
1. If any new areas of interest are being deciphered on for deployment of PyBer's business, I would recommend urban areas be targeted for best return of investment. In this dataset, urban areas made 2.6 times and 13 times more rides than suburban and rural areas respectively. With the averages fare per ride staying within $10 dollars between each city type, urban arease provide the biggest carrot.
2. $10 per ride is not a very big difference from a rural ride to an urban ride given the lesser amount of drivers available to give rides to those in rural areas. I would recommend a price increase on rural rides (price per mile) as there are less ride opportunities available and to make sense economically, those fares have to be worthwhile.
3. Urban is the only city type that has more drivers available than the amount of rides that occured. Each driver in rural areas make 1.60 rides, suburban make 1.28, and urban only make .68 per driver. What this means is each driver in rural and suburban gets better opportunities to give rides than Urban. I would recommend cutting the workforce in drivers for urban areas to increase the economics per driver in the city. If the goal is to ensure that each driver gets at least one ride, this would mean that 780 drivers did not have the opportunity to give rides at PyBer. If they only get paid based off the rides they give, this would not necessarily be a problem, but anything outside of that, PyBer would be in the negative.
