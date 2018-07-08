# Code Book for Getting and Cleaning data project
  Please note that you may refer to tidy_data.txt to see the data set.

# Identifiers:

* Subject - ID number of the subject, integer range 1 to 30
* Activity - the activity of the subject when the measurement was done

## Activities include the following:

* WALKING : subject was walking during the test
* WALKING_UPSTAIRS : subject was walking up a staircase during the test
* WALKING_DOWNSTAIRS : subject was walking down a staircase during the test
* SITTING : subject was sitting during the test
* STANDING : subject was standing during the test
* LAYING : subject was laying down during the test 

# Transformations
  Some transformations to the raw data are the following:

* Merges the training and the test sets to create one data set.
* Extracts only the measurements on the mean and standard deviation for each measurement.
* Uses descriptive activity names to name the activities in the data set
* Appropriately labels the data set with descriptive variable names.
* From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
