# README
#Describes How the script works

This repository hosts the R code and documentation files for the Data Science's track course "Getting and Cleaning data", available in coursera.
 +
 +The dataset being used is: (http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)
 
 +## Files
 1. Download the dataset into the working directory
 2. Load activity and feature info
 3. Load the training and test datasets, keeping only those columns which reflect a mean and standard deviation
 4. Merges the two datasets
 5. Creates a tidy dataset that consists of the means of each of the variables
 +
 +The code takes for granted all the data is present in the same folder, un-compressed and without names altered.
 +
 +`CodeBook.md` describes the variables, data and any transformations performed to clean up the data.
 +
 +`run_analysis.R` contains code to perform the analyses described in the steps outlined above. They can be 
 launched in RStudio by reading the file in.
 +
 +The output of the step 5 is called `tidy.txt`, and uploaded in the course project's form.
