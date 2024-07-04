# Data Analytics Portfolio
by Andrew Dyet


## Project 1 - Cleveland Crime Statistics

**This Jupyter notebook file uses the Cleveland City API - Crime Incidents**

[Download Crime Statistics Here](https://data.clevelandohio.gov/datasets/c749e34199c1425cbbc5959308658ec3_0/explore?location=41.370816%2C-81.632583%2C10.60)

Note: To run the notebook, save the .csv file renamed crime.csv in the same folder as the notebook

To view the Tableau Dashboard of this project, click [here](https://public.tableau.com/shared/8RHS7Z26R?:display_count=n&:origin=viz_share_link)

The purpose of this project is to answer the following questions: 
- Which types of crime are the most common?
- Is there a correlation between the time of day, day of the week, or month of the year, where crime spikes?
- Which neighborhoods have the highest crime rates?
- Which zip codes have the highest crime rates?

The steps taken to clean the data are as follows;

1. Import data and set the encoding type
2. Drop Duplicated rows and rows with null values
3. Set date type as datetime, set zip codes type as int64, format the names of cities
4. Create a dataframe of crimes from 2016-2024, eliminating outlier values

The conclusions drawn are: 

- The most common crimes are Assault, Theft, and Vandalism.
- The most common times for crime to occur are noon and midnight, with no correlation between amount of crime and days of the week.
- The neighborhood with the highest crime is the city of Cleveland.
- The zip code with the highest crime is 44102.

## Project 2 - United States Senate Stock Trades

[Download Stock History Here](https://senatestockwatcher.com/api)

Note: To run the notebook, save the .csv file renamed trades.csv in the same folder as the notebook

To view the Tableau Dashboard of this project, click [here](https://public.tableau.com/views/SenateStockTrades/Dashboard1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

The purpose of this project is to answer the following questions: 
- What sectors are most commonly traded?
- Which political party trades stocks the most?
- Is there a particular senator that has traded more stocks than the rest?
- Was there a period of time where the most stocks were traded?

The steps taken to clean the data are as follows;

1. Import required packages
2. Import data as a csv
3. drop duplicate rows and rows with null values
4. Change dtype of dates to datetime
5. Begin creating plots to draw conclusions

The conclusions drawn are:

- The most commonly traded sector is Finance followed by Health Care.
- Republicans trade more often and at higher volume than Democrats or Independants.
- Kelly Loefler and Susan M. Collins traded the highest amount of money in stocks.
- The year with the most trades was 2020 with 1,168 trades with the majority happening in the month of April.
  
