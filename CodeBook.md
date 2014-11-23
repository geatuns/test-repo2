## CodeBook File for Getting & Cleaning Data Course Project Week 3
This file provides information about transformations and work performed in the script file "run_analysis.R"
FIle "run_analysis.R" is the instructions/script file delivered for the course project
The course project is a peer-assessment project 

Raw data files provided for the project at site:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

The following steps are performed by the script

### Obtain Raw data files
1.Download archive file with raw data sets
2.Extract data files from the downloaded archive

### Reads data sets into tables - Prepare with appropriate labels
1.Read varible lists
2.Read test data files into table structures
3.Appropriately labels the data set with descriptive variable names using gsub transforms on original variable lists
4.Read training data files into table structures
5.Appropriately labels the data set with descriptive variable names using gsub transforms on original variable lists


### Merge training & test data sets - Prepare with appropriate labels
1. Merge the training and the test sets to create one data set
2. Check the labels of the merged data set


### Extracts only the measurements on the mean and standard 
1. Create data set with only the measurements on the mean and standard deviation for each mesurement
2. Use descriptive activity names to name the activities in the data set


### Tidy Data set - Write to file to submit
1.From the data set in previous step, create a second, independent tidy data set with the average of each variable for each activity and each subject 
2.Write results into tidy file using write.table: tidyData.txt
