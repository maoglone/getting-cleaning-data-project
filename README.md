getting-cleaning-data-project
=============================

Class project from Coursera's Getting & Cleaning Data course.

Repo for the submission of the course project for the Johns Hopkins Getting and Cleaning Data course.

### Overview

This project serves to demonstrate the collection and cleaning of a tidy data set that can be used for subsequent analysis. A full description of the data used in this project can be found at [The UCI Machine Learning Repository.](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

[The source data for this project can be found here.](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)

### Modifying the script

Download and unzip the source files. You'll need to make one modification to the R file before you can process the data. On line 26 of run_analysis.R, setwd() to relect the location of the source files in your own directory.

### Project summary

The following is a summary description of the project instructions

You should create one R script called run_analysis.R that does the following: 
1. Merges the training and the test sets to create one data set. 
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set 
4. Appropriately labels the data set with descriptive activity names. 
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Additional Information about the code, data, and manipulations exist in this repo's CodeBook.MD file.
