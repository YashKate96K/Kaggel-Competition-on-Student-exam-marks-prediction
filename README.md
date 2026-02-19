# Student Exam Score Prediction (Kaggle Style Project)

This project predicts student exam scores using machine learning by combining academic, lifestyle, and exam-related factors.  
The goal is to understand how student habits and exam difficulty influence performance and generate accurate score predictions.

## Project Overview
- Uses training and test datasets (`train.csv` and `test.csv`)
- Performs feature engineering based on study habits, sleep, attendance, and exam difficulty
- Trains a regression model to predict exam scores
- Generates prediction CSV files suitable for Kaggle submission

## Dataset
The dataset contains student-related information such as:
- Study hours
- Class attendance
- Sleep hours and sleep quality
- Study method
- Exam difficulty level

Both training and test datasets are combined temporarily to apply consistent feature engineering.

## Feature Engineering
Several meaningful features are created to improve model performance:
- **Sleep Health Score** based on sleep hours and sleep quality
- **Discipline Score** using study hours, attendance, and study method
- **Effort Consistency** combining study hours and attendance
- **Routine Score** reflecting attendance and sleep health
- **Stress Index** derived from exam difficulty and sleep health
- Log and squared transformations for better learning patterns

These features help capture real-world student behavior more effectively.

## Model Workflow
1. Load and combine datasets
2. Encode categorical variables
3. Create engineered features
4. Split back into training and test data
5. Train a regression-based machine learning model
6. Predict exam scores for test data
7. Save predictions as CSV files

## Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Output
- Multiple CSV files containing predicted exam scores
- Final prediction file suitable for evaluation or Kaggle submission

## Learning Outcome
This project helped me gain hands-on experience with:
- Feature engineering
- Handling real-world datasets
- Building end-to-end ML pipelines
- Preparing competition-style prediction outputs

## Author
**Yash Kate**
