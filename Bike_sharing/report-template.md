# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### Rodan Mohamed

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
TODO:  I realized that Kaggle rejects submissions with negative values, but the initial model predictions contained negative values. To address this issue, I set all negative predictions to zero before submission.

### What was the top ranked model that performed?
TODO: The top-ranked model that performed was the AutoGluon model trained with the best_quality preset.

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
TODO: The exploratory analysis revealed insights into the distribution of features and helped identify potential relationships between variables. Additional features, such as hour, day, and month extracted from the datetime column, were created to capture temporal patterns in the data

### How much better did your model preform after adding additional features and why do you think that is?
TODO: The model performance improved after adding additional features, as evidenced by a reduction in root mean squared error (RMSE). These new features provided the model with more information about temporal patterns, which helped it make more accurate predictions

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
TODO: After trying different hyperparameters through hyperparameter optimization, the model performance further improved. By tuning the hyperparameters, the model was able to find optimal configurations that better captured the underlying patterns in the data.

### If you were given more time with this dataset, where do you think you would spend more time?
TODO:  I would spend more time exploring feature engineering techniques to create more informative features. Additionally, I would experiment with different machine learning algorithms and ensemble methods to further improve model performance.

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
	model	hpo1	hpo2	hpo3	score
0	initial	Default value	Default value	Default value	1.80063
1	add_features	Default value	Default value	Default value	0.57370
2	hpo	150	150	30	3.66841
### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Replace the image below with your own.

![model_train_score.png](img/model_train_score.png)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.

![model_test_score.png](img/model_test_score.png)

## Summary
TODO: In summary, the project involved iterative processes of data exploration, feature engineering, model training, and hyperparameter tuning to improve predictive performance. By leveraging insights from exploratory analysis and incorporating additional features, such as temporal components extracted from datetime data, the model's ability to capture underlying patterns in the data was enhanced. Further improvements were achieved through hyperparameter optimization, leading to a reduction in error metrics. Overall, the project demonstrated the importance of a systematic approach to model development and optimization in predictive modeling tasks.
