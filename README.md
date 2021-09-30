# Election_Analysis

## Overview of Election Audit

The purpose of this analysis is to assist a Colorado Board of Elections employee in an audit of election results. The election results of interest are for a US congressional precinct. The data being used is a tabulated agglomeration of mail-in , punch cards, and direct recording electronic ballots. Typically, the analysis is performed using Microsoft Excel, but the process has now been automated using Python. The analysis provides total votes, votes by county, votes per candidate, and a winner of the election.

## Election Audit Results

The following is the summary of election outcomes for the US concressional precinct. This summary is output from the python script. Each outcome within the summary is further explained with areas of relavent python script.

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

In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.
1. Change input pathways for a new .csv data set
2. 
