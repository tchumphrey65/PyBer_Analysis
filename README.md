# PyBer Analysis
## Ride Share data Analysis

## Deliverables (Number 1)

Ride Analysis by city type

![Data Frame Ride data by city type](https://user-images.githubusercontent.com/91839403/146114560-4f1e30bc-c10f-4127-bdb8-5864d21d2965.png)


This analysis shows ride data and analysis by rural, suburban and urban city types.  The data by city type shows Total Rides, Total Drivers, Total Fares, Average fare per ride and average fare per driver.

## Deliverables (Number 2)
1. DataFrame using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time. 

![image](https://user-images.githubusercontent.com/91839403/146115026-4355e962-b52c-4307-9e09-e7192989e828.png)

2. DataFrame using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare."

![image](https://user-images.githubusercontent.com/91839403/146115235-e19fba52-378a-4a89-8c7d-561c78754557.png)

DataFrame created using the loc method on the date range: 2019-01-01 through 2019-04-28. 

![image](https://user-images.githubusercontent.com/91839403/146115359-4c9e44e1-6f57-40bf-91ed-22de5e85da05.png)

DataFrame created using the resample() function in weekly bins and shows the sum of the fares for each week.

![image](https://user-images.githubusercontent.com/91839403/146115467-e821fde8-ebcd-483a-9d71-c5c5654d970d.png)

Produce an annotated chart showing the total fares by city type is created and saved to the "analysis" folder.

![Fare_by_city_chart](https://user-images.githubusercontent.com/91839403/146115513-8f76ddfa-4c81-4079-bedc-8d479e0abcfc.png)


## Deliverables (Number 3)

# Overview of the analysis

## Background
Our client V. Isualize has tasked us to analyze data from PyBer ride sharing creating a summary DataFrame of the ride-sharing data by city type and a  multiple-line graph showing the total weekly fares for each city type. The client requested a written report summarizing the data by city type and showing how those differences can be used in decision-makeing at PyBer.

## Approach
Utilize Python, Pandas, matplotlib and Numpy to create a summary DataFrame of the ride-sharing data by city type and a multiple-line graph that shows the total weekly fares for each city type.

## Results
The analysis shows that Urban cities have the most drivers, generates 63% of all fares in total and with the most drivers has the lowest fare per ride and fare per driver.  The data also shows that over 85% of all rides happen in Urban cities.  The largest Fare / Driver happens in rural cities, the highest fare/ride is also seen in rural cities.  The chart of the data by city over time shoes the smae with fare totals highes in Urban cities, Suburban cities in second and Urban cities the lowest in total fares by month.  The trends over the months show spikes in April in all areas, with lower numbers in January. The spike in April might be worth more investigation There is variability over the months but no trends or significant spikes that stand out.

## Summary: 
Results and recommendations
Based on this analysis there may be some opportunity to capitalize on the spike in April by offering incentives or a follow up inentive to offset the drop in march, especiall in suburban areas.

The other areas of oppirtunity may be to look at January for creating additional ride traffic.  This is a low point in Urban and Suburban areas.  Marketing, parterning or other avenues might be worth looking into to boost January numbers.

THe third area to mine for opportunity is Suburban and Rural PyBer usage. There may be more ride opportunity there but lacking drivers and the cost of rides may be limiting usage.

More data analysis would be useful on all areas to find opportiunity or identify trends.  Knowing the hours drivers are available in all areas and the percentage of utilization would help in decision making.  The reason the rural ride costs are so high would also be important to analyze and understand.  THe other data that would be interesting to study by type of city would be ride purpose or destination.  Are the trips business or pleasure?  That might help define mechanisims for pricing or for increasing driver participation to support new ride demand.

------------------------------------------------------------------------------------------------------------------------------------------------------------
