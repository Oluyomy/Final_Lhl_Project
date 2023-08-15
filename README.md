# Final_Lhl_Project
## Introduction:
weather forecasting has evolved significantly over the years with the utilization of Machine Learning (ML) to enhance the accuracy and efficacy of predictions.
Machine learning effectiveness is  largely derived from the fact that it can be trained on various data sources, like weather station data, satellite imagery, and radar data.
In this project, data for  Calgary was derived from NOAA using  the airport as the base station  has 94% data coverage accuracy.
## Project  Goals
-
- The ultimate goal of this project, is to ensure models were fed with data that allowed us to understand the relationship between different weather variables and subsequently make more accurate predictions. 
- Make 3, 7, 14 & 90 days weather predictions.
- To perform cross-validation for the purpose of validating and enhancing model accuracy, the model's predicted outcomes are contrasted with the real-world weather conditions to ascertain improvements.
- Make 3,7,14, 90 days prediction of weather features.

## Step 1: Obtaining data
This dataset is from National Oceanic and Atmospheric Administration (NOAA) API:
[weather Dataset]( https://www.ncdc.noaa.gov/cdo-web/webservices/v2)

Step 2: Loading and understanding the dataset.
- Working with uptodatecalgary.csv data to understand  each feature in the dataset.
- Having a general understanding and information about the relationship between various features .

Step 3: Exploratory data analysis and pre-processing 
- clean the data sets, analyze and visualize the relationships between the different variables, handle missing values and outliers.
- Create a displot, histplot,Densityplot, scatterplot and pairplot to look at the distributions of different variables and their correlation.
- summary statistics such as mean, median, and standard deviation for each column of the dataset. 
- Learn the trend and detect outlier or possible factor that can affect the data output.
- Create heatmap to take a closer look at the corellation.
- Detect and handle outliers.
- Structure the data for efficient analysis.
- Split the into training and testing for appropriate training .
- Scale the data 

Step 4:  Model: Ridge regression, Decision tree,Randomforest Regressor, GradientBoostingRegressor,Support Vector Regression,Time series analysis.
step 5: Model evaluation
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R-squared (R2)
- Cross validation

## Results
Based on these matrics, the Ridge Regression Metrics appears to perform slightly better than the Linear Regression model in terms of both MSE and MAE, while also having a slightly higher R-squared value. This suggests that the Decision Tree Regression model might capture the underlying patterns in this data more effectively. however,we also experiment with other regression algorithms like RandomForestRegressor and GradientBoostingRegressor to see which one performs better for this dataset.Although  Ridge regression model was used for the prediction because of its ability to penalizes coefficients to account for multi-collinearity; it is important to further analyze and  explore feature engineering, hyperparameter tuning, cross-validation, more data cleaning and consider the broader context of this analysis before making a final decision.

## conclusion
Based on Machine learning’s ability to offer enhanced accuracy and timely weather predictions,it bring about improvement in various domain including public safety, effective resource allocation, efficient disaster response, increased agricultural output, and valuable insights into the study of climate change. 
 ## Challenges
- Complex Data:The data contains multiple predictor variables that interact with each other, this maked identifying  the most critical variables for modelling and forecasting a challenge. 
- Uncertainty: The possibility of imprecise measurements maked weather forecasting inherently uncertain. In turn, this uncertainty maked it tougher to build accurate ML models and effective weather forecasts. 
- Data Quality: machine learning accuracy is dependent on the quality and quantity of input data. Although the data was obtained from an API whose data was 94% accurate,however, data completeness and up-to-date can be tricky. 
- Interpretation  of weather forecasting are often complex  and hard  because ofa lots of parameters attached to the prediction which may in turn build lack of trust in models.
- Time constrain.
## Future goals
- I will  used data from other weather APIs for better comparison.

