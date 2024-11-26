# ICP-4
Data manipulation and linear regression

Recording Code Walkthrough: https://drive.google.com/drive/folders/1jP5daYRfUjMhn4edOn1mkOak7pQbD63_?usp=share_link

1. Data Manipulation
  Read the provided CSV file ‘data.csv’.
  Basic statistical description about the data.
  Checked if the data has null values.
  Replaced the null values with the mean
  Selected two columns and found aggregate the data using: min, max, count, mean.
  Filtered the dataframe to select the rows with calories values between 500 and 1000.
  Filtered the dataframe to select the rows with calories values > 500 and pulse < 100.
  Created a new “df_modified” dataframe that contains all the columns from df except for
  “Maxpulse”.
  Deleted the “Maxpulse” column from the main df dataframe
  Converted the datatype of Calories column to int datatype.
  Created a scatter plot for the two columns (Duration and Calories).
  
2. Linear Regression 
  Import the given “Salary_Data.csv”
  Split the data in train_test partitions, such that 1/3 of the data is reserved as test subset.
  Training and predicting the model.
  Calculated the mean_squared error
  Visualized both train and test data using scatter plot
