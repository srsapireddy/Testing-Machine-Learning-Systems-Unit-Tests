# Testing-Machine-Learning-Systems-Unit-Tests

•	Developed Unit Test Cases for Machine Learning Model functions for testing input data, feature engineering, model prediction quality, and model configuration.
-	Input Data Testing: Created a schema and specified maximum and minimum values each variable can take to test input data ranges and types.
-	Data Engineering: Updated the pipeline with new functionality to preprocess the data by applying a scaler with unit tests. This brings the x train to mean near zero and standard deviation near zero for preprocessing.
-	Model Prediction Quality: Employed benchmarking tests for model prediction quality, checking model accuracy against a simple benchmark and differential test to check model accuracy from one version to the next.
-	Model Configuration: Updated the pipeline class. The configuration for the model is passed in as an argument when the pipeline object is instantiated, and the tested configuration is validated against the optimal configuration parameters.
