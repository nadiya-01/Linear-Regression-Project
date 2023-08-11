# Linear-Regression-Project
Exploratory Data Analysis (EDA):

*Loading libraries.
*Loading the housing dataset.
*Displaying dataset information such as shape, data types, and non-null information.
*Visualizing histograms of numerical columns.
*Creating a scatter matrix for selected attributes.
*Displaying missing value information.
*Visualizing the distribution of 'median_house_value' using a histogram.
*Creating a scatter plot of latitude and longitude colored by 'median_house_value'.
*Sorting the dataset by 'population' to identify potential outliers.
*Displaying a heatmap to visualize correlations among numerical features.

Linear Regression:

*Preparing the dataset by engineering new features ('avgrooms', 'avBedgrooms', 'pop_per_household') and transforming categorical features into dummy variables.
*Dropping unnecessary columns.
*Splitting the dataset into training and testing sets using train_test_split().
*Creating and fitting a Linear Regression model using LinearRegression().
*Handling missing values using SimpleImputer().
*Evaluating the model's performance using the score() function on both the training and testing data.
*Making predictions using the trained model.
