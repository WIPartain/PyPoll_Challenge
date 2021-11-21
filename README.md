# PyPoll_Challenge

Module 3 challenge
## Overview
We have been tasked with providing additional information for the results of an election audit run by the Colorado Board of Elections.  After completing the initial audit, we were asked to provide the following information:
* The voter turnout for each county
* The percentage vote from each county out of the count total
* The county with the highest turnout.


## Election Audit Results
After running our code with the new changes, we yielded the following results
* Voter Turnout: There were 369,711 votes cast during this election
* Percentage Vote for each county: Jefferson Coutny had 10.5% of the votes, Denver county had 82.8% of the votes, and Arapahoe county had 6.7% of the votes
* The county with the highest turnout: Denver had far and away the largest voter turnout.
* Candidate Diana DeGette received 73.8% of the votes with 272,892 total votes.  Charles Casper Stockham received 23% of the votes with 85,213 total votes.  Raymon Anthony Doane received 3.1% of the votes with 11,606 total votes.
* Diana DeGette won the election with 73.8% of the votes and 272,892 total votes.

  ![PyPoll_Results](https://github.com/WIPartain/PyPoll_Challenge/blob/main/PyPoll_results.png)

## Election Audit Summary
The script used for this project can be modified for other elections. By importing a new CSV file, and cleaning the data to represent the candidate and county, no additional changes would need to be made. 
for example:
file_to_load = os.path.join( "resources_pathway", "example.csv")
file_to_save = os.path.join("analysis_pathway", "example.txt")

If the CSV contains the results from multiple elections in multiple states, you can create a new variable to select which election or which state needs to be analyzed. There would need to be a conditional which filters out candidates not in a particular election.


