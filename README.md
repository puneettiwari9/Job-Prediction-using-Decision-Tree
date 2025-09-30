# Job-Prediction-using-Decision-Tree
This project implements a Decision Tree classifier to predict job selection outcomes based on candidate attributes such as CGPA, Aptitude, Programming Skills, and Communication abilities.
Dataset

## The dataset (job_dataset.csv) contains candidate details such as:
CGPA (Low, Medium, High)
Aptitude (Low, Average, High)
Programming Skill (Poor, Average, Good)
Communication (Poor, Average, Good)
Job Offered? → Target (Yes/No)

# Model Training
Algorithm: Decision Tree Classifier (Entropy criterion – Information Gain)
Train/test split: 80/20
Evaluation metrics:
Accuracy = 1.0
Confusion Matrix
Classification Report

##  Features

 **Data Preprocessing**: Handles categorical data through one-hot encoding
 **Decision Tree Model**: Uses entropy-based criterion for classification
 **Performance Metrics**: Provides accuracy score, classification report, and confusion matrix
 **Visualization**: Includes a heatmap for the confusion matrix
 **User Prediction**: Interactive system to predict job selection for new candidates

# Example prediction input
CGPA: low
Aptitude: low  
Programming Skill: bad
Communication: bad
# Output
Prediction for job selection: No

# Results
Decision Tree Visualization
![Decision Tree](assets/decision_tree.png)



  
