# getting-clean-data
Downloading the file
Unzipping the file
About Variables:
x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.
x_data, y_data and subject_data merge the previous datasets to further analysis.
features contains the correct names for the x_data dataset, which are applied to the column names stored in

How code works:
Reading in the files and merging the training and the test sets to create one data set.
Reading files
Reading trainings tables
Reading testing tables
Reading feature vector
Reading activity labels
Assigning variable names
Merging all data in one set
Extracting only the measurements on the mean and standard deviation for each measurement
Reading variable names
Create vector for defining ID, mean and standard deviation
Making nessesary subset from merged data set
Using descriptive activity names to name the activities in the data set
Appropriately labeling the data set with descriptive variable names
Creating a second, independent tidy data set with the average of each variable for each activity and each subject
Making second tidy data set
Writing second tidy data set in txt file
