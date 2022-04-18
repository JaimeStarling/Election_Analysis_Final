# Election_Analysis

# An Analysis of Voting Results from a Colorado Congressional Precinct Election

## Overview of Election Audit:

This congressional precinct’s tabulation of votes has been performed with [(**Python**)](https://www.python.org/) coding [(provided here)](PyPoll_Challenge.py) from a submitted csv (*comma-separated values*) spreadsheet [(provided here)](election_results.csv) following ballot collection. The purpose is to apply the code to future elections in order to determine the winner and details of the win in a more efficient and accurate way.

## Election Audit Results:

*The results are also [(provided here)](election_analysis.txt)*. 

The total number of votes submitted for analysis is **367,711**. Of the three counties in this precinct:

- **Arapahoe County** had 23,801 votes, or 6.7 percent of the submitted ballots.

- **Denver County** had 306,055 votes, or 82.8 percent of the submitted ballots.

- **Jefferson County** had 38,855 votes, or 10.5 percent of the submitted ballots.

As we do not have the number of registered voters in each county, the voter turnout (the term *turnout* is used differently in the code) cannot be calculated. However, of the votes collected, **Denver County had the most votes** followed by Jefferson County and then Arapahoe County.

The three candidates in this congressional race, each presumably listed on the ballot and not as write-in candidates, are **Charles Casper Stockham**, **Diana DeGette**, and **Raymon Anthony Doane**, no political party affiliations cited. Below are the results from processing the submitted ballots via Python:

- **Charles Casper Stockham**: 85,213 votes, or 23.0 percent of the submitted ballots.

- **Diana DeGette**: 272,892 votes, or 73.8 percent of the submitted ballots.

- **Raymon Anthony Doane**: 11,606 votes, or 3.1 percent of the submitted ballots.

**The winning candidate of this election is Diana DeGette**, with 73.8 percent of the submitted ballots, that being 272,892 votes.

## Election Audit Summary:
With some modifications, the provided Python code can take on other csv spreadsheets of collected information and quickly provide accurate tabulation and results for the Colorado Board of Elections. See the image below at how the command line can show results as soon as the code is run:
![This is an image](https://github.com/JaimeStarling/Election_Analysis_Final/blob/main/Screen%20Shot%20Election%20Analysis%20to%20Terminal.png)
It is applicable to local elections, senatorial elections, gubernatorial elections, and to an extent, any future ballot measures or state propositions. Anything grander may require federal approval but for the Centennial State, this code can save a lot of time and trouble.
