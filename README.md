Introduction:
The goal is to prepare tidy data that can be used for later analysis.

The data source will be: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
And its explanation could be found: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Transformation done by run_analysis.R:
1. Merge the training and the test sets to create one data set.
step 1: download zip file from website
step 2: unzip data
step 3: load data into R
step 4: merge train and test data

2. Extract only the measurements on the mean and standard deviation for each measurement.
step 1: load feature name into R
step 2: extract mean and standard deviation of each measurements

3. Uses descriptive activity names to name the activities in the data set.
step 1: load activity data into R
step 2: replace 1 to 6 with activity names

4. Appropriately labels the data set with descriptive variable names.

5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
