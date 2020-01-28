# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.8, Visual Studio Code 1.41.1

## Summary
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The candidates were:
	- Charles Casper Stockham
	- Diana DeGette
	- Raymon Anthony Doane
- The candidate results were: 
	- Charles Casper Stockham: 23.0% (85,213)
	- Diana DeGette: 73.8% (272,892)
	- Raymon Anthony Doane: 3.1% (11,606)
- The winner of the election was:
	- Diana DeGette who received 73.8% of the vote and 272,892 votes

## Challenge Overview
The challenge asks to determine county turnout. Percentages will be respect to county rather than candidate.

## Challenge Summary
The analysis of the election show that:
- The county vote distribution of the total 369,711 votes were:
	- Jefferson: 10.5% (38,855)
	- Denver: 82.8% (306,055)
	- Arapahoe: 6.7% (24,801)
- Largest county turnover: Denver

## Challenge Notes
The county turnout requirement is not really clear. Without knowing the county total populations, the following cannot be determined:
- At first reading, I initially thought I was supposed to find out how many people chose not to vote. 
- Did Denver have the most active voters or simply had a higher population than the other two counties?
