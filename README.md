# Election_Analysis

## Project Overview
The purpose of this analysis is to conduct a congressional election audit for the Colorado Board of Election.

## Audit Tasks to be Determined
1. The total number of votes cast.
2. A complete list of candidates who received votes.
3. The total number of votes and precentage of total votes each candidate received.
4. A breakdown of the number of votes and percentage of total votes for each county in the precinct.
5. The county with the largest voter turnout.
6. Determine the winner of the election based on popular vote.

## Results
The analysis of the election shows that:
- The total vote in the election was **369,711**.
- The counties:
    - Jefferson
    - Denver
    - Arapahoe
     
- The candidates:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
    
    
- The number and percentage of votes per county:

    Jefferson: **10.5%** of total vote with **38,855** votes.
    
    Denver: **82.8%** of total vote with **306,055** votes.
    
    Arapahoe: **6.7%** of total vote with **24,801** votes.
    
    
- The candidate results were:

    Charles Casper Stockham received **23.0%** of the total vote and **85,213** votes.
    
    Diana DeGette received **73.8%** of the total vote and **272,892** votes.
    
    Raymon Anthony Doane received **3.1%** of the total vote and **11,606** votes.
    
- The winner of the congressional election:
 
    Diana DeGette, who received **73.8%** of the total vote and **272,892** votes.
    
<img src="https://github.com/courtneysims/Election_Analysis/blob/9f23f2427923777e8712c55b0a4eaf34655f0058/Resources/Election%20Results.png" width="40%">
     
## Election-Audit Summary
The script can be modified to include additional breakdown of voter turnout and can be modified to analyze federal elections. The script for analyzing the counties can be modified to analyze states by reassigning the county variables to track states. It can also be modified to account for voter party affiliation should the data source include such data by adding a list and dictionary to the script and writing code blocks similar to those used for analyzing the county votes. 

<img src="https://github.com/courtneysims/Election_Analysis/blob/9f23f2427923777e8712c55b0a4eaf34655f0058/Resources/county_vote_script.png" width="50%">

<img src="https://github.com/courtneysims/Election_Analysis/blob/9f23f2427923777e8712c55b0a4eaf34655f0058/Resources/county_tracking_script.png" width="50%">

### Resources
Data Source: election_results.csv

Software: Python 3.9.7, Visual Studios Code, 1.65.2
