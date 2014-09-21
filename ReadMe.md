Data Clean Course Assignment
The script run_analysis.R produces a tidy data set (tidyDataSet) from raw data collected from the Human Activity Recognition Using Smartphones project. A full description is available at the site where the data was obtained: 

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

Raw data for the project can be downloaded from here:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

The data must be downloaded to the R working directory and then unzipped into the R working directory maintaining the file structure in the zip file 
The R script run_analysis.R does the following. 
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
The output is a txt file written to the R working directory (tidyDataSet.txt)
 
