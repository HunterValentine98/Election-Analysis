# Election Analysis With Python

## Overview of Election Audit
Tom and Tom's manager, Seth, have tasked us with a few  data values they need calculated for an election audit coming from  voters' Ballot ID, county they are voting in, and the candidate they voted for. We are originally tasked with finding five data values that we need to retrieve from the whole data set. These consisted of: The total number of votes cast, a complete list of candidates who received votes, the percentage of votes each candidate won, the total number of votes each candidate won, and the winner of the election based on popular vote. From here, Seth and Tom requested further analysis, including: the voter turnout of each county, the percentage of votes from each county out of the total votes, and the county with the highest turn out. Below are our results for Seth and Tom!


## Election Audit Results
![Election Outcome](Resources/Election_Outcome.png)

Based on our analysis, we were able to crunch the data into the following data above. 
- We were able to calculate the total number of voters to be 369,711.
- Our county votes display the total amount of votes from each county and what percentage of votes came from each county when compared to the total votes.
  For example, Denver had 306,055 votes placed within its county, which came out to be a total of 82.8% of all votes placed in this election.
- The most votes came from Denver County, displaying next to the Largest County Turnout.
- Similar to the County votes section, we created a section showing every candidate that received votes, how many votes they received, and what percentage of the total     votes they ended up receiving. For instance, Charles Casper Stockham received 85,213 votes, which ended up being 23% of the total votes that were casted.
- Lastly, our program show who ended up winning the election, the amount of votes they received, and what percentage of the total votes they received.
- Diana DeGette seems to be the election winner by a long shot. She received a total of 272,892 votes, while second only received 85,312. Her percentage of the total       votes received was 73.8%, followed by Stockham with 23% 


## Election Audit Summary
- In summary, this program can be sent to the election commission for analysis of future elections as well. Under "file_to_load = os.path.join( ".", "Resources", "election_results.csv")", you would simply change "election_results.csv" to whatever data comes from the new election!
- Don't forget in "file_to_save = os.path.join("analysis", "election_analysis.txt")" to change "election_analysis.txt" to a new text file name that you would like to create for the new election results.

