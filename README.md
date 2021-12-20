# Cardio-Disease-Prediction

### Inspiration for the Project
Heart disease is the leading cause of death for men, women, and people of most racial and ethnic groups in the World.
One person dies every 36 seconds in the United States from cardiovascular disease. 
About 659,000 people in the United States alone die from heart disease each year—that's 1 in every 4 deaths.

## DataSet 
I have used a publically available [Dataset](https://www.kaggle.com/sulianova/cardiovascular-disease-dataset) on Kaggle

### Insights about the Dataset..
The Dataset Contains about 70000 rows and includes following features..
1. Age | Objective Feature | age | int (days)
2. Height | Objective Feature | height | int (cm) |
3. Weight | Objective Feature | weight | float (kg) |
4. Gender | Objective Feature | gender | categorical code |
5. Systolic blood pressure | Examination Feature | ap_hi | int |
6. Diastolic blood pressure | Examination Feature | ap_lo | int |
7. Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above normal |
8. Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal |
9. Smoking | Subjective Feature | smoke | binary |
10. Alcohol intake | Subjective Feature | alco | binary |
11. Physical activity | Subjective Feature | active | binary |
12. Presence or absence of cardiovascular disease | Target Variable | cardio | binary 

## ML Models Used - 
1. Ridge Classifier 	
2. Logistic Regression
3. Naive Bayes 	
4. K Neighbors Classifier
5. SVM - Linear Kernel 
6. Decision Tree Classifier
7. Stacked Models

## Evaluations and Conclusions
| Classifier  | Accuracy  | 
|---|---|
|  Stacked Method (Gradient Boosting,Light Gradient Boosting, Ridge Classification) | 72.79%  |
| Gradient Boosting | 72. 3% |
| Decision Trees | 72.15% |
|  Random Forests | 72.02%  |
| Logistic Regression | 71.07% |
| K Nearest Neighbours | 70.83% |
| Naive Bayes | 67.47% |
|  Support Vector Machines | 59.95%  |

### Why Does Stacking have the highest Accuracy ?
The benefit of stacking is that it can harness the capabilities of a range of well-performing models on a classification or regression 
task and make predictions that have better performance than any single model in the ensemble.

### Gradient boosting is one of the most powerful techniques for building predictive models.
Gradient Boosting methods are generalized methods of Ada Boost Algorithm that are very powerful algorithms for making weak learners learn more. 
In Ada Boost the weak learners are decision Trees.Gradient boosting involves three elements-
1. A loss function to be optimized.
2. A weak learner to make predictions.
3. An additive model to add weak learners to minimize the loss function.

### Plots and Matrics
![](https://bin.wantguns.dev/tqPamn)
![HeatMap for Feature Matching](https://bin.wantguns.dev/Vmj9CD)
![](https://bin.wantguns.dev/hLsYiW)

# Whole Project is At [Colab Notebook](https://colab.research.google.com/drive/1MrATY52ttboUR-XvIin_8eGbY15KG7fT?usp=sharing)
