# Erica Wurster
Time Ser Model Bus 33:136:485:03  
Professor Parikh  
Assignment #3  

## Question 1: Uploaded WomenUnemploymentRate.xlsx in this repository


## Question 2: Detailed description of the data

The dataset contains time series data for the unemployment rates for women in the U.S., displayed monthly, from January 1948 to January 2025. 

# Data Dictionary for Unemployment Rates of Women in the U.S. (1948-2025)

| Variable Name     | Readable Variable Name       | Measurement Units | Allowed Values                             | Definition of the Variable                                                                                                                                  | Synonyms        | Description of the Variable                                                                                                                                                              |
|-------------------|------------------------------|-------------------|--------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| observation_date  | Observation Date              | MM/DD/YY           | Minimum: 1/1/1948, Maximum: 1/1/2025   | Date when each data point is recorded | Date             | The observation date refers to the exact date on which the unemployment rate was recorded for women in the U.S., with each entry representing the first day of the month.              |
| LNS14000002       | Unemployment Rate (Women)     | Percentage (%)    | Minimum: 0.0%, Maximum: 100.0%             | Represents the proportion of women in the labor force who are unemployed but actively seeking employment | Unemployment rate | This variable represents the unemployment rate for women in the U.S., reported monthly. The rate is expressed as a percentage with one decimal point (e.g., 3.3%). |


## Question 3: Data Collection Methodology

The data is published on the Federal Reserve Economic Data (FRED) website, but is collected by the U.S. Bureau of Labor Statistics (BLS) through the Current Population Survey (Household Survey). This survey is conducted monthly and provides estimates on various labor market indicators, including unemployment rates.

To estimate the unemployment rate for women, the ratio of weighted women employees to all employees in the sample is used. This ratio is assumed to be the same in the broader population, and it is calculated using a weighted-difference-link-and-taper formula. The formula adjusts the estimate based on changes in the sample composition and provides the monthly unemployment rate for women in the U.S.

The data is seasonally adjusted and is released on a monthly basis.


## Question 4: Why does this data set intrigue you?

When searching for a time series dataset, I was immediately attracted to those surrounding unemployment rates. This was mainly because I see a lot online and in the media today that it is virtually impossible to find a job, so comparing unemployment rates now to those over the past 70+ years would provide many insights. Additionally, I saw that there was data focused female unemployment. Especially as this dates back to 1948, I think it will be extremely interesting to investigate how trends in the data may correlate with how women's places in society and the home changed over the years.





