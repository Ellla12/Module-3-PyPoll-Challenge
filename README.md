# Module 3: PyPoll Challenge
## Overview of Election Audit
Through this module, we help a Board of Elections employee, Tom, audit the  tabulated results for the US Congressional precinct in Colorado. From the analysis, we are helping Tom report the following:
- Total Votes Overall
- Total Votes for Each Candidate
- Percentage of Vote for Each Candidate
- Winner of the Election

Furthermore, through the module challenge, we are adding the following to the analysis:
- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the highest turnout

## Election-Audit Results
![Election Results](https://github.com/Ellla12/Module-3-PyPoll-Challenge/blob/main/Resources/election_results.PNG)
- How many votes were cast in this congressional election?
Total Votes: 369,711

- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
<br>Jefferson: 10.5% (38,855)
<br>Denver: 82.8% (306,055)
<br>Arapahoe: 6.7% (24,801)

- Which county had the largest number of votes?
<br>Denver

- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
<br>Charles Casper Stockham: 23.0% (85,213)
<br>Diana DeGette: 73.8% (272,892)
<br>Raymon Anthony Doane: 3.1% (11,606)

- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
<br>Diana DeGette
<br>Vote Count: 272,892
<br>Percentage: 73.8%

## Election-Audit Summary
The benefit of the Election-Audit script is that it can be adjusted and used for different elections. The current script only tabulates results for Colorado, but this can be modified and used for other states or any election that the commission is overseeing.

Furthermore, this scripts reads from csv files, so election results are not hard-coded into the script. This means that it is very simple to analyze election results with the current script. To do that, they'll just have to formulate a similar csv file.
