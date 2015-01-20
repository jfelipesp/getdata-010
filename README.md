Getting and Cleaning Data Peer Assesment Project
================================================
Here are the steps to properly execute run_analysis.R script.
1 The script was tested and executed under R version 3.1.2 (2014-10-31) "Pumpkin Helmet"
2 Make sure you have data.table v1.9.4 installed.
3 Make sure you have sqldf v0.4-10 installed.
4 Source the script, source(path/to/file/run_analysis.R) 
5 The script will now do it's magic 
  - Download needed data ZIP file.
	- Join test and train data provided by the files downloaded.
	- Discard unnecessary data collected.
	- Rename original columns to improve readability.
	- Put data scattered throught out downloaded files into a single data table.
6 And provide the following:
  - features_avg_groupedby_subject_activity.txt : data containing the average measurement of Means and Standard Deviation grouped by Subject and Activity.
7 Resulting data tables, data (10299 observations of 68 variables) and features_avg_groupedby_subject_activity (180 observations of 68 variables) will remain in memory for further usage if necessary.