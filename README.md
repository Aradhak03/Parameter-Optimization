# Parameter-Optimization

This project demonstrates the optimization of Support Vector Machine (SVM) on the Dry Bean dataset obtained from the UCI Machine Learning Repository. The dataset contains instances of seven different varieties of dry beans, with 16 features describing each instance.

## Dataset 
The Dry Bean dataset consists of 13611 instances, with each instance having 16 features. The dataset is divided into 10 different samples for training and testing.

## Implementation
Loading the Dataset: The dataset is loaded from a CSV file using the pandas library.

Splitting the Dataset: The dataset is split into training and testing sets with a 70-30 ratio, repeated 10 times to get 10 different samples.

Optimizing SVM: SVM is optimized for each sample using cross-validation with 100 iterations. GridSearchCV is used to find the best hyperparameters.

Recording Results: The best parameters and accuracies are recorded for each sample. The sample with maximum accuracy is identified.

<img width="513" alt="Screenshot 2024-05-05 at 11 34 39 PM" src="https://github.com/Aradhak03/Parameter-Optimization/assets/100716183/1874455e-30ef-4ef3-802f-4eeb2cc6c3b4">

 Convergence Graph: A convergence graph is plotted for the sample with the maximum accuracy, showing how the training and testing accuracies change over iterations during the optimization process.

<img width="856" alt="Screenshot 2024-05-05 at 11 37 49 PM" src="https://github.com/Aradhak03/Parameter-Optimization/assets/100716183/872f4eb4-151f-49a4-b946-7b4e28dd3c8e">

## Files Included
-dry_bean_data.csv: CSV file containing the Dry Bean dataset.
-parameter_optimization.ipynb: Jupyter Notebook containing the Python code for the project.
-README.md: This README file providing an overview of the project.

## Requirements
-Python 3.x
-Required libraries: pandas, scikit-learn, matplotlib

## Acknowledgments
-UCI Machine Learning Repository for providing the Dry Bean dataset.
-Scikit-learn and pandas libraries for their functionalities in data preprocessing and machine learning.

