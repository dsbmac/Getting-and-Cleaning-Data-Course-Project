=================================================================
Getting and Cleaning Data Project
=================================================================

Denis Mach
Coursera, Getting and Cleaning Data
=================================================================

The values shown are mean calculations on a selected set of variables from the Human Activity Recognition Using Smartphones Dataset Version 1.0.

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The original data are accelerometer and gyroscope data, captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. This data was collected for 30 test subjects during 6 different possible activities.

From the original data a subset of mean and standard deviation values were chosen for all subjects and activities. The mean was subsequently calculated on the subset and grouped by subject and activity.

To run the script, the unzipped data files from the original study must be inside the local folder.

For each record it is provided:
======================================

- mean 
- standard deviation
- A 86-feature vector with time and frequency domain variables. 
- Its activity label. 
- An identifier of the subject who carried out the experiment.


The dataset includes the following files:
=========================================
README.md
codebook.md
run_analysis.R