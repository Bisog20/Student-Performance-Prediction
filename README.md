# 🎓 Predicting Student Academic Performance using Regression Analysis

## 📌 Project Overview
This project predicts the final grade (G3) of students using regression analysis on the [UCI Student Performance Dataset](https://archive.ics.uci.edu/ml/datasets/student+performance).  
Here, I employed the linear regression model to build a model to predict the fianl grade (G3) based on features such as study time, internet access, absences and so on. 

## 📂 Dataset
- **Source:** UCI Machine Learning Repository
- **Target Variable:** G3 (Final Grade)
- **Features:** Study time, absences, internet access, family background, and more.

## 🛠️ Tools & Libraries
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- Jupyter Notebook

## 🤖Modelling
- I conducted data cleaning using Pandas library in Python to remove the unwanted variables so as to focus on the variables needed for the project, remove variables and also to make sure that each column was appropriately formatted (e.g. Text, Number) for accurate analysis. Additionally, I implemented the use of pipeline to make sure that both preprocessing technique and model training happens together.
- To divide the dataset set, I made use of the train_test_split to divide the dataset into 80% training and 20% testing for appropriate modelling. 

## 📊 Results
- Best Model: **Linear Regression**
- MAE: 1.38
- R² Score: 0.77
- RMSE - 2.19

![Alt text](https://github.com/Bisog20/Student-Performance-Prediction/blob/main/Metrics.png)

- MAE (Mean Absolute Error)= 1.38 - The result above shows that on average, the model's predictions differ from the actual student grades by about 1.38 points on the grading scale.
- R-Squared Score = 0.77 - This indicates that the model explains about 77% variance in the final grades (G3). In other words, the model captures most of the patterns in the data, making it fairly reliable for prediction. 
- RMSE (Root Mean Squared Error) = 2.19 - This indicates that on average, the model is off by 2.19 grade points. 
# Visualization 
The chart below is the graph of the actual G3 score against that of the predicted G3 score. 

![Alt text](https://github.com/Bisog20/Student-Performance-Prediction/blob/main/Chart.png)

## 💡Recommmendation
- The model should be retrained periodically with new student dataset to maintain accuracy.
- More relevant factors can be included in the model to improve orediction accuracy.
- Although Linear Regression performed well, testing other advanced models like Random Forest or Gradient Boosting might capture more complex patterns.

## ✔️Conclusion
The model can predict most students' grades quite accurately, but performance could improve with diverse and richer data. This project demonstrates the potential of data science in education to identify at-risk-students early and help educators make informed decisions. 




