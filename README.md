

# sta141b assignments
STA 141B: Data and Web Technologies for Data Analysis

## Assignment 1
The purpose of this assignment is to practice programming fundamentals: writing functions, if-statements, and loops. We'll get to more interesting and data science-y exercises in the next assignment

## Assignment 2
The purpose of this assignment is to practice using data frames to index, slice, reshape, aggregate, and group data.

#### Aquaculture Data Set 🐟🦐¶
The U.S. Department of Agriculture publishes data sets about U.S. food production online. In the next few exercises, you'll use the U.S. Aquaculture data set. The data set contains information about fish and shellfish imports and exports (more info here). The data set is published as a single Excel file

## Assignment 3
The purpose of this assignment is to practice using web APIs and combining data from multiple sources.

#### USDA Food Composition
The US Department of Agriculture publishes price estimates for fruits and vegetables online. The most recent estimates are based on a 2013 survey of US retail stores. We've cleaned and merged the fruit and vegetable price estimates for you. The result is the fresh.csv file included in the repository.

In this assignment, you'll combine the price estimates with nutrition data from the USDA Food Composition Databases, and then analyze the resulting dataset.

The USDA Food Composition Databases have a documented web API that returns data in JSON format . You need a key in order to use the API. Only 1000 requests are allowed per hour, so it's a good idea to use caching.

#### How can I improve?
* I should consider items with trace amount for Q1.4b, plenty of foods has 33 nurtients but many of them are only trace amount
* Make code more general

## Assignment 4
The purpose of this assignment is to practice scraping data from web pages.

#### The San Francisco Chronicle
In this assignment, you'll scrape text from The San Francisco Chronicle newspaper and then analyze the text.

The Chronicle is organized by category into article lists. For example, there's a Local list, Sports list, and Food list.

The goal of exercises 1.1 - 1.3 is to scrape articles from the Chronicle for analysis in exercise 1.4.

#### How can I improve?
* It would be a good idea to split the code in extract_data() into smaller functions for each item being scraped
* I could also specify the error to catch in except, otherwise the try-except block may catch errors you don't meant to catch

## Asignment 5
The purpose of this assignment is to practice querying databases with SQL.

#### Lahman's Baseball Database
In this assignment, you'll use SQL queries and pandas to explore data in Lahman's Baseball Database, which contains "complete batting and pitching statistics from 1871 to 2018, plus fielding statistics, standings, team stats, managerial records, post-season data, and more."

#### how can I improve?
I should consider the spread of distribution in Q1.1.4, why average is enough to represent all other teams?
