# PythonReport1
Titanic_Train analysis

This code takes all of the data from the titanic_train csv file and analyzes it.

After importing all dataframes and libraries:

The first histogram shows a distribution of ages

The pie chart shows a distribution of people in each class, along with that labels on the pieces of the pie the amount of people per each class

The scatter plot shows the relationship between fare price and total family size. I derived total family size by just adding the SibSp and Parch colums together to get total # of family brought aboard. There's a regression line and r^2 value as well included in the code.

Next I calculated the corr scores of the dataset, and made a figure for it

I combed through Titanic_Train, removing any missing values from Survived and Pclass, then created a contingency table and chi square test of the table.

I then broke the three ports into seprate dataframes (Q, S and C), then took the percentages of every class at each port, which gave me some surprising insight.

