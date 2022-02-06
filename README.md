# Election Analysis

## Overview of Election Audit

In this analysis, our purpose was to gather summary data from a congressional election for the Colorado Board of Elections. This included calculating the total number of votes cast, highlighting the candidates with the number and percentage of votes they received, to determine the winning elected official of the race. We provided further analysis by looking at voter turnout for each county, the percentage of votes from each county based on the total votes, and identifying the county with the highest turnout. 

We received the data via a .CSV file and utlized Python to code the calculations and analyze the data.  

## Election-Audit Results

* How many votes were cast in this congressional election?
  * A total of 369,711 votes were cast in this election.
* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  *  Jefferson County cast 38,855 votes (10.5% of the total)
  *  Denver County cast 306,055 votes (82.8% of the total)
  *  Arapahoe County cast 24,801 votes (6.7% of the total)
* Which county had the largest number of votes?
  *  Denver, with 306,055 votes cast.
* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  *  Charles Casper Stockham - 85,213 number of votes (23% of total votes)
  *  Diana DeGette - 272,892 number of votes (73.8% of total votes)
  *  Raymon Anthony Doane - 11,606 number of votes (3.1% of total votes)
* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  * Diana DeGette won the election with 272,892 votes (73.8% of total votes). 

*Visual representation after analysis* 

![Alt text](https://raw.githubusercontent.com/lgonzales1/election_analysis/main/election_data.png)

## Election-Audit Summary

By using Python, this code can be used in analyzing other elections. For example, the script can be modified from a state election to a national election. In this instance, the county would be replaced with state. 

Additionally, if there was more information provided, we can provide further analysis. For example, rather than just voter turnout, we could analyze the voters based on their demographics. We would need to add additional loops and if statements if more data is available, but the detail of analysis could be substancially more significant. 
