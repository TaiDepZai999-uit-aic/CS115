# About Dataset
## Context
- This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective is to predict based on diagnostic measurements whether a patient has diabetes.
## Content
- Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.
 * **Pregnancies**: Number of times pregnant
 * **Glucose**: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
 * **BloodPressure**: Diastolic blood pressure (mm Hg)
 * **SkinThickness**: Triceps skin fold thickness (mm)
 * **Insulin**: 2-Hour serum insulin (mu U/ml)
 * **BMI**: Body mass index (weight in kg/(height in m)^2)
 * **DiabetesPedigreeFunction**: Diabetes pedigree function
 * **Age**: Age (years)
 * **Outcome**: Class variable (0 or 1)
# Models and Methods
- Data cleaning and Feature selection:
  * Identify and exclude outliers.
  * Tackle with Null values with 4 methods: Drop Null, Fill Null with 0 and global mean, KNN Imputer techniques.
  * Utilizing GridSearchCV to find optimal hyperparameters for models.
  * Calculating Correlation between each feature with target in order to select the most impactful features.
- Models choosing:
  * Decision tree
  * Random forest
  * Bagging
  * Gradient Boosting
# Results
- The result in based on Accuracy score with different features used and models.
![Screenshot 2024-12-09 205526](https://github.com/user-attachments/assets/374281d1-5bc3-4f40-857d-604edcced167)

# Demo application
![Screenshot 2024-12-09 212844](https://github.com/user-attachments/assets/84e0f32f-1cc6-4e15-8785-54d6ee168303)
