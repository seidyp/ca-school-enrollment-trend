# California School Enrollment Trend
Did you know California school enrollment rates in LA have decreased significantly in the past few years? Our team wants to analyze if there is a correlation between California school enrollment trends relating to unemployment rates. 

## Our Hypothesis and Research Questions
1. Hypothesis: 
- School enrollment in California decreases when the unemployment increases
2. Research Questions:
- How is school enrollment trending in California? Within cities?
- Are there enrollment trend differences within different regions in California?
- What trends are observable with unemployment rates in California? Within cities?
- Is there a strong correlation between enrollemnt trends and unemployment rates?

## Tools and Libraries Project Uses
- Python
  - Pandas
  - Matplotlib
  - Stats
  - Requests
  
## Sources and Libraries 
Enrollment data was pulled and built upon [California School Districts] (https://www.greatschools.org/schools/districts/California/CA/)

Employment data was pulled and built upon [Census API] (https://data.census.gov/cedsci/table?q=employment&g=0400000US06,06.960000,06.970000&tid=ACSST1Y2014.S2301&hidePreview=true)

Census Data API User Guide can be found [API User Guide] (https://www.census.gov/content/dam/Census/data/developers/api-user-guide/api-guide.pdf)

## Our Divide and Conquer Strategy 
- Team Enrollment 
- [x] Pull data from 2015-2019 
- [x] Merge all data together by school district code
- [x] Clean data
- Team Employment
- [x] Pull data via API from 2015-2019 including 3 school types: Unified, Elementary, and Secondary
- [x] Merge yearly data all together 
- [x] Merge all datas together
- [x] Clean data

##### Combining, Plotting, and Analysis
1. Combine both employment and enrollment data
2. Plot line graphs and scatter plot to find trends

## Final Analysis
After extracting, cleaning, and merging the data, we were able to conclude that the correlation between school enrollment rates and unemployment rates is weak.

![Alt text](Visualization/unemp_vs_yoy_enroll_change.png?raw=true "correlation")

First, we graphed Los Angeles school district from 2015-2019. It shows us a significant decrease of school enrollments.

![Alt text](Visualization/LAUSD_enrollment_trend.png?raw=true "LAUSD Enrollment Trends")

Secondly, we graphed the average percent change throughout the years. As the graph shown above, it indicates the average overall school enrollment decreases as well. 

![Alt text](Visualization/LAUSD_enrollchange_unemployment.png?raw=true "ca_average_percent_change")


However, when plotting the enrollment rates and unemployment rates together. We found that the using a linear regression the correlation coefficient to be 0.05 (first table). This shows a weak positive correlation between unemployment rate and total enrollment by district. 

## Next Steps

Oh, bummer! Unemployment rates are not the best factor to correlate with enrollment rates for datasets in California from 2015-2019. 

If you are interested in this enrollment data, things you may want to consider.
1. Other economic factors such as CPI
2. Whether you want to add 2020 (COVID year)
3. Adding private schools to public schools

## Hope you enjoyed the project as much as we did!








