# Election_Analysis

## Project Overview
### Purpose
The purpose of this project was to, under the easiest and fastest way, get the results into a election. In this case the analysis was focused in a county election.

The analysis ask us to get the next points:
1. Calculate the total number of votes.
2. Calculate the total number of votes and share for each county.
3. Get the county with the highest participation.
4. Get a complete lists of candidates who recieved votes.
5. Calculate the total number of votes each candidate received.
6. Calculate the percentage of votes each candidate won.
7. Determine the winner of the election based on popular vote.

## Results
### Analysis Results
The analysis of the election show that:
- The final votes count was of: 369,711 into the counties of Arapahoe, Denver and Jefferson.
![image](https://user-images.githubusercontent.com/96214489/150704232-88387ca6-07f2-414d-9efc-a9637b4f4300.png)

- The share of votes in the counties was:
    - 10.5% for Jefferson county with a total of 38,855 votes.
    - 82.8% for Denver county with a total of 306,055 votes.
    - 6.7% for Arapahoe county with a total of 24,801 votes.
- Being Denver the county with the largest count of votes

![image](https://user-images.githubusercontent.com/96214489/150704341-38191233-8b6f-485e-8561-88b064b9adc6.png)


- The candidates were:
    - Charles Casper Stockham,
    - Diana DeGette, and
    - Raymon Anthony Doane
- And the results were:
    - Charles Casper Stockham received 23.0% of the votes and 85,213 number of votes.
    - Diana DeGette received 73.8% of the votes and 273,892 number of votes.
    - Candidate 3 received 3.1% of the votes and 11,606 number of votes.
- The winner of the election was:
    - Diana DeGette, who eceived 73.8% of the votes and 273,892 number of votes
     
 ![image](https://user-images.githubusercontent.com/96214489/150704630-f81d356d-0a47-4900-8f06-0a2b10e7003b.png)

## Summary
This script was made to get the count of votes from small group of counties in the United States, I don't know the electoral structure of the united states, but I assume  that there are so many mores counties in the country and perhaps there regions, zones, quarters, etc.
The way this script could be used is as base of something bigger, if the only way to get the total votes is counting each one them, perhaps the data base could increase the quantity of columns by adding, as I mention, the region, zones and quarters. Adding some extra lines in the code could get the results for every part we want to know.

I think that one way that this script could be modified is that instead of being connected with a data base stored in my computer, the script connect with a data base in the cloud via SQL query. That would help to get the information almost in real time and not to wait to get or download the entire information.

Also, looking that getting the results of the candidates and the counties is very similar (by no to say that is the same), perhaps the lines of code could be less if we add some conditions at the beggining, the result would chance depending on what they want to look: county summary, candidates summary, region summary, all, etc. This would help if this script was used in any election. 

     
