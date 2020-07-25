# Getting-and-cleaning-data
Course project - Coursera
In the first part of the script, "Merges the training and the test sets to create one data set", the aim is at aggregating the separate files in order to have three variables, which are "Features", "Subject" and "Activity". The result is that we have merged the training and the test sets to make up one data set. So, it was necessary to concatenate the data tables by rows, give names to the variables and, finally, merge columns to form the "Data" data frame, containing all data.

In the second part, "Extracts only the measurements on the mean and standard deviation for each measurement", the aim is at having a data that shows the mean and standard deviation according to Names of Features. In order to do that, we got the subset Name of Features by measurements on the mean and stardard deviation, subset the data frame from step 1 (Data) by selected Names of Features.

In the third part, "Uses descriptive activity names to name the activities in the data set", the aim is at factorizing the variable "Activity" according to activityLabels provided by the downloaded file ("activity_labels.txt").

In the fourth part, "Appropriately labels the data set with descriptive variable names", the aim is at providing full name to the abbreviated variable names. In this sense, Acc is replaced by accelerometer, gyro is replaced by gyroscope, mag by magnitude and so forth. 

In the fifth part, "From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject", the aim is at forming a new data set, the so-called tidy data, and besides that, it contains the average of each variable for each activity as well as each subject built on the former data set. 
