# PyBer_Analysis

# Analysis of PyBer Ride Sharing Data

## Overview of the analysis

We have analyzed ride-share data (to visualize using different graphs such line, bar, or pie charts) with the aim to help PyBer improve access to ride-sharing services and determine affordability for underserved neighborhoods. The goal of this analysis was to create a summary DataFrame of the ride-sharing data by city type, and then to use Pandas and Matplotlib, for creating a multiple-line graph that shows the total weekly fares for each city type. The visualizations generated from this analysis will inform the trends and facilitate decisiuon making. 

Software Tools Used: Python/ Pandas, Matplotlib, NumPy

## Results

The overall ride-share data shows that there is a huge difference in the number of rides between city types (See **Figure 1** below).
- The order for number of rides is (Rural (125) < Suburban (625) < Urban (1625)). 
  Therefore the total fares from each of the city types have larger gaps.
  
- The average fare for a ride is highest among the rural rideshares. 
  The trend forthe average fare is Rural ($34.62) > Suburban ($30.97) > Urban ($24.53). 
  
- The number of drivers depended on the number of rides. It follows the trend similar to the number of rides (Rural (78) < Suburban (490) < Urban (2405). 
  It is interesting to see that there are more drivers than the number of rides among urban ride-shares. 
  
- The average fare per driver is highest among rural ride-shares whereas it is the lowest among urban ride shares (urban ($16.57) < suburban ($39.50) < rural ($55.49). 

![PyBer-Summary DataFrame](/analysis/PyBer-Summary-DataFrame.png)
 ### Figure 1. Summary of rideshares between city types
 
The line graph of the total fare by city type (**Figure 2**) shows the weekly fare of each city type over 16 weeks (January - April). 

- The trend for weekly fares is  as follows: below $500 for rural neighborhoods, between $500-$1500 for suburban neighborhoods, and between $1500 - $2500  for urban neighborhoods. 

- The last week of February was the week with peak fares for all the city types. The following week (1st week of March), it dropped for each city type. 
  The weekly fares fluctuated differently for each city type (peaks and dips are different in each city type). 
    - The fare for suburban ride-shares was lower than other weeks in the 1st week of January, 1st week of March, and 2nd week of April. 
    - The lowest in fares for both urban and suburban ride shares is for the 1st week of January.

![PyBer-Fare Summary](/analysis/PyBer_fare_summary.png)
### Figure 2. The multi-line graph for fare by city type

## Summary

In summary, the total rides, the total drivers, and the total fares had larger gaps between city types. Therefore the earnings are significantly different between city types. There may be factors that affect the differences in ride-shares such as infrastructure (e.g. roads and conditions and accesibility, gas stations, phone usage, internet access etc.) and the availaibility of automobiles (cars, vans etc.). It may also be in part due to the affordability for people for ride-shares. It is obvious that the urban cities have more drivers and more ride-shares. The suburban areas falls between rural and urban cities and that can be expected. 

The following recommendation can be made based on this analysis.
1. Lower the rates for ride shares for rural and suburban cities while keeping fare rates among urban ride-shares. 
2. Increase the number of drivers to rural and suburban cities (it may also need to encourage drivers by providing incentives, provisions for gas etc. for ride-shares in those under previledged neighborhoods). 
3. Initiate discussions with city administrations on ways to improve infrastructure in needed neighborhoods (especially in rural areas).  

The link to the Notebook: [PyBer_Challenge](PyBer_Challenge.ipynb)
