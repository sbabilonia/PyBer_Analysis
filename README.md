# PyBer_Analysis
module 5 JN and Matplotlib


 The purpose of this analysis was to utilize Matplotlib in order to create line and bar charts, scatter plots, pie charts, and box-whisker-plots. These visualizations may be enchanced by adding: titles, axes labels, legends, custom colors, font size, errorbars and more. This module also utilizes new packages; numpy and scipy. In this module further applications with Pandas is also utilized. 

Results

For this challenge specifically, we took data from the pyber_data_df and created a new data frame 'pyber_summary_df' to observe features regarding city type vs a few points of interest:

![image](https://user-images.githubusercontent.com/90811811/152719132-3e89c9da-ece2-473a-855b-b9cffc23ad33.png)

It can be seen from pyber_summary_df Urban cities have the highest number of rides, fares, and total drivers with the lowest average fair per ride. Conversly rural cities have lowest number to total rides, fares, and drivers with the highest average fare per ride.

Possible explanations for the observed data may include: lack of total rides available leading to low driver count in rural areas despite average fair per driver being the highest of the city types. Long communte in rural areas means increased commute time, therefore increasing the average fare per driver and average fare per ride. Urban cities have the largest total rides. Due to high volume of rides, total profit from fares is largest in Urban citites. Average fare per ride and average fare per driver are the lowest in urban cities, possibly due to the high volume of rides and a shorter commutes. Suburban cities strike a balance between urban and rural cities most likely due to the hybridization of the aforementioned factors and is an expected outcome given the urban/rural city dynamic.

The figure(s) below shows the total fare by city type; line chart includes fares in USD on y-axis and the range of months (jan-april) on the x-axis

![image](https://user-images.githubusercontent.com/90811811/152720918-95b58cd8-57a7-4f9a-9dc8-60783728321c.png)

![image](https://user-images.githubusercontent.com/90811811/152721008-f332ab4c-54b7-4256-9915-2acbd4235e94.png)

Again, it may be observed Urban cities have the hightest total fares of the city types, while rural has lowest. Also of note is the time frame between the end of February/beginning of March. During this time all city types see an increase in total fares, followed by a sharp decline by the start of March.

The three business recommendations are as follows: to maximize access of ridesharing for underdeserved neighborhoods it is advised to put most time and resources into the Urban city type. With the highest in total fares while also being the lowest average fare per ride, ridesharing is cheapest for the consumer and most profitable by volume for PyBer.
In addition it is recommended to begin resource allocation to underdeserved neighborhoods early in the year (Jan/Feb) due to the lower fare cost. Lastly, it is recommended to allocate little resources to rural cities for the time being due to low total rides and driver volume. Although average fare per ride and average fare per driver are highest in rural cities, lack of volume from total rides and drivers leads to a more expensive fare for the consumer and lack in profitablity for PyBer.
