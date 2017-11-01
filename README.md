# getcleandata

This repo was created to finish assignment for Week 4 of the Getting and Cleaning Data Coursera course.
First, download and unzip the data file into your R working directory.
Second, download the R source code into your R working directory.
Finally, execute R source code to generate tidy data file.

##Data description
The code combined a training dataset and a test dataset involving sensor signals from smartphones for specific physical activitie 
(walking, standing, laying, etc.), and extracted partial variables
to create another dataset with the averages of each variable for each activity.

##New dataset
The new generated dataset contained variables calculated based on the mean and standard deviation. Each row of the dataset is an average 
of each activity type for all subjects.

##The code was written based on the instructions of the assignment
Read training and test dataset into R environment. Read variable names into R envrionment. Read subject index into R environment.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each 
subject.
