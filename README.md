# Election_Analysis

## Overview of Election Audit
The election commission has requested data to complete an audit of the most recent election. The audit consists of counting the votes for each candidate and county. 


## Election-Audit Results

- Total Votes: 369,711
- The county results:
  - Jefferson: 10.5% (38,855)
  - Denver: 82.8% (306,055)
  - Arapahoe: 6.7% (24,801)

![](https://github.com/mpfraser7/Election_Analysis/blob/main/Analysis/County%20Votes%20Code.png)

- Largest County Turnout: Denver

- Candidate results:
  - Charles Casper Stockham: 23.0% (85,213)
  - Diana DeGette: 73.8% (272,892)
  - Raymon Anthony Doane: 3.1% (11,606)

- Election winner: Diana DeGette with 272,892 votes and 73.8% vote percentage

## Election-Audit Summary
Given the simple and straightforward nature of this script, it could easily be tailored and used for other elections. For the script to work in it's current form, the county field and candidate name have to be exactly in the 2nd and 3rd column respectively. However, if other elections data was structured differently, we could modify the script to locate and find the the county and candidate columns using 'pandas.read_csv'. Also, we could have this script run through multiple CSV files and audit many election results at once by using a new For loop that looks for multiple csv files in one folder.

