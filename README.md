# Election_Analysis

## Project Overview:
The election commison would like some additional information about the local election audit.
1. The voter turnout.
2. Calculate the percentage of votes for the counties.
3. Determine the winning county and get its vote count.

## Resources
-Data Source: election_results.csv

## Election Audit Results:
The election audit results indicate that:

- Jefferson county received 10.5% of the votes, the total of 38,855 number of votes.
- Arapahoe county received 6.7% of the votes, a total number of 24,801.
- Denver county received 82.8%  of the votes, and the total number of 306,055

The total amount of votes for the congressional election was 369,711.

The county that had the largest amount of votes was Denver, with 82.8% of the votes, a total number of 306,055. As shown in the data below, I was able to extract the data from the resource _election_results.csv_, from there create a calculation that would provide the data that gave me the results I wanted.

<img width="286" alt="image" src="https://user-images.githubusercontent.com/107371010/178828382-61314ed6-6edb-46e6-a61c-73cc1be71200.png">

## Electional Candidate Results:

There were three candidates in the running, the candidates were, Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane. 

- Charles Casper Stockham received 23.0% of the vote with a total number of 85,213 votes.
- Diana DeGette received 73.8% of the vote with a total number of 272,892 votes.
- Raymon Anthony Doane received 3.1% of the vote with a total number of 11,606 votes.

Based on the data, there is a clear indication Diana DeGette won the election, receiving 73.8% of the votes and a total number of 272,892 votes.

## Election-Audit Summary:

Using the resource _election_reults._csv_, I needed to extract and calculate the data that was necessary to provide that outcomes that the election commision requiered. In order to do so, I used the Software Python 3.6.1 and Visual Studio Code. The first step was to import the csv information into Python, as shown below:

<img width="452" alt="image" src="https://user-images.githubusercontent.com/107371010/178830326-40c3e50a-b2ff-44a6-beb0-f779e4af9304.png">

Then from there I needed to create dictionaries and lists of the data to start the process of creating the calculations, the image below is an example of the dictionaries and list:

<img width="332" alt="image" src="https://user-images.githubusercontent.com/107371010/178830854-a9bd16af-b015-4a49-9da8-48be06a1bd97.png">


Now is when the calculations needed to be conducted in order to calculate the requiered information, some examples of the calculations is shown below:

### Calculations for County outcomes:

<img width="599" alt="image" src="https://user-images.githubusercontent.com/107371010/178831382-c6d7906a-bf99-451d-90e8-78abdbb6033c.png">



### Calculations for Candidate outcomes:

<img width="485" alt="image" src="https://user-images.githubusercontent.com/107371010/178831752-89313a69-af49-48ab-b66d-ca6ade7a2e58.png">



After performing all of these tasks, the results are that the county with the largest turnout is Denver and the Candidate that won is Diana DeGette. 








##
