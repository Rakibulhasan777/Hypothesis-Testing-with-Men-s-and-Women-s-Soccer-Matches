# Hypothesis-Testing-with-Men-and-Women-Soccer-Matches 

## Project Overview 
This Data Analysis project aims to Perform an appropriate hypothesis test to determine the p-value, and hence result, of whether to reject or fail to reject the null hypothesis that the mean number of goals scored in women's international soccer matches is the same as men's by using a 10% significance level.
The question I am trying to determine the answer to is:

> Are more goals scored in women's international soccer matches than men's?

I assume a **10% significance level**, and use the following null and alternative hypotheses:

$H_0$ : The mean number of goals scored in women's international soccer matches is the same as men's.

$H_A$ : The mean number of goals scored in women's international soccer matches is greater than men's.


## The Data
While scoping this project, I acknowledge that the sport has changed a lot over the years, and performances likely vary a lot depending on the tournament, so I decide to limit the data used in the analysis to only official `FIFA World Cup` matches (not including qualifiers) since `2002-01-01`. I create two datasets containing the results of every official men's and women's international football match since the 19th century, which I scraped from a reliable online source. This data is stored in two CSV files: `women_results.csv` and `men_results.csv`. 

## Prerequisites
  * Python 3.6 or higher [Download Here](https://www.python.org/downloads/)
  * Pandas
  * Matplotlib
  * Pingouin
  * Mannwhitneyu

## Steps to complete 
  * Exploratory data analysis
  * Filtering the data
  * Choosing the correct hypothesis test
  * Performing the hypothesis test
  * Interpreting the result of the hypothesis test

## Results/ Findings
|P Val| Result|
|-----|--------|
|0.005106609825443641| reject|
