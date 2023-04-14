# Score_prediction


In this code, we are analyzing the relationship between the number of hours a student studies and their score percentage.

Firstly, we import some necessary libraries like pandas, numpy, and matplotlib. Then we read the data from a remote link using pandas and store it in a variable called "s_data". We then print the first 25 rows of the data using the head function to check if the data is properly imported.

Next, we plot a scatter plot of the number of hours studied versus the score percentage using matplotlib. We also create a histogram of the number of hours studied and the score percentage using matplotlib.

We then create a linear regression model using scikit-learn library. We split the data into training and testing sets using the train_test_split function. We then fit the training data to the model using the LinearRegression function.

After fitting the model, we plot a scatter plot of the training data and the predicted values using matplotlib. We also print the test data to see which values were used to test the model.

We then predict the percentage score for a student who studies 9.25 hours a day and print the result.

Finally, we evaluate the performance of the model using the mean absolute error and the r2 score.

In conclusion, this code helps us to understand how to build a linear regression model using scikit-learn library and how to evaluate the performance of the model.
