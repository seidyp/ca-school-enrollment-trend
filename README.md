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
Team Enrollment 
1. Pull data from 2015-2019 
2. Merge all data together by school district code
Team Employment
1. Pull data via API from 2015-2019 including 3 school types: Unified, Elementary, and Secondary
2. Merge yearly data all together 
3. Merge 


