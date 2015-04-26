# Getting-and-Cleaning-Data-Coursera
-----------

This file describes how run_analysis.R script works.
* First, unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip.
* Install package `plyr`, if it's not installed. 
* Make sure run_analysis.R script are in the same directory of the dataset.
* Second, use source(`run_analysis.R`) command in RStudio. 
* Third, you will find output files are generated in the current working directory:
  - `average_data.txt` (220 Kb): independent tidy data set with the average of each variable for each activity and each subject.
