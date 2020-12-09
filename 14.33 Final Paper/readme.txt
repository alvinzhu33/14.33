Data: directory to store all source data and data through the data processing procedure



Data\Source Data: directory to store all source data

Data\Source Data\States: directory to store all the tweet IDs of the U.S. separated into the 50 states and D.C.

Data\Source Data\Affinity - State - Daily.csv: file for data about the changes in consumer spending

Data\Source Data\COVID - State - Daily.csv: file for data about COVID cases

Data\Source Data\Employment Combined - State - Daily.csv: file for data about changes in employment levels

Data\Source Data\GEOIDs - State.csv: file for data about states

Data\Source Data\Google Mobility - State - Daily.csv: file for data about changes in time spent outside

Data\Source Data\Policy Milestones - State.csv: file for data about dates of stay-at-home orders



Data\Data Processing: directory to store all the files created during the data processing procedure

Data\Data Processing\State Batches: directory to store batches of polarity scores for hydrated tweets

Data\Data Processing\covid.csv: processed COVID - State - Daily.csv file

Data\Data Processing\employment.csv: processed Employment Combined - State - Daily.csv file

Data\Data Processing\final.csv: aggregation of all the data that I have. Will use this file to run my regression on

Data\Data Processing\outside.csv: processed Google Mobility - State - Daily.csv file

Data\Data Processing\policy.csv: processed Policy Milestones - State.csv file

Data\Data Processing\spend.csv: processed Affinity - State - Daily.csv file

Data\Data Processing\stateCount.csv: table linking state to the amount of tweets collected from that state. Used to make figure in paper

Data\Data Processing\tweets.csv: aggregation of polarity scors for every single tweet I have in my database.

Data\Data Processing\wordsFreqNeg.csv: file storing the most common words found in tweets with negative (unhappy) sentiments

Data\Data Processing\wordsFreqPos.csv: file storing the most common words found in tweets with postive (happy) sentiments

Data\Data Processing\TwitterHydration.ipynb: Python script to hydrate my dataset of tweet IDs. Also creates word cloud graphs

Data\Data Processing\Data Processing.ipynb: Python script to compile all my data into the final.csv file



Data\Analysis: directory to store all data for Analysis

Data\Analysis\Graphs and Quick Facts.ipynb: Python script for calculating fast facts about the COVID-19 pandemic and several graphs

Data\Analysis\Policy Incorporation.ipynb: Python script to create dummy variables for my 30-day window around a stay-at-home order. This creates the analysis.csv file

Data\Analysis\analysis.csv: file of all the data needed for my event study diff-in-diff regression. Will pass this into 14.33 Final Analysis.Rmd

Data\Analysis\14.33 Final Analysis.Rmd: R script to run my event study regression and secondary regression. Also creates the graphs for these results