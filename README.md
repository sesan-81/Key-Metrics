# Key-Metrics

Predictive Analytics Evaluation Report: Cyclist Traffic Models

Abstract

This report presents a comprehensive evaluation of two predictive models created to forecast cyclist traffic. The models, based on Random Forest Regressor and Gradient Boosting Regressor algorithms, were meticulously developed and assessed to predict the total cyclists variable using a dataset encompassing various environmental factors. The evaluation involved calculating key metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-Squared (R2). Furthermore, the actual vs. predicted values were visualized to gain insights into the models' performance. This report sheds light on the comparative analysis of these models, providing valuable information for decision-making in urban planning.


Data Preparation

The dataset was meticulously prepared, encompassing features like date, day, temperature, and rainfall. Dates were transformed into numerical values, ensuring compatibility with the predictive models. Missing data was handled judiciously, and categorical variables were appropriately encoded.

Model Development

Two powerful algorithms, Random Forest Regressor and Gradient Boosting Regressor, were employed for model development. These models were trained on a subset of the data and evaluated using the remaining data to ensure their predictive accuracy.

Model Evaluation

Key Metrics Calculation Definition

●	Mean Squared Error (MSE): Measures the average of the squared differences between actual and predicted values. Both models exhibited low MSE values, indicating accurate predictions.

●	Root Mean Squared Error (RMSE): Represents the square root of MSE, offering insight into the magnitude of prediction errors. Both models demonstrated low RMSE values, indicating precise predictions.

●	Mean Absolute Error (MAE): Calculates the average absolute differences between actual and predicted values. Both models exhibited low MAE values, reflecting accurate predictions.

●	R-Squared (R2): Measures the proportion of the variance in the dependent variable that is predictable from the independent variables. Both models showed high R2 values, indicating their ability to explain the variance in cyclist traffic data.

Key Metrics Calculation

Random Forest Regressor Metrics:

●	MSE: 738304.46
●	RMSE: 859.25
●	MAE: 709.17
●	R2: 0.9208
Gradient Boosting Regressor Metrics:

●	MSE: 383235.31
●	RMSE: 619.06
●	MAE: 436.07
●	R2: 0.9589


Visualizations

Scatter plots were created to visualize the actual vs. predicted values for both Random Forest Regressor and Gradient Boosting Regressor models. These visualizations provided a clear understanding of how well the models aligned with the actual data points.

Comparative Analysis

Both models performed exceptionally well, showcasing their effectiveness in predicting cyclist traffic. While both models exhibited similar accuracy metrics, slight variations were observed in their predictions. The comparative analysis highlighted the models' strengths, enabling a nuanced understanding of their respective capabilities.

Conclusion

In conclusion, the Gradient Boosting Regressor proved to be the superior model, achieving a higher R2 value and lower error metrics than the Random Forest Regressor. Both models, however, exhibited strong predictive capabilities, emphasizing their utility in urban planning and policymaking. The models' accuracy can significantly aid decision-making processes related to cyclist traffic management and infrastructure planning.

