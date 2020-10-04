# Election_Analysis

## Overview of Election Audit:

An election recently held in the state of Colorado, is in need of being audited per the request of the election commission.  Traditionally, an audit such as this would be conducted through Excel.  In an effort to automate the audit and make it more easily applied to future elections, Python was used to import the election results from a CSV file and provide additional analysis of the results.

The written Python code, when exectued, provides the total number of votes, total number of votes for each candidate, the percentage of votes for each candidate, the winner of the election based on the popular vote.  In addition, the voter turnout for each county, the percentage of votes from each county, and the county with the highest turnout are also provided when the Python code is run.  All of this compiled information is then printed to a text file which has been formatted for easy reading and analysis of all of the aforementioned results.

## Election-Audit Results:

* A total of 369,711 votes were cast in this election.  Below is the breakdown of total votes for each county along with the percentage contribution to the total:
  * Jefferson County had 38,855 votes, making up 10.5% of the total.
  * Denver County had 306,055 votes, making up 82.8% of the total votes.
  * Arapahoe County had 24,801 votes, making up 6.7% of the total votes.
* Denver was the county with the highest voter turnout bringing in over 3/4 of all votes cast for this election.  
* There were three candidates running in this election, below is each candidate's performance:
  * Charles Casper Stockham received 85,213 votes which was 23% of the total.
  * Diana Degette received 272,892 votes which was 73.8% of the total.
  * Raymon Anthony Doanne received 11,606 votes which was only 3.1% of the total.
* The winning candidate was Diana DeGette.
  * She had 272,892 votes, 73.8% of all the votes cast.
  * Diana won by a landslide, the next closest candidate only brought in just over 85,000 votes.

## Election-Audit Summary:

As can be seen, Python has many strengths, one of them being the ability to take on the analysis of very large data sets and then quickly output requested/specific metrics in need of analysis to a separate document.  There are 369,712 rows of data within the CSV file from the election.  Though this could have been done through Excel's fucntions, Python provides more felxibilty for future applications and is less restricted regarding data set sizes.  

Though the Python code written provided the answers to questions requested by the election commission, there are some ways that this code could be modified for other elections.  For future elections, if a CSV file is similar in format to the one utilized in this analysis but has more rows of data, counties and candidates: this Python code can be easily applied to the new data set to provide similar analysis on voter turnout, county and candidate performance, and the winner of an election.    If information was needed regarding the vote make-up based on county for each candidate, an additional set of for loops could be introduced to provide the percentage of the candidate's votes that came from each county.  Initially this code was used to asses a county election but could also be used at the city or state level for other elections, including one for the Governor.  In the event that more voter data was provided which described the voter demographic (age, gender, ethnicity, etc.), for for loops and conditional statements can be added to the exisiting code to provide a more detailed description of not only where the votes came from but who submitted the votes.  Overall, the true tell of this code's adaptability is its ability to easily reference a larger data set with more votes, counties, and candidates in the same way these results were analyzed.

