# EECS731P1DataExplorer

Creation Steps
  Step 1:
    Project Structure set up in this Git Repository
  Step 2:
    Installed Anacode3 and Python 3.6
  Step 3:
    Industry selected is Politics, specifically political contributions
  Step 4:
    The two data sets selected for this project were taken from Data.Gov
    The first data set is data on political contributions to candidates in the State of Washington, originally containing data from 2007 to 2016
      -Removed records using excel first based off of because JupyterLab was taking too long to load the file
    The second data set is data on political contributions to candidates in the city of San Francisco, originally containing data from 2009 to 2019
  Step 5:
    Data Sets were loaded into Pandas following the "https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html" guide
  Step 6:
    Data Set could be used to check to see if an increase in contribution during a calender year in a State like Washington could predict an increase in the following year in San Francisco
  Step 7:
    Just grabbed the year and amount column from each data set. Removed empty values and removed the years of data that we had for only one data set. Renamed columns on data sets to distinguish columns after merge. Merged data sets on common years
  
