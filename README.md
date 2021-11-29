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
[!Total Riders by Area](https://github.com/srfassihi/PyBer_Analysis/blob/d38391777d4b1003a0bf864a01a6e1404c893045/analysis/Fig6.png)

Furthermore, the data shows that nearly 2/3 of PyBer's total fares came from the urban areas. This relationship is strong with the riders share data.
[!Total Fares by Area](https://github.com/srfassihi/PyBer_Analysis/blob/d38391777d4b1003a0bf864a01a6e1404c893045/analysis/Fig5.png)

Over 80% of drivers serviced the urban areas during the same time period. This further paints a picture of dominance in the urban areas and underservicing in suburban and rural locations.
[!Total Drivers by Area](https://github.com/srfassihi/PyBer_Analysis/blob/d38391777d4b1003a0bf864a01a6e1404c893045/analysis/Fig7.png)

## Summary
Below is a summary of the totals for each area: Urban, Suburban and Rural. It shows that riders in the rural areas have to pay on average ~$10 per ride more than their urban counterparts. This could be factored due to higher competition and availability of drivers as well as shorter distances traveled in the urban areas. PyBer can encourage more rural and suburban riders by increasing the availability of drivers in those areas.
[!Summary DataFrame](https://github.com/srfassihi/PyBer_Analysis/blob/e994fc5b32c6c37cd3e7795f854b919a36e0a73d/analysis/Summary%20df.png)

