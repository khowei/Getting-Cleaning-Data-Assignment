The purpose of this project is to demonstrate my ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. 


In order for run_analysis.R script to work.
1. Unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and rename the folder with "data".
2. Make sure the folder "data" and the run_analysis.R script are both in the current working directory.
3. Use source("run_analysis.R") command in RStudio. 
4. There will be two output files are generated in the current working directory: ?merged_data.txt (7.9 Mb): it contains a data frame called cleanedData with 10299*68 dimension.
?data_with_means.txt (220 Kb): it contains a data frame called result with 180*68 dimension.
5. Use data <- read.table("data_with_means.txt") command in RStudio to read the file.