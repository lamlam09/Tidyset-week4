# Tidyset-week4

4 different files: 
README.md, codebook.md, run_analysis.R, tidy_data.txt

I. download and unzip the data file into R working directory.
II. download the R source code into your R working directory.
III. execute R source code to generate tidy data file.

Data description
full: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Code explaination
The code grouped together the training dataset and test dataset, and extracted partial variables to create another dataset with the averages of each variable for each activity.

New dataset
It contained variables calculated based on the mean and SD. Each row is the mean of each activity type for all subjects.

Following steps involved to create datasets.
I. Read files
II Assigning names to variables
III Merging all data into one dataset
IV. Extracting only the measurements on the mean and SD
V. Reading variable names
VI. Create vector for defining ID, mean and SD
VII. Making nessesary subset from merged data set
VIII. Name the activities in the data set with descriptive activity
IX. Appropriately labeling the data set with descriptive variable names
X. Creating another data set with the average of each variable for each activity and each subject
XII. Making second tidy dataset
XIII. Writing second tidy data et in txt file
XIV. The code assumes all the data is present in the same folder, un-compressed and without names altered.
