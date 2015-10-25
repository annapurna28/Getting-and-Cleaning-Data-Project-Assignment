## Getting-and-Cleaning-Data-Project-Assignment

## run_analysis.R

This R script performs the following steps, as per the project assignment instructions:

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive activity names.
Creates a second, independent tidy data set with the average of each variable for each activity and each subject

## how to run the analysis

1. Assume that all the data has been down loaded and kept in the working directory. 
2. Load the script in the R invironment - source('run_analysis.R')
3. Create one output folder in working directory
4. The end result will be a file called final_tidy_dataset.txt' in the output folder.

## final tidy dataset
Each row in the final, clean dataset contains subject, activity, and measures for all required features (i.e., mean or standard deviation)
