# TFA-Final-Project
This is the final project of Tools for Analytics (Project Group 54) at Columbia Engineering.

## Project Information
Section: Tools for Analytics IEOR4501 - 002 (Tuesday Section)
<br /> Group Name: Project Group 54
<br />List of UNI: mc5092, rw2906
<br /> Meixi Chen (mc5092)
<br /> Ruying Wang (rw2906)


## Project Overview
In this project, we explored the dataset recording 311 phone number for non-emergency services in New York City in 2020. Two problems were studied:
<li> What are the top 10 causes of calls to 311 are in our chosen ZIP code?
<li> Is illegal parking incidents a larger fraction of total 311 incidents in our ZIP code than they are in general?

The ZIP code we chose to analyze is 10025, an area near Columbia University campus. 
<br /> The results of our analysis are stored in two files: Top10.ipynb and Parking.ipynb

### Top 10 Analysis
  <li> Import dataset as a Pandas DataFrame
  <li> Create a sub-dataframe containing information from chosen ZIP code
  <li> Use <code> <i> groupby</i></code>,<code><i>size</i></code>,<code><i>sort_values</i></code>functions to return the target series.

    
### Parking Analysis
  <li> Import dataset as a Pandas DataFrame
  <li> Create a sub-dataframe containing information from chosen ZIP code
  <li> Use <code> <i> groupby</i></code>,<code><i>size</i></code>,<code><i>sum</i></code>functions to return the target boolean.
