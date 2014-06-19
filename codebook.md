## Code Book

Source of the original data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip .

Original description: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The attached R script (run_analysis.R) performs the following to clean up the data:

* Merges the training and test sets to create one data set, namely train/X_train.txt with test/X_test.txt -- the result is a 10299 x 561 data frame, as in the original description ("Number of Instances: 10299" and "Number of Attributes: 561")

train/subject_train.txt with test/subject_test.txt -- the result is a 10299 x 1 data frame with subject IDs,

train/y_train.txt with test/y_test.txt -- the result is also a 10299 x 1 data frame with activity IDs.

* 
