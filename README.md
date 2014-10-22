CLEANING_DATA
=============

This is the ReadMe of the script run_analysis.R

Working directory is set
Start directory data is created and data.zip is downloaded from the given fileURL into a new directory project data
Data is extracted in the directory data
features.txt is cleaned up and read into data frame features_cleaned
feature names is got from features_cleaned
Create a vector varnames containing the variable names of the combined data set.
Load the files X_train.txt, X_test.txt and combine using rbind
Repeat for subject train and Y files
Combine the above three row binded data sets into combined_df data frame
Give names to the columns of combined_df
Extract the required variables of mean and standard deviation into selected_df
Each activity is labelled with descriptive activity labels.
Giving descriptive names to the variables in data set.
Melted the data set using melt for subject and actlabel
Created tidy data set using dcast
Written out tidy data set to a .txt file
