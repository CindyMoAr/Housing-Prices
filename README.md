# Housing-Prices
Assignment proposed by the Applied Data Science with Python course in Coursera. Data cleaning and Hypothesis Testing with Pandas.

Hypothesis: University towns have their mean housing prices less effected by recessions. Run a t-test to compare the ratio of the mean price of houses in university towns the 
quarter before the recession starts compared to the recession bottom.

##### The following data files are available for this assignment:

1. From the Zillow research data site there is housing data for the United States. In particular the datafile for all homes at a city level, City_Zhvi_AllHomes.csv, has median home sale prices at a fine grained level.
2. From the Wikipedia page on college towns is a list of university towns in the United States which has been copy and pasted into the file university_towns.txt.
3. From Bureau of Economic Analysis, US Department of Commerce, the GDP over time of the United States in current dollars (use the chained value in 2009 dollars), in quarterly intervals, in the file gdplev.xls. For this assignment, only look at GDP data from the first quarter of 2000 onward.

##### Definitions:

- A quarter is a specific three month period, Q1 is January through March, Q2 is April through June, Q3 is July through September, Q4 is October through December.
- A recession is defined as starting with two consecutive quarters of GDP decline, and ending with two consecutive quarters of GDP growth.
- A recession bottom is the quarter within a recession which had the lowest GDP.
- A university town is a city which has a high percentage of university students compared to the total population of the city.

##### Tasks
1. Load and clean the data set university_towns.txt
2. Load and clean the data set gdplev.xls
3. Returns the year and quarter of the recession start time as a string value in a format such as 2005q3.
4. Returns the year and quarter of the recession end time as a string value in a format such as 2005q3.
5. Returns the year and quarter of the recession bottom time as a string value in a format such as 2005q3.
6. Plot the data.
7. Load the data set 'City_Zhvi_AllHomes.csv'.
8. Convert column names to quarters and map 'State' column.
9. Create new data showing the decline or growth of housing prices between the recession start and the recession bottom.
10. Run a ttest comparing the university town values to the non-university towns values,return whether the alternative hypothesis (that the two groups are the same)
    is true or not as well as the p-value of the confidence.

