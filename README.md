---
output:
  pdf_document: default
  html_document: default
---
# Project Title: 4th Down Decision Advisor
Group-10 project for DSCI445 @ CSU

## Required R Packages
Make sure to have these packages installed: `dplyr, nflfastR, ggplot2, tidyverse, tidyr, janitor, randomForest, xgboost, vip, caret, readr, knitr, tidymodels, kableExtra, and ranger.`

## How to Run the Code
Start in the `EDA and Cleaning` folder and run everything from top to bottom in the `EDA and Cleaning` rmd file. Running this code and loading all the initial plays may take a few minutes.
Then transition back to the `Model Work` folder and open `GoForItPlays_from_modelwork_s` rmd file and run all the code from top to bottom as well. This run time also may make a few minutes, mostly for the random forest model and fitting the different models to find the best model in chunk #7.

# Disclaimer
Our issues like discussed in the first string of emails were do to commit issues with members of the group working in the same person's branch. 
The second problem we later had, had to do with Read-Only and Writing and executing privileges. As of now all group members are able to access 
and Read everything. Only Andrew (the branch owner) is currently able to make changes to all files. Previously when emailing first, other members 
were unable to do anything, but this was later discovered to be a bug. If for some reason you are unable to open or view or run the code due to 
what is likely this issue, we have a backup ready to go right away. andy34@colostate.edu