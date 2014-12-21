
Getting_and_Cleaning_Data
=========================
This is a repository for the code written for the course project of Getting and Cleaning Data Coursera course through Johns Hopkins University.

Course Project

Unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder 

Change the variable “a” in the code to the location of UCI HAR Dataset folder

In RStudio run the run_analysis.R file
Use data <- read.table("data_set_with_the_averages.txt") to read the data. It is 180x68 because there are 30 subjects and 6 activities, thus "for each activity and each subject" means 30 * 6 = 180 rows. 

