# ACM Research coding challenge (Fall 2022)

- Trained a machine learning model to predict some aspect of a car based on other information from its listing.
- Made a graph to visualize car make's and their prices

## Trained A Machine Learning Model To Predict The Prices of cars
- Data was read into the program
- Unnecessary characters like "$" and "," were removed from the Price coloumn and converted to float to help the model predict car prices
- Dropped coloumns with missing data
- Selected coloumns with a low cardinality to increase performance
- Checked the dtypes of all the useful coloumns to make sure there were all floats
- Checked to see if they were any missing values
- One hot encoded the train predictors
- Removed rows with missing target data and separated the target from predictors
- Broke off validation set from training data
- Selected categorial columns with low cardinality and kept the selcted coloumns.
- Define the model with XGBRegressor
- Fitted the model
- Got the model's predictions 
- Calculated the Mean Absolute Error and got 3335.7002



## No collaboration policy

**You may not collaborate with anyone on this challenge.** You _are_ allowed (and encouraged) to use internet documentation. If you use existing code (either from Github, Stack Overflow, or other sources), **please cite your sources in the README**.

## Timing
