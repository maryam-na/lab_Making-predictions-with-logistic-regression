In this lab, you will be using the Sakila database of movie rentals.

In order to optimize our inventory, we would like to know which films will be rented next month and we are asked to create a model to predict it.

Instructions
1- Create a query or queries to extract the information you think may be relevant for building the prediction model. It should include some film features and some rental features.
2- Read the data into a Pandas dataframe.
3- Analyze extracted features and transform them. You may need to encode some categorical variables, or scale numerical variables.
4- Create a query to get the list of films and a boolean indicating if it was rented last month. This would be our target variable.
5- Create a logistic regression model to predict this variable from the cleaned data.
6- Evaluate the results.