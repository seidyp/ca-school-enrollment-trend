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
After pulling, cleaning, and combining the data, we were able to get an overview of the trends of LAUSD (Los Angeles Unified School District). 
![Alt text](/relative/path/to/img.jpg?raw=true "Optional Title")




