# Election_Analysis

## Overview of Election Audit:

### Why are we doing this?
This project helps Tom, who works for the Colorado elections board with a summary of the results for a U.S. congressional precinct in Colorado. The results summarize the total number of votes cast in each county, the total number of votes for each candidate, the percentage of votes for each candidate, and the winner of the election based on the popular vote, including the county with the most votes cast. 
### Why use Python when we have data formated for Excel
This task is usually done in Excel, but Tom's manager wants to know if there's a way to automate the process using Python. If this audit is done successfully with Python, the code you and Tom write will be used to audit not only other congressional districts, but also senatorial districts and local elections.

### What types of votes are being counted?
There are three primary voting methods that you and Tom will take into account, mail-in ballots, punch cards, and direct recording electronic, or DRE, counting machines. Mail-in ballots are typically hand counted at the central office. Punch cards are collected and then fed into a machine that tabulates vote totals and sends the results to the central office. Finally, memory cards from DRE counting machines are sent to the central office and read by a computer. Tom's manager, Seth, would like him to become familiar with the command line, so we are providing a Python script that will both produce a text file that Tom can electronically provide to his manager as well as results on the terminal (command line).

### what do the total votes and winners tell us?
Altogether, the votes cast by these three methods will determine the final election results. After the votes are counted, your job is to generate a vote count report to certify this U.S. Congressional Election. 


## Election-Audit Results:
The following results were found:
* there were a total of 369,711 votes cast in this U.S. Congressional Election for the 3 counties.

* Here are the rsults for each county:
  Jefferson County: 38,855 votes were cast, which is 10.5% of the total vote
  Denver County: 306,055 votes were cast, which is 82.8% of the total vote
  Arapahoe County: 24,801 votes were cast, which is 6.7% of the total vote
  
* Denver, with the largest population, had the largest number of votes, or 82.8% of the votes

* For the 3 Candidates, here are their totals and percentages of the total vote:
  Charles Casper Stockham got 85,213 votes or 23% of the total vote
  Diana DeGette got 272,892 votes which is 73.8% of the total vote. She is the winner.
  Raymon Anthony Doane got 11,606 votes which is 3.1% of the vote.
  
  Please see this image of the results:
  [Summary of Counties and Candidate Results](analysis/election_analysis.png) 

## Election-Audit Summary
In Conclusion, this new Python script can be used to process any csv election file containing the number of votes for each candidate for each county in the data. You can use this for election data for the entire state if you have the number of votes for each county for each candidate. The program is flexible enough to add as many counties and candidates as necessary. It gives a summary report when run in the terminal but at the same time, the program writes out a text file with the results that you can send as needed by email or place on a website.
[Summary of Counties and Candidate Results in a Text File](analysis/election_analysis.txt) 

