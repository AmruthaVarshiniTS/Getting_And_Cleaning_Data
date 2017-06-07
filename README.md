# Getting and Cleaning Data

This file conatins all the relevent information about the repository Getting_And_Cleaning_Data.

## Getting_And_Cleaning_data

This repository contains all the files related to the assignment for the "Getting and Cleaning Data" course.

The contents include:
- Data files downloaded form the provide URL
- run_analysis.R script file, containing the R Script
- CodeBook.md conating all details about the "run_analysis.R" file
- secTidyset.txt contains the cleaned data

## Data:
Conatins the various source files, that are unzipped and are further used in "run_analysis.R" as input.

## run_analysis.R:

Conatins the R code that:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set.
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each   subject.

## CodeBook.md:

Conatins details about how variables, data, and any transformations were performed to clean up the data in "run_analysis.R".

## secTidyset.txt:
Conatins the data set with the average of each variable for each activity and each subject, which is created by the "run_analysis.R".
