# Election_Analysis
## Overview of Election Audit
A Colorado Board of Elections employee requires an audit of a recent local election.  In order to have a successfull audit, he has requested to:
1. Calculate the total amount of votes
2. Find the list of candidates, their respective quantity of votes, and their respective percent of votes.
3. Determine the winner of the election based on popular votes
4. find the list of counties, their respective voter turnout, and their respective percent of voter turnout.
## Election-Audit Results
Based on the election data and our analysis we were able to determine the following: 
Election Results
1. Total Vote count was 369,711
2. Vote details per county are as follows:
    1. Jefferson:10.5% (38,855)
    2. Denver:82.8% (306,055)
    3. Arapahoe:6.7% (24,801)
3. County with Largest Turnout was Denver
4. Election results per candidate are as follows: 
    1. Charles Casper Stockham: 23.0% (85,213)
    2. Diana DeGette: 73.8% (272,892)
    3. Raymon Anthony Doane: 3.1% (11,606)
5.  Election Winner was Diana DeGette:
    1. The Winning Vote Count: 272,892
    2. The Winning Percentage: 73.8%
-------------------------
## Election-Audit Summary
The election audit audit script used to analysis the election data can be used to audit any election other results.  In order to use the script on another election, two minor changes will have to be made to the script. 
The first minor change is to update the file path locations and the file names of both the file with the data and the file with the output. (![Lines_to_update_for_NewElection1.PNG](C:\Users\rdsm1\Documents\GitHub\Election_Analysis\Resources\Lines_to_update_for_NewElection1.PNG)). 
The second minor change is to update the column index, this will only have to be updated if the election csv file's column data headers are in a different order.  ((![Lines_to_update_for_NewElection2.PNG](C:\Users\rdsm1\Documents\GitHub\Election_Analysis\Resources\Lines_to_update_for_NewElection2.PNG)))
