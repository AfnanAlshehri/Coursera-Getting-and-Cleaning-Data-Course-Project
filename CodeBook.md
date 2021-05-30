CodeBook
================
Afnan Alshehri
5/30/2021

# Getting and Cleaning Data - Course Project

### Processing

  - Creating a single data set by combining the training and test sets
    and extracting only the mean and standard deviation measures for
    each measurement.

  - To name the activities in the data collection, we used descriptive
    activity names.

  - Using descriptive variable names to appropriately label the data
    collection.

  - Making a separate tidy data set with the average of each variable
    for each activity and each subject.

### Variables

  - features \<- features.txt : 561 rows, 2 columns The features
    selected for this database come from the accelerometer and gyroscope
    3-axial raw signals tAcc-XYZ and tGyro-XYZ.

  - activities \<- activity\_labels.txt : 6 rows, 2 columns List of
    activities performed when the corresponding measurements were taken
    and its codes (labels)

  - s\_test \<- test/s\_test.txt : 2947 rows, 1 column contains test
    data of 9/30 volunteer test subjects being observed

  - x\_test \<- test/X\_test.txt : 2947 rows, 561 columns contains
    recorded features test data

  - y\_test \<- test/y\_test.txt : 2947 rows, 1 columns contains test
    data of activities’code labels

  - s\_train \<- test/subject\_train.txt : 7352 rows, 1 column contains
    train data of 21/30 volunteer subjects being observed

  - x\_train \<- test/X\_train.txt : 7352 rows, 561 columns contains
    recorded features train data

  - y\_train \<- test/y\_train.txt : 7352 rows, 1 columns contains train
    data of activities’code labels
