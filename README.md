Getting and Cleaning Data Peer Assesment Project
================================================
Here are the steps to properly execute run_analysis.R script.
* 1 - The script was tested and executed under R version 3.1.2 (2014-10-31) "Pumpkin Helmet"
* 2 - Make sure you have data.table v1.9.4 installed.
* 3 - Make sure you have sqldf v0.4-10 installed.
* 4 - Unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip on your R environment working directory.
* 5 - Source the script, source(path/to/file/run_analysis.R) 
* 6 - The script will now do it's magic 
	- Join test and train data provided by the files downloaded
	- Discard unnecessary data collection
	- Rename original columns to improve readability
	- Put data scattered throught out downloaded files into a single data table.
* 7 - and provide the following:
  - data.txt : Means and Standards Deviations from all subjects's activities features observations.
  - features_avg_groupedby_subject_activity.txt : data containing the average measurement of Means and Standard Deviation grouped by Subject and Activity.
* 8 - Resulting data tables, data(10299 observations of 68 variables) and features_avg_groupedby_subject_activity(180 observations of 68 variables), will remain in memory for further usage if necessary.