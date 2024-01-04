# Student Performance Prediction using Machine Learning

## Overview
This project utilizes machine learning techniques to predict factors that affect student grades based on a dataset provided in a CSV file. The dataset includes information about students' gender, nationality, grade level, and various determining factors such as the number of hands raised, attendance, hours studied, etc.

## Project Structure

### Data Loading:
- The project starts by loading the dataset from a CSV file using the Pandas library.

### Data Visualization:
- The Seaborn and Matplotlib libraries are used to create visual aids such as graphs to explore the relationships between different factors and student grades.

### Data Preprocessing:
- Data preprocessing involves dropping unnecessary columns and converting categorical variables into numerical format using Label Encoding.

### Model Building:
- The project employs different classifiers and machine learning models to predict student grades. The following models are used:
  - Decision Tree Classifier
  - Random Forest Classifier
  - Perceptron
  - Logistic Regression
  - MLP (Multi-Layer Perceptron) Classifier

### Model Evaluation:
- The accuracy of each model is evaluated using classification reports and accuracy scores.

### User Input Testing:
- The project allows the user to test the models with specific input data, providing predicted grades using each classifier.

## Usage Instructions

### Visualizations:
- The user can choose from various visualizations such as class count graphs, semester-wise graphs, gender-wise graphs, etc., to explore the dataset.

### Model Training and Testing:
- Different machine learning models are trained on the dataset, and their accuracies are evaluated. The user can input specific data to get predictions using each model.

### Requirements
- Python 3.x
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn

### How to Run
1. Clone the repository to your local machine.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the script `student_performance_prediction.py`.
