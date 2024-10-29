# Linear-Regression-Health-Cost-Calculator

1.	Objective:
      Use a dataset containing information about individuals to predict healthcare costs.
	
2.	Data Preparation:
      	•	Import necessary libraries and the dataset.
      	•	Convert categorical data to numeric values.
      	•	Split the data into training (80%) and testing (20%) datasets.
       
3.	Feature and Label Separation:
      	•	Pop off the “expenses” column from the dataset to create new datasets:
      	•	train_labels and test_labels: use these labels when training your model.
4.	Model Training:
	      •	Create and train a regression model using train_dataset.
5.	Model Evaluation:
      	•	Run the final cell to evaluate your model’s performance using the unseen test_dataset.
	      •	Ensure model.evaluate() returns a Mean Absolute Error (MAE) of under $3500.
6.	Prediction and Visualization:
	      •	The final cell will predict healthcare expenses using the test_dataset and plot the results.
