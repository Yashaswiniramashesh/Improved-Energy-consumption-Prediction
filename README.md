# Improved-Energy-consumption-Prediction
The project focuses on improving energy consumption prediction through hyperparameter tuning, leveraging the XGBoost regression model and time series analysis techniques. The dataset used includes hourly energy consumption data (PJME_MW) from 2008 to 2016. Initial data preprocessing involved outlier removal and the creation of time-based features like hour, day of the week, month, and year. Additional lag features were introduced to capture historical trends for enhanced predictive capability.

A robust train-test split strategy using TimeSeriesSplit ensured sequential validation. Performance metrics included Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R², which evaluated model efficacy across multiple folds.

Hyperparameter tuning was performed using GridSearchCV to optimize parameters such as learning rate, maximum depth, minimum child weight, subsample, colsample_bytree, and number of estimators. The tuned model outperformed the baseline in most metrics, demonstrating improved predictive accuracy. For instance, the RMSE reduced from 3472.21 to 3321.01, and MAE decreased, enhancing the model's ability to generalize across test data.

The project emphasizes the significance of hyperparameter tuning in refining model performance and highlights the importance of advanced regression techniques and temporal feature engineering in time series forecasting tasks. These findings underscore the potential of data-driven approaches to enhance energy management and planning.
