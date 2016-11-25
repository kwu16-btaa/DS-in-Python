## Applied Data Science in Python

Data science class assignments and projects in Python using real life datasets. Code is written in Jupyter Notebook. Following Jupyter notebooks are included:

#### 1. Assignment 4 - Hypothosis Testing
   
#### Hypothesis: University towns have their mean housing prices less effected by recessions. 
  
Run a t-test to compare the ratio of the mean price of houses in university towns the quarter before the recession starts compared to the recession bottom. 
   
The following datasets are used for this project
   * Monthly median home sales price data of United States is obtained from the Zillow web site. 
   In particular the datafile for [all homes at a city level.](http://files.zillowstatic.com/research/public/City/City_Zhvi_AllHomes.csv)
   * From the Wikipedia page on college towns is a list of [university towns in the United States.](https://en.wikipedia.org/wiki/List_of_college_towns#College_towns_in_the_United_States)
   * From Bureau of Economic Analysis, US Department of Commerce, the [GDP over time](http://www.bea.gov/national/index.htm#gdp) of the United States in current dollars 
   (use the chained value in 2009 dollars), in quarterly intervals. 
   
#### 2. Assignment 3 - Data Cleaning, Transformation, Merging, and Charting
  
#### Tasks: Perform data analysis to discover hidden relationships between below variables. 
   * Energy supply per capital.
   * GDP per capital.
   * Renewable energy as percentage of total energy supply.
   * Sciamgo Journal Country Rank data for Publications on Energy Engineering and Power Technology.

Below three datasets are used for this assignment

* Load the [energy supply and renewable electricity production](http://localhost:8888/notebooks/ds_with_python/Energy%20Indicators.xls) data from the United Nations for the year 2013. Make sure to exclude the footer and header information from the datafile. The first two columns are unneccessary, so you should get rid of them, and you should change the column labels so that the columns are:
For all countries which have missing data (e.g. data with "...") make sure this is reflected as np.NaN values.
* load the GDP data from the file world_bank.csv, which is a csv containing countries' GDP from 1960 to 2015 from [World Bank](http://data.worldbank.org/indicator/NY.GDP.MKTP.CD). 
Make sure to skip the header, and rename the following list of countries:
     
    	"Korea, Rep.": "South Korea",     
    	"Iran, Islamic Rep.": "Iran",    
    	"Hong Kong SAR, China": "Hong Kong"
        

* Load the [Sciamgo Journal and Country Rank data for Energy Engineering and Power Technology](http://www.scimagojr.com/countryrank.php?category=2102), which ranks countries based on their journal contributions in the aforementioned area. 

#### 3. Assignment 2 - Slicing, Grouping, Aggregation and Sorting Data

#### Task: Read csv files and return subset of data after slicing, grouping, sorting and aggregation.

Below tow datasets are used for this assignment
* olympics.csv, this dataset was derived from the Wikipedia entry on [All Time Olympic Games Medals](https://en.wikipedia.org/wiki/All-time_Olympic_Games_medal_table). 
* census.csv: this dataset contains population data from counties and states in the US from 2010 to 2015. 
It is from [United State Census Bureau.] (http://www.census.gov/popest/data/counties/totals/2015/CO-EST2015-alldata.html)
See [this document](http://www.census.gov/popest/data/counties/totals/2015/files/CO-EST2015-alldata.pdf) for a description of the variable names.
