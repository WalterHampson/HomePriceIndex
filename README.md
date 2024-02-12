# Zillow Home Values

Collaborators 

Walter Hampson, Drew Kirke, Michael Haile, Kortney Cose

Background

The purpose of this project is to analyze home prices based off Zillow data to determine trends and predict future pricing. The data introduced is intended to allow you to correlate home prices to different economic indicators and urbanization.
Throughout this project we will be analyzing Zillow Home Pricing Index data. We will use this data to identify the average change in home prices in the US within the last 5 and 10 years. This data will also allow us to gather what States see the largest increases in home pricing.  To determine what may influence changes in home prices, we will compare trends from FRED data that outlines different economic measures such as inflation, consumer pricing index, and interest rates. Using US census populations, we be able to determine if home pricing and urban population growth have any correlation. With this data we should be able to predict how home prices will trend in the future. This will be useful information to identify how home prices interact with other economic measures and developments. The learning from this project will allow others to anticipate home prices based off fiscal standings and performance. 

Which states have the greatest increase of home pricing within the last 5 years? 10 years? 
How does inflation influence overall home pricing? 
What type of relationship do interest rates have to home pricing?  
What is the average change in home prices in the US within the last 5 years? 10 years? 
What is the relationship between urbanization rates and home prices per state? 
Can we predict future home prices using a regression analysis? 

We will use a combination of pandas and matplotlib to clean and display the data to answer the above questions. 

FILES

ZILLOW
https://www.zillow.com/research/data/ (ZHVI.csv) 
Select time phased data set and download
![image](https://github.com/WalterHampson/ZillowHomeValue/assets/152203394/cc747c67-af6a-4dc1-bef0-89d515a3c7d4)

FRED
All files from the federal reserve Economic data can be accessed with the below link: https://fred.stlouisfed.org/ 
Search Report name
Press download button
Select preferred file format

https://fred.stlouisfed.org/series/DFF 
Federal Funds Effective Rate (FEDFUNDS.csv) 
 ![image](https://github.com/WalterHampson/ZillowHomeValue/assets/152203394/8f29dbfd-d2da-4eda-a355-6b935d4a476c)

https://fred.stlouisfed.org/series/MORTGAGE30US 
30 - Year Fixed Rate Mortgage Average in the United States (MORTGAGE30US.csv)
 ![image](https://github.com/WalterHampson/ZillowHomeValue/assets/152203394/a3ec53d7-155a-4ecf-9ac4-3d7692efebab)

https://fred.stlouisfed.org/series/CPIEHOUSE
Research Consumer Price Index: Housing (CPIEHOUSE.csv)
 ![image](https://github.com/WalterHampson/ZillowHomeValue/assets/152203394/df41b1dc-a26b-43d8-9363-509aff8153d6)

https://fred.stlouisfed.org/series/CPIHOSSL 
Consumer Price Index for All Urban Consumers in U.S. City Average (CPIHOSSL.csv) 
 ![image](https://github.com/WalterHampson/ZillowHomeValue/assets/152203394/a12540b0-88c9-4c64-9e8c-2c5aa95964e2)

UNITED STATES CENSUS BUREAU
Census Data can be accessed from the reference page located below:
https://www2.census.gov/geo/docs/reference/ua/ (State_Urban_Rural_Pop_2020_2010.csv)

We assume to see a close correlation to economic indicators and urbanization and their relationship to home price indices. 

