## Getting-and-Cleaning-Data-Project
=================================

* Unzip the source ( https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip ) into your workspace.
* Save run_analysis.R to your working directory.
* Run the command source("run_analysis.R") in Rstudio.
* This will run the R script, it will read the dataset and write these files:
merged_clean_data.txt -- 8.35 Mb, a 10299x68 data frame
data_set_with_the_averages.txt -- 0.225 Mb, a 180x68 data frame
* The first step is to merge the training and the test sets to create one data set.
* The second step is extracting only the measurements on the mean and standard deviation for each measurement.
* The third step is to name the activities in the data set using descriptive activity names.
* Then appropriately labels the data set with descriptive activity names.
* Then create a second, independent tidy data set with the average of each variable for each activity and each subject.
* Finally write the tidy data to a table using the command write.table(result, "data_set_with_the_averages.txt")
* Thus the tidy data set is created.


