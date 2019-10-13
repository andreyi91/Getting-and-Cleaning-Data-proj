# Getting-and-Cleaning-Data-proj
Study Project for "Getting and Cleaning Data" course

File run_analysis.R:
1) read all the parts of data set using read.table() function
2) Bind XTrain and XTest data into one data frame (df)
3) Assign column names to df
4) Find out all the columns with "mean" and "std" in their names
5) Remove unwanted columns from dataset
6) Prepare "activities" vector merging Activity labels with names
7) Bind dats frame with subjects and activity names
8) Change feature names with sub() and rsub() functions
9.1) Using dplyr package group df data frame by subjects and activities
9.2) Summarize all features of df with mean() function
9.3) Add 'Avg' to the names of the features
10) Write new data frame to TidyDataAvg.txt file using write.table() function


CodeBook:
1. features  - data frame with names of features (file features.txt)
2. act_labels - data frame with names and labels of activities (file activity_labels.txt)
3. YTrain - data frame with labels of activities for train data (file Y_train.txt)
4. YTest - data frame with labels of activities for test data (file Y_test.txt)
5. SubjTrain - data frame with subject labels for train data (file subject_train.txt)
6. SubjTest - data frame with subject labels for test data (file subject_test.txt)
7. XTrain - data frame with features for train data (file X_train.txt)
8. XTest - data frame with features for test data (file X_test.txt)

9.  df - data frame fo collecting tidying all necessary data
10. fMeanStd - vector to collect feature names of "mean" and "std" data
11. activities - data frame to store activity names for all measures



