## CodeBook File - Getting & Cleaning Data Course Project Wk 3
This file provides information about transformations and work performed in the script file "run_analysis.R"
FIle "run_analysis.R" is the instructions/script file delivered for the course project
The course project is a peer-assessment project 

Raw data files provided for the project at site: See raw data site on project instructions page.

The following steps are performed by the script

### Obtain Raw data files
* Download archive file with raw data sets
* Extract data files from the downloaded archive

### Reads data sets into tables - Prepare with appropriate labels
* Read varible lists
* Read test data files into table structures
* Appropriately labels the data set with descriptive variable names using gsub transforms on original variable lists
* Read training data files into table structures
* Appropriately labels the data set with descriptive variable names using gsub transforms on original variable lists


### Merge training & test data sets - Prepare with appropriate labels
* Merge the training and the test sets to create one data set
* Check the labels of the merged data set


### Extracts only the measurements on the mean and standard 
* Create data set with only the measurements on the mean and standard deviation for each mesurement
* Use descriptive activity names to name the activities in the data set


### Tidy Data set - Write to file to submit
* From the data set in previous step, create a second, independent tidy data set with the average of each variable for each activity and each subject 
* Write results into tidy file using write.table: file "tidyData.txt" uploaded to Coursera web site
