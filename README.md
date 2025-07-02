# Online Course Engagement Analysis and Completion Prediction

This project focuses on analyzing online course engagement data and predicting whether a student will complete a course based on their interaction patterns. The analysis includes visualization, feature correlation, and the application of various classification models including Decision Tree, Random Forest, and K-Nearest Neighbors (KNN) to predict course completion.

## DataSet
The dataset online_course_engagement_data.csv contains features related to:
- User engagement metrics (Time Spent on Course, Number of Videos Watched, Number of Quizzes Taken)
- Performance indicators (Quiz Scores, Completion Rate)
- Categorical attributes (Course Category, Device Type)
- Target variable: CourseCompletion (1 = Completed, 0 = Not Completed)

## Project Workflow
1. Initial Data Analysis
- Scatter plots to visualize the relationship between TimeSpentOnCourse and CompletionRate for completed vs. not completed courses.
- As well as Scatter plots to visualize the relationship between QuizScores and CompletionRate for completed vs. not completed courses.
- Category exploration to identify unique CourseCategory entries.
- Correlation heatmap to understand relationships among features.
<p align="center">
  <img src="https://github.com/user-attachments/assets/3f3cc434-a595-4fe7-83ad-0ad4bf994ff5" alt="TimeSpentOnCourse vs CompletionRate" width="45%" />
  <img src="https://github.com/user-attachments/assets/1e2c5e58-6e25-4ba5-8153-e0d6b37b31f9" alt="QuizScores vs CompletionRate" width="45%" />
</p>

2. Preprocessing
- Handling the missing values if there exists.
- Label Encoding for categorical variables.
- Handling class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).
- Outlier detection through boxplots.

3. Modeling
Implemented classification algorithms:
* Decision Tree
* Random Forest
* K-Nearest Neighbors (KNN)

## Techniques Used:
* Hyperparameter tuning via GridSearchCV.
* Model evaluation using Accuracy, ROC-AUC, Confusion Matrix, and Classification Report.
* Feature importance analysis.

## Visualizations
- Scatter Plots
- Correlation Heatmaps
- Boxplots for Outlier Detection
- Confusion Matrices
- Feature Importance Charts
- Decision Tree Structure Visualization

## Model Performance Summary
Each model was evaluated using:
- Accuracy Score
- ROC-AUC Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)
Class imbalance was effectively handled using SMOTE.


## Contact 
Samia Jahan-
[LinkedIn](https://www.linkedin.com/in/samia-jahan-binte-nour/)-
[github](https://github.com/Samia1925)
