# election-analysis

## Project Overview
I was requested by a Colorado Board of Elections employee to complete the following tasks in order to complete the election audit of a recent congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.8.8, Visual Studio Code, 1.60.2

## Results
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The counties who voted in this election were:
  - Denver County, which cast 306,055 votes (82.8% of total votes cast).
  - Jefferson County, which cast 38,855 (10.5% of total votes cast).
  - Arapahoe County, which cast 24,801 (6.7% of total votes cast).
- Denver County case the largest number of votes in this election, with their 306,055 total votes cast.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the votes and 85,213 number of votes.
  - Diana DeGette received 73.8% of the votes and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the votes with 11,606 number of votes.
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the votes with 272,892 number of votes.

### Outcomes of Election-Audit
![Election Results](Election_Results.png)

## Summary
This script could be used for any election, of any size or circumstance.

If someone wanted to see the breakdown of votes for homecoming king at a high school, this script could be used. All that would need to change are a few things. First, the data from which we pull would need to be the relevant data for who received votes to become the high school homecoming king for a specific year. Certain variable names would need to be altered to become more specific and appropriate to the election of homecoming king. Second, the messages our code writes into the output .txt file would need to be altered, again, to reflect the specific homecoming election going on. We could even breakdown the votes per class, those being the freshman, sophomore, juinor, and senior classes. We would simply need to alter the "county" lines of our code to become "classes" in lieu of "counties".

Similarly, we could alter this code to use it for votes cast for an all-star soccer game, per position. We would need various data files, with each one specifically conveying voting data for a specific position on the pitch. All in all, we would just run the code 11 times for 11 positions on the soccer field. Again, we would alter the label names in our code to reflect more appropriately what the votes were being cast for. But, the greater part of the code could remain untouched and it could do an excellent job displaying to us which players received the most votes from fans. Ultimately, we could fill a pitch of 11 poisitons, of individuals who received the greatest amount of votes per specific position they play for.
