# PyBer_Analysis

## Project Overview

### Assignment
1. Create a summary dataframe of the PyBer ride sharing data by city type
2. Create a multiple-line graph showing the weekly fares by city type
3. Create report summarizing the differences by city type from the dataset

### Steps

1. Import ride and city data into a Pandas DataFrame.
2. Merge the DataFrames.
3. Create a Line chart showing the:
    - Weekly fares by city type
    
### Software Requirements
- Python 3.6 or higher
- JuPyter Notebook (Recommended)
- Anaconda (Recommended)

### Dependencies
- pandas
- matplotlib (with Pyplot installed)
- numpy (if using VS Code)
- scipy (if using VS Code)

## Results 
There is slightly over 2/3 share of riders from the urban areas compared to suburban and rural areas over the period from January 2019 to May 2019.  
![Total Riders by Area](https://github.com/srfassihi/PyBer_Analysis/blob/d38391777d4b1003a0bf864a01a6e1404c893045/analysis/Fig6.png)

Furthermore, the data shows that nearly 2/3 of PyBer's total fares came from the urban areas. This relationship is strong with the riders share data.
![Total Fares by Area](https://github.com/srfassihi/PyBer_Analysis/blob/d38391777d4b1003a0bf864a01a6e1404c893045/analysis/Fig5.png)

Over 80% of drivers serviced the urban areas during the same time period. This further paints a picture of dominance in the urban areas and underservicing in suburban and rural locations.
![Total Drivers by Area](https://github.com/srfassihi/PyBer_Analysis/blob/d38391777d4b1003a0bf864a01a6e1404c893045/analysis/Fig7.png)

## Summary
Below is a summary of the totals for each area: Urban, Suburban and Rural. It shows that riders in the rural areas have to pay on average ~$10 per ride more than their urban counterparts. This could be factored due to higher availability of drivers, larger population density, and shorter distances traveled in the urban areas. 
- Shorter distances can be attributed to availability of Public Transportation options such as buses and trains in those areas as well. Due to lack of access to these public resources most potential PyBer customers may be encouraged to provide their own transportation method. 
- Lack of riders may also pose a problem for drivers as well which rely on the PyBer fares for their livelihood. PyBer can find ways to incentivize drivers in rural and suburban areas where there is a potential market. Further market analysis can be done to identify which specific cities are most suitable for these subsidies.
![Summary DataFrame](https://github.com/srfassihi/PyBer_Analysis/blob/e994fc5b32c6c37cd3e7795f854b919a36e0a73d/analysis/Summary%20df.png)

The last chart shows the 'Total Fare by City Type over the period of January 2019 to April 2019. There is noticable growth in demand in the urban areas for PyBer's services. We can observe an overall flat trend for both suburban and rural areas. Suburban areas seem to deviate the most from the average with local minimum of $700 to maximum of nearly double (~$1400). This could indicate the beginning of an increasing trend due to the peak occuring at the end of the time period. There is a shared peak in late Februrary 2019 in all three city types. This could be attributed to an increase in travel around this time.
![Total Fare by City Type](https://github.com/srfassihi/PyBer_Analysis/blob/1563415459f637fce750e4ecb8777f4687103d04/analysis/PyBer_fare_summary.png)

### Recommendations
1. Continue to drive costs down in urban areas to encourage growth and nudge customers to use the 'recommended tip' feature and 'driver rating' system.
2. Further market research in rural and suburban areas to identify potential demand growth for ride sharing services.
3. Plan for incentivizing PyBer drivers to service areas with ride sharing demand potential such as car rentals.
