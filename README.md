# Getting-and-Cleaning-Data-Project course

## Purpose:

You should create one R script called run_analysis.R that does the following:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Steps to run analysis 

1. Download the data source and put into a folder on your working directory. You'll have a UCI HAR Dataset folder.
2. Download and put run_analysis.R in the same directory (working directory).
3. Run source("run_analysis.R"). It will generate a new file tiny_data.txt in your working directory.

## Dependencies:

1. reshape2
2. data.table

Make sure this dependencies was already installed using the command install.packages()
