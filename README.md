# Pypoll with Python

## Overview of Project

The purpose of this project was to add these features to a Python script for auditing elections: measure the voter turnout for each county, calculate the percentage of votes from each county out of the total count, and determine the county with the highest turnout.

## Election-Audit Results

*369,711 total votes were cast in the election.
*Denver had 306,055 votes(82.8%). Jefferson had 38,855 votes(10.5%). Arapahoe had 24,801 votes(6.7%).
*Denver was the county with the most votes.
*Diana DeGette received 272,892 votes(73.8%). Charles Casper Stockham received 85,213 votes(23.0%). Raymon Anthony Doane received 11,606 votes(3.1%).
*Diana DeGette won the election with 272,892 votes, representing 73.8% of the total vote count.
![Screenshot of results](/resources/results.png)

## Election-Audit Summary

This Python script would work as-is for any state-level election with the results in the same format (first column: ballot number, second column: county, third column: candidate). For a city-level election, we would have to change any mentions of "county" to "district" or "community" in the output statements, but otherwise the script would be the same. For a national (ie presidential) election, we would have to track voting totals in each state separately, and then determine a winner by allocating the electoral college votes from each state.