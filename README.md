Getting and Cleaning Data Peer Assesment Project
================================================
Here are the steps to properly execute run_analysis.R script.
* 1 - Make sure you have data.table v1.9.4 installed.
* 2 - Make sure you have sqldf v0.4-10 installed.
* 3 - Unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip on your working directory.
* 4 - Source the script e.g: source(path/to/file/run_analysis.R) 
* 5 - The script will now do it's magic and provide the following:
  - filtered_data.txt : Means and Standards Deviations from all subjects's activities variables observations.
  - vars_avg_groupedby_subject_activity.txt : data containing the average measurement of Means and Standard Deviation grouped by Subject and Activity.
* 6 - Resulting data tables, filtered_data and vars_avg_groupedby_subject_activity, will remain in memory for further usage if necessary.