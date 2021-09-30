# Election_Analysis

## Overview of Election Audit

The purpose of this analysis is to assist a Colorado Board of Elections employee in an audit of election results. The election results of interest are for a US congressional precinct. The data being used is a tabulated agglomeration of mail-in , punch cards, and direct recording electronic ballots. Typically, the analysis is performed using Microsoft Excel, but the process has now been automated using Python. The analysis provides total votes, votes by county, votes per candidate, and a winner of the election.

## Election Audit Results

A total of 369,711 votes were counted in this congressional election. Jefferson, Denver, and Arapahoe counties are the three counties within this precint. Denver county had the majority of votes cast in the precint with 82.8% of total votes. The three candidates that recieved votes were Charles Casper Stockham, Diana Degette, and Ryman Anthony Doane. The analysis ultimately found Diana DeGette to be the winning candidate with 73.8% of the vote. The following includes an overall summary of election and further information on how each outcome was calculated using Python. 

* Election Resutls Summary

  ![Election_Results](/Analysis/election_results.png)

  ![Complete_Python_Script](/PyPoll_Challenge.py)

* Total Votes Cast

  ![Total_Votes](/Analysis/total_votes.png)
  
  ![PYTotal_Votes](/Analysis/py_total_votes.png)
  
  The data for total votes and the rest of the analysis comes from a .csv file. A *for* loop is used to count votes row by row. The total count for this variable is displayed as     total votes. 
  
* County Breakdown  

  ![County_Breakdown](/Analysis/county_breakdown.png)
  
  ![PYCounty_Breakdown2](/Analysis/py_county_breakdown2.png)
  
  ![PYCounty_Breakdown1](/Analysis/py_county_breakdown.png)
  
  An *if not in* statement is used to add each county to the list of counties. Votes are then tallied by county as a *for* loop is used. The percentage of votes from each county   is calculated within this for loop as well.
  
* Largest County Turnout

  ![County_High_Votes](/Analysis/largest_county_vote.png)
  
  ![PYCounty_High_Votes](/Analysis/py_winning_county.png)
  
  The county with the largest voter turnout is determined using an *if and* statement that selects the county with the highest vote count.
  
* Candidate Breakdown  

  ![Candidate_Breakdown](/Analysis/candidate_breakdown.png)
  
  ![PYCandidate_Breakdown2](/Analysis/py_candidate_breakdown2.png)
  
  ![PYCandidate_Breakdown1](/Analysis/py_candidate_breakdown.png)
  
  The candidate breakdown is performed in a very similar way as the county breakdown. An *if not in* statement and a *for* loop are used to add candidate names, tally votes, and   to calculate percent of the total vote.
  
* Winning Candidate  

  ![Winning_Candidate](/Analysis/winning_candidate.png)
  
  ![PYWinning_Candidate](/Analysis/py_winning_candidate.png)
  
  The winning candidate is calculated in a very similar way as the county with the largest voter turnout. An *if and* statement is used to determine the candidate with the         highest vote count.


## Election Audit Summary

All in all, the election audit was a success. Using this python script allows for a fast and accurate, count and summary of results. With a different data set, a similar analysis can be performed. If the .csv file that holds the raw ballot information maintains the same column format, this python script can be used for future election and other precints. Because of the way the script is written other counties or candidates can be used, and a very similar *Election Results* text file will be generated. Not only can the counties and candidates names change, but a larger or smaller amount of each will not be an issue. To run other precints in the future will require a change to the pathway that opens the .csv file, if the file name is changed. A similar pathway change will be needed for other elections that have a different .csv file name. Pathways can also be changed if there is a desire to hold the .csv file in a different loacation. Inputs are not the only pathways that can be modified. If a different location or file is desired for the output summary, this can be modified by using a different pathway. Based on the speed, accuracy, and summary of results, full recommendation is given to the Election Commission to use this python script for future audits.

In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.
1. Change input pathways for a new .csv data set
2. 
