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
- Selected categorial columns with low cardinality and kept the selcted coloumns
- Define the model with XGBRegressor
- Fitted the model
- Got the model's predictions 
- Calculated the Mean Absolute Error and got 3335.7001911458333
## Build A Bar Graph Based On The Each Car's Make and Price
- Data was read into the program
- Constructed the dimensions of the bar graph
- Selected ten random car make's and price's
- Selected random colors to add to each bar 
- Created the x and y-axis and labeled them as Make and Prices
- Set the font size to 12
- A bar graph with various colors and and information was created
- 

[![alt text](http://url/to/Bar Graph(Make Vs. Price).png)
](https://github.com/abiolaalalade/ACM-Research-coding-challenge-22F/blob/main/Bar%20Graph(Make%20Vs.%20Price).png)

## Sources
- https://www.kaggle.com/code/dansbecker/xgboost/notebook
- https://www.kaggle.com/code/ankitkuls/xgboost-with-one-hot-encoding/notebook
- https://www.kaggle.com/code/abiolaalalade/exercise-xgboost/edit
