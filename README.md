# NHL Statistical Analyses

This project is part of the Flatiron School Data Science Fellowship requirements.

# Slide Deck

https://docs.google.com/presentation/d/1SUyliAcehcWRUGnE2pYFd1p6wEPfNhvfAiF5YMmV85M/edit?usp=sharing

# Project Discussion

Using goals and points statistics from NHL players from 1940-2017, this project aims to (1) determine the significance of a player's decline after the age of 30 and (2) determine correlations between the 2005-06 offseason rule changes and increased goal scoring across the 30 teams of the National Hockey League.

## Collaborators

- Buddy Bernhard
- Irving Campbell

## Methods Used

- Paired t-tests
- Cohen's d meta-analysis

## Technologies

- Python (SciPy, Seaborn)

## Project Description

### TWO SETS OF HYPOTHESES TO BE ADDRESSED BY THIS ANALYSIS

### 1. It is said that after age 30, a player becomes "too old" for hockey.  But is that really true?  We form our null and alternative hypotheses to be:

H0: In comparing the point totals from the seasons when an NHL forward turns 30 and when that same NHL forward turns 31, there is either no difference or net positive change in points scored by the forward in the later season.

Ha: In comparing the point totals from the seasons when an NHL forward turns 30 and when that same NHL forward turns 31, there is a net negative change in points scored by the forward in the later season.

### 2. In the 2005-06 offseason, some changes were made to the rulebook.  It is known that these changes were made in an attempt to increase scoring in the league.   We form our null and alternative hypotheses to be:

H0: There is no statistically significant difference between teams' goals scored per game between the season before rule change (2003-2004) and the season after the rule change (2005-2006).

Ha: There is a statistically significant difference between teams' goals scored per game between the season before rule change (2003-2004) and the season after the rule change (2005-2006).

## Sources:

- NHL player stats at http://inalitic.com/datasets/nhl%20player%20data.html 
- NHL team stats through the NHL's REST API
