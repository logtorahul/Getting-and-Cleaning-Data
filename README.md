# Getting-and-Cleaning-Data
This Repo contains my Project assignment for Getting-and-Cleaning-Data

It has 
a) run_analysis.R : which has R code which cleans and create TidyData from Rawdata.
b) CodeBook :  which contains description of all the variables in the data set.

# How to run the project

1. Download data from 
 https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
2. Unzip and copy files in working directory
3. download and install packages (plyr, data.table, dplyr) in R : these pacakae have neccesay libraries required to run the project R Script
4. Execute script run_analysis.R

#run_analysis.R
run_analysis.R script will do following tasks
1.Merges the training and the test sets to create one data set.
2.Extracts only the measurements on the mean and standard deviation for each measurement. 
3.Uses descriptive activity names to name the activities in the data set
4.Appropriately labels the data set with descriptive variable names. 
5.From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject


