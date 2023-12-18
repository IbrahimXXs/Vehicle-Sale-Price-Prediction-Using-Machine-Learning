# Bulldozer Sale Price Prediction using Machine Learning

## Overview:

### *This project focuses on predicting the sale prices of bulldozers using machine learning techniques, specifically employing the RandomForestRegressor model. The aim is to leverage characteristics and historical examples to estimate the future sale prices of bulldozers accurately.*

#### Datasets:

Train.csv: The training set containing data through the end of 2011.

Valid.csv: The validation set with data from January 1, 2012, to April 30, 2012. Predictions on this set contribute to the public leaderboard score.

Test.csv: The test set, released in the last week of the competition, covering data from May 1, 2012, to November 2012. Scores on this set determine the final competition rank.

#### Features:

The dataset includes various features such as SalesID, MachineID, ModelID, YearMade, MachineHoursCurrentMeter, UsageBand, Saledate, Saleprice, and numerous others providing details about the bulldozer's characteristics, usage, and sale information.

Data preprocessing involved converting categorical data into a NumPy category and filling missing values based on the median.

#### Characteristics and Features:

*The dataset encompasses a wide range of characteristics and features, including:*

* Machine configuration

* Machine usage information

* Sale date and price
  
* Product description and grouping
  
* State in which the sale occurred

* Engine specifications

* Hydraulics and implement interfaces

* Operator control configurations

*And many more

#### Libraries Used:

The project utilized the following Python libraries:

* NumPy

* Pandas

* Matplotlib

* Scikit-Learn

* The RandomForestRegressor model was employed to make predictions about bulldozer sale prices. The model was fine-tuned using RandomizedSearchCV to optimize its performance.

#### Usage:

To explore the project, clone the repository and run the provided Python script. Make sure to have the necessary libraries installed

#### License:

This Project  Was Fully Coded by Ibrahim Sarraj

This project is licensed under the MIT License.

Contributions, feedback, and issue reports are welcome. Happy predicting!

