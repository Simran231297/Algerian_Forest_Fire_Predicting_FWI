Data Analysis of Algerian Forest Fire Dataset to predict FWI using Multiple Linear Regression

Dataset columns: Date : (DD/MM/YYYY) Day, month ('june' to 'september'), year (2012) Weather data observations Temp : temperature noon (temperature max) in Celsius degrees: 22 to 42 RH : Relative Humidity in %: 21 to 90 Ws :Wind speed in km/h: 6 to 29 Rain: total day in mm: 0 to 16.8 FWI Components Fine Fuel Moisture Code (FFMC) index from the FWI system: 28.6 to 92.5 Duff Moisture Code (DMC) index from the FWI system: 1.1 to 65.9 Drought Code (DC) index from the FWI system: 7 to 220.4 Initial Spread Index (ISI) index from the FWI system: 0 to 18.5 Buildup Index (BUI) index from the FWI system: 1.1 to 68 Fire Weather Index (FWI) Index: 0 to 31.1 Classes: two classes, namely Fire and not Fire Region: two values 0 and 1

Model Performance:

• All regression models achieved relatively high R-squared values, indicating good explanatory power of the models. The R-squared values range from 0.912 to 0.927, suggesting that between 91.2% to 92.7% of the variance in forest fire severity can be explained by the independent variables included in the models.
• The mean squared error (MSE) and mean absolute error (MAE) vary among the models but generally indicate reasonable predictive accuracy, with lower values indicating better performance.
• The Elastic Net Regression model achieved the lowest MSE (4.144) among all models, indicating the lowest average squared difference between predicted and actual values.

Strengths and Recommendations:

• Despite the variations in performance between training and unseen data, the regression models still demonstrate valuable predictive capabilities and offer insights into forest fire severity prediction.
• To improve generalization to unseen data, model refinement strategies such as feature selection, regularization, and cross-validation should be considered.
