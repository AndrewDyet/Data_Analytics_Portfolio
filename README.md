# Data Analytics Portfolio
by Andrew Dyet


## Project 1 - Cleveland Crime Statistics - Using Pandas, Numpy, Seaborn, and Tableau

**This Jupyter notebook file uses the Cleveland City API - Crime Incidents**

[Download Crime Statistics Here](https://data.clevelandohio.gov/datasets/c749e34199c1425cbbc5959308658ec3_0/explore?location=41.370816%2C-81.632583%2C10.60)

Note: To run the notebook, save the .csv file renamed crime.csv in the same folder as the notebook

To view the Tableau Dashboard of this project, click [here](https://public.tableau.com/shared/8RHS7Z26R?:display_count=n&:origin=viz_share_link)

The purpose of this project is to answer the following questions: 
1. Which types of crime are the most common?
2. Is there a correlation between the time of day, day of the week, or month of the year, where crime spikes?
3. Which neighborhoods have the highest crime rates?
4. Which zip codes have the highest crime rates?

The steps taken to clean the data are as follows;

1. Import data and set the encoding type
2. Drop Duplicated rows and rows with null values
3. Set date type as datetime, set zip codes type as int64, format the names of cities
4. Create a dataframe of crimes from 2016-2024, eliminating outlier values

The conclusions drawn are: 

1. The most common crimes are Assault, Theft, and Vandalism.
2. The most common times for crime to occur are noon and midnight, with no correlation between amount of crime and days of the week.
3. The neighborhood with the highest crime is the city of Cleveland.
4. The zip code with the highest crime is 44102.

## Project 2 - United States Senate Stock Trades - Using Pandas, Numpy, Seaborn, and Tableau

[Download Stock History Here](https://senatestockwatcher.com/api)

Note: To run the notebook, save the .csv file renamed trades.csv in the same folder as the notebook

To view the Tableau Dashboard of this project, click [here](https://public.tableau.com/views/SenateStockTrades/Dashboard1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

The purpose of this project is to answer the following questions: 
1. What sectors are most commonly traded?
2. Which political party trades stocks the most?
  3. Is there a particular senator that has traded more stocks than the rest?
  4. Was there a period of time where the most stocks were traded?

The steps taken to clean the data are as follows;

1. Import required packages
2. Import data as a csv
3. drop duplicate rows and rows with null values
4. Change dtype of dates to datetime
5. Begin creating plots to draw conclusions

The conclusions drawn are:

1. The most commonly traded sector is Finance followed by Health Care.
2. Republicans trade more often and at higher volume than Democrats or Independants.
3. Kelly Loefler and Susan M. Collins traded the highest amount of money in stocks.
4. The year with the most trades was 2020 with 1,168 trades with the majority happening in the month of April.
  
## Project 3 - Chicago Crime Statistics - Using SQLite3 and Pandas

The purpose of this project is to demonstrate SQL query abilities by referencing 3 separate dataframes and drawing conclusions based on these queries.
