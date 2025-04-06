Predicting Digital Marketing Conversion Utilizing ML Flow in Databricks

We utilized ML Flow to log various ML models that were built where campaign and customer attributes were used to predict whether or not 
digital marketing advertisement led to conversion.

Data: This dataset provides a comprehensive view of customer interactions with digital marketing campaigns. 
It includes demographic data, marketing-specific metrics, customer engagement indicators, and historical purchase data. 
https://www.kaggle.com/datasets/rabieelkharoua/predict-conversion-in-digital-marketing-dataset

Model: After analyzing the data and performing feature selection techniques (Chi-squared, Kruskal-Wallis), the relevant features
were passed into AutoML to give us insight on which models to test off the bat. We then did some more pre-processing on the data to standardize it 
and account for the imbalance in the target variable and tested out different ML models utilizing Random Search for hyperparameter tuning. All model results
were logged on ML Flow to give us insight on the different metrics/results of the different model versions.

Result: 95.6% F1 Score
