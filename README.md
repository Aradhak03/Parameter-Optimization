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

