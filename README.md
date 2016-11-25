# Applied Data Science in Python
Data science class assignments and projects in Python using real life datasets. Code is written in Jupyter Notebook.
##Following Jupyter notebooks are included:

1. Assignment 4 - Hypthosis Testing
   Hypothesis: University towns have their mean housing prices less effected by recessions. 
   Run a t-test to compare the ratio of the mean price of houses in university towns the quarter 
   before the recession starts compared to the recession bottom. 
   The following datasets are used for this project:
   a. Monthly median home sales price data of United States is obtained from the Zillow web site. 
   In particular the datafile for [all homes at a city level.](http://files.zillowstatic.com/research/public/City/City_Zhvi_AllHomes.csv).
   b. From the Wikipedia page on college towns is a list of university towns in the United States.
   c. From Bureau of Economic Analysis, US Department of Commerce, the GDP over time of the United States in current dollars 
   (use the chained value in 2009 dollars), in quarterly intervals. For this assignment, only look at GDP data from the first quarter of 2000 onward.
   
   
2. Assignment 3 - Data Cleaning, Transformation, Merging, and Charting
   Tasks: Load the [energy supply and renewable electricity production](http://localhost:8888/notebooks/ds_with_python/Energy%20Indicators.xls) data from the United Nations for the year 2013. 
   Make sure to exclude the footer and header information from the datafile. The first two columns are unneccessary, 
   so you should get rid of them, and you should change the column labels so that the columns are:
	['Country', 'Energy Supply', 'Energy Supply per Capita', '% Renewable's]
    Convert the energy supply and the energy supply per capita to gigajoules (there are 1,000,000 gigajoules in a petajoule). 
	For all countries which have missing data (e.g. data with "...") make sure this is reflected as np.NaN values.


3. Assignment 2 - Reading, Grouping, Aggregation and Sorting
This file consists of solutions for 13 questions. Talk more about data cleaning and transformation. Move grouping up.
In order to complete this assignment, one needs to use Pandas to first clean data using regular expression. 
group data, merging data and applying statistcal functions to the data sets. Three data sets are used for this assignment.

##Below datasets are used for this assignment.
1. olympics.csv, this dataset was derived from the Wikipedia entry on [All Time Olympic Games Medals](https://en.wikipedia.org/wiki/All-time_Olympic_Games_medal_table). Used in assignment 2 of Pandas. 
2. census.csv: this dataset contains population data from counties and states in the US from 2010 to 2015. 
It is from [United State Census Bureau.] (http://www.census.gov/popest/data/counties/totals/2015/CO-EST2015-alldata.html)
See [this document](http://www.census.gov/popest/data/counties/totals/2015/files/CO-EST2015-alldata.pdf) for a description of the variable names.