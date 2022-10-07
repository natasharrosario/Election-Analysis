# Election Analysis
Election Results Automated with Python

# Overview of Election Audit
## Purpose

The purpose of this challenge was to assist a board of elections employee in an election audit of the tabulated results for a U.S. congressional precinct in Colorado. This was done by reporting the total number of votes cast, the percentage of votes for each candidate, and the winner of the election based on popular vote. Additionally, the election commission requested additional information about the voter turnout for each county in the dataset, as well as the percentage of votes from each county out of the total count. Lastly, we were asked to identify the county with the highest voter turnout. The data for this analysis was collected using mail-in-ballots, punch cards, and DRE counting machines, and was then used to determine the final election results. The goal of this project was to find a way to automate the auditing process using Python so that the code could be used by not only other congressional districts, but also senatorial districts and local elections. 

# Election Audit Results
The results of this election audit show that:

* There were 369, 711 votes cast in the election.

### County Statistics

* Three counties participated in this election:
  * Jefferson County
    * Voters from Jefferson County made up 10.5% of the total voter turnout, casting 38, 855 votes.
  * Denver County
    * Voters from Denver County made up 82.8% of the total voter turnout, casting 306,055 votes.
  * Arapahoe County
    * Voters from Arapahoe County made up 6.7% of the total voter turnout, casting 24, 801 votes.

* The county with the highest voter turnout was Denver County. 

### Candidate Statistics

* The candidates in this election were:
  * Charles Casper Stockham
  * Diana DeGette
  * Raymon Anthony Doane
  
* The candidate results were:
  * Charles Casper Stockham received 23% of the vote with 85,213 votes.
  * Diana DeGette received 73.8% of the vote with 272, 892 votes.
  * Raymon Anthony Doane received 3.1% of the vote with 11, 606 votes. 

* The winner of the election was Diana DeGette, who recieved 74% of the vote with 272, 892 votes.

# Election Audit Summary

## Recommendations

With a few modifications, this script can be used for any election in any state; the dataset would simply have to be altered in order match the election you are seeking to audit. This would entail changing the candidate and county names, as well as the ballot IDs. For local elections where county information is not needed, you could measure a different category, such as neighborhoods or boroughs. For national elections that require more information, one would only need to add additional columns to the dataset, and repeat the code as needed to collect information about the new variable, such as "State" or "Political Party", and the number of votes and the percentage of the total votes in that category.  
