# Labor-Market-Analysis

LMA_project

For this project, we will use individual-level data from the 2016 American Community Survey (ACS).

Research questions:

- In the state of Washington, how do women's personal earning vary by educational attainment? 
- Does the premium for higher educated women vary by race?

The Census Bureau provides each state’s data file in comma separated value (CSV) format. We choose Washington State's data to analyze, data source: https://www2.census.gov/programs-surveys/acs/data/pums/2016/1-Year/csv_pwa.zip

We will be using the population records (elsewhere called person records) rather than the housing records.

The data dictionary provides variable names and codes; it's in this repository; the codes for the person records begin on page 35.

target columns:

AL: MAR(Marital status)
BS: WAGP (Wages or salary income past 12 months)
BN: SCHL (Educational attainment)
Race:RAC1P, RAC2P, RAC3P. Which one to use?

Sample Selection Criteria:

We use individual-level data in Washington State from the 2016 American Community Survey (ACS) to examine earning gaps between individuals with different educational attainments. The American Community Survey (ACS) is a national survey that uses continuous measurement methods. In this survey, a series of monthly samples produce annual estimates for the same small areas (census tracts and block groups) formerly surveyed via the decennial census long-form sample. In our study, we define workers as individuals who are over 16 years old and full-time workers who work more than or equal to 40 hours per week. Our sample consists of 24,710 individuals in total. Specifically, there are 12,050 people with or without high school diploma, 8,830 people with college degree, 620 people with professional degree, 2,775 people with master’s degree, and 435 people with doctor degree. Regarding total personal earning, we define it as individuals who earns over $1 during the past year. 
