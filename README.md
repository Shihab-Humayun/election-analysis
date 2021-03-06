# Election_Analysis

## Project Overview
The purpose of this election audit analysis is to implement for loops and conditional statements with membership and logical operators to find results requested by the election commission. The additional data requested to complete the audit are to find the voter turnout for each county, the percentage of votes from each county out of the total count, and the county with the highest turnout. After finding these information, the results will then be printed out onto a .txt file.

## Results

* How many votes were cast in this congressional election?

The total number of votes that were casted in this congressional election is 369,711 votes.

* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

Out of the total number of votes casted for the congressional election, Denver had 306,055 votes, which made 82.8% of the total votes. Denver had the largest voting turnout out of all the other counties. The second highest voting turnout was from the county Jefferson with 38,855 votes. This made only 10.5% of the total votes. The lowest voting turnout was from the county Arapahoe with 24,801 votes. This was 6.7% of the total votes from the congressional election. The following picture shows the result that supports the analysis.

![Screenshot (4)](https://user-images.githubusercontent.com/49353083/111043056-73ac1c80-840e-11eb-8abb-4f747f775ada.png)

* Which county had the largest number of votes?

The county with the largest number of votes is Denver, which made up 82.8% of the total votes.

* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

The number of votes that Charles Casper Stockham received from the congressional election is 85,213 votes that makes up 23% of the total votes casted. Diana DeGette received 272,892 votes that made up 73.8% of the total votes. Raymon Anthony Doane received 11,606 votes that makes up 3.1% of the total votes. The following picture shows the result that supports the analysis.

![candidates](https://user-images.githubusercontent.com/49353083/111043443-8e7f9080-8410-11eb-9647-96dbe19aa0e5.png)


* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

The candidate that won the election is Diana Degette. She received 272,892 votes, which was 73.8% of the total votes.

## Summary

The script that I have created can be implemented to future elections with a few modifications. This code is ideal because it has empty lists and dictionaries which is showed from the picture below. 

![Screenshot (6)](https://user-images.githubusercontent.com/49353083/111043835-d1dafe80-8412-11eb-96fd-22b21a76ed36.png)

One way to modify this Python code is by creating a state list and state votes dictionary and analyze the total number of votes were made by states. It can be written as 

state_list = []

state_votes = {}

The total number of votes would be the sum of votes from all of the states. Another way to modify the code is by adding different level of officials. For example, having a list and dictionary made for mayors, House of Representatives, and other elected officials. The code would consist of having variables that has the winning candidate, the total votes from that candidate, and the percentage from the total vote from that cadidate. The declaration of these lists and dictionaries will be similar to the picture provided:

![Screenshot (7)](https://user-images.githubusercontent.com/49353083/111044201-1bc4e400-8415-11eb-99cb-ca11251d910d.png)
