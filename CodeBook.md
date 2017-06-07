### Code Book For run_analysis.R

The purpose of this project is to collect, work and clean a data set. The goal is to prepare tidy data that can be used for later analysis.

## Source Data

The source data is available at the link:

[Source Data] (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)

Further details about this data can be found at:

[Human Activity Recognition Using Smartphones](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

## R Script

Actions performed by "run_analysis.R" 


1. Merging the train and test datasets to create a single data set:
	Download the Data file from the given URL and unzip the files.
	Reading files including Train,Test,Feature,Activity
	Rename the columns with meaningful names
	Merge all the data in one dataset

2. Extracting only the measurements on the mean and standard deviation for each measurement
	Reading all the column names
	Create vector for defining ID, mean and standard deviation
	Making nessesary subset from the merged dataset

3. Creating a second, independent tidy data set with the average of each variable for each activity and each subject
	Creating second tidy data set ("secTidySet")
	Writing second tidy data set into "secTidySet.txt" file


Using descriptive activity names to name the activities in the data set and Appropriately labeling the data set with descriptive variable names have been taken care at the earlier steps.

## Variables used

- x_train,y_train,x_test,y_test,subject_train,subject_test contains the data read from the source file
- x_data,y_data,subject_data contrains the merged data of both test and train
- featurs have the proper names for the x_data dataset which are used to rename the columns appropriately.

