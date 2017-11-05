# getting_cleaning_data_project-

The R_script, run_analysis.R does the following:

1.	Download the dataset if it does not already exist in the working directory
2.	Loads the training and testing data into R keeping only the mean and std features from the original data set.
3.	Merges both the training and testing data into one dataset.
4.	Groups the data by subjects and the activities (convert to factors).
5.	Averages the data collected (the mean) for each subjects' activities.
6.	Exports the averaged data as "tidy_data.txt".


