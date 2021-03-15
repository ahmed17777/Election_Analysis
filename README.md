# Election_Analysis

Syed Ahmed 
March 3, 2021 


## Overview of Election Audit 

In this project, the election comission has requested a complete audit of voter turnouts by county. We will be using Python to analyze the following: 
- Voter turnout for each county 
- The percentage of votes from each county of the total count 
- The county with the highest turnout 

## Election-Audit Results 

Upon running the analysis of voter turnout, we came up with the following findings: 

- There was a total of 369,711 votes cast in the election 

- County Votes: 
  - Jefferson:  10.5% ( 38,855)
  - Denver:  82.8% ( 306,055)
  - Arapahoe:  6.7% ( 24,801)

- Denver had the largest number of votes 

- Candidate Votes Stats: 
  - Charles Casper Stockham: 23.0% (85,213)
  - Diana DeGette: 73.8% (272,892)
  - Raymon Anthony Doane: 3.1% (11,606)

- Winning Candidate: 
  - Winner: Diana DeGette
  - Winning Vote Count: 272,892
  - Winning Percentage: 73.8%

The following is a screenshot of the results printed in Terminal using Python: 

![results](https://user-images.githubusercontent.com/45697471/111227926-bd853600-85b9-11eb-94a2-1cefdcb03eef.png)

## Election-Audit Summary: 

This Python script can be used to analyze any election. The use of variables throughout the script means that we can change the data without having a direct affect on the code. Examples of how this script can be reused include:
- In the case of a federal election, we can change the "counties" to "states" and run the script normally. 
- In the case of a university student body election, we can use the same script and change the "counties" to "parties" 
