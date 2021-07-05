# election_analysis

## Overview
The purpose of this activity was to build a python program that will assist a election comission with their election audit.  This program will greatly speed up the audit by providing key results quickly.

## Election-Audit Results
- Total Votes: 369,711

- County Votes:
  - Jefferson: 10.5% (38,855)
  - Denver: 82.8% (306,055)
  - Arapahoe: 6.7% (24,801)

- Largest County Turnout: Denver

- Candidate Votes:
  - Charles Casper Stockham: 23.0% (85,213)
  - Diana DeGette: 73.8% (272,892)
  - Raymon Anthony Doane: 3.1% (11,606)

- Winner: Diana DeGette
  - Winning Vote Count: 272,892
  - Winning Percentage: 73.8%


## Election-Audit Summary
This program is capable of running this audit for any file in the same format.   Furthermore with some modifications the program could cycle through many similar election datasets and provide reports of them very quickly. In order to cycle through many different election datasets the program needs to be wrapped in another for loop which will load the different datasets. Additionally, this program could keep track of total votes in the state, the largest county turnout of the state, which elections had the smallest or largest margins of victory, and the winners of each county election. This could be accomplished by simply repeating sections of the existing code to apply to all the files entered instead of just a single file.
