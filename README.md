# Drug_Classification

## Problem Statement: 
To predict which of the available drug type should be prescribed to a patient with certain features.

## Dataset: 
drug200.csv
- Source: https://www.kaggle.com/prathamtripathi/drug-classification
- Response Variable: Drug type (A,B,C,X,Y)
- Predictors: Age, Sex, Blood Pressure Levels (BP), Cholesterol Levels, Na to Potassium Ration

## Steps:
1. Importing the libraries
2. Importing the dataset
3. Encoding Categorical Variables
4. Splitting the dataset into the Training set and Test set
5. Feature Scaling
6. Data Modelling
7. Results
8. Feature Importance

## Results:
![image](https://user-images.githubusercontent.com/56295513/149037001-3ff77965-976f-443a-aebf-ca3715e1a95a.png)

![image](https://user-images.githubusercontent.com/56295513/149037053-1e93332e-1a11-4452-a2fb-8b0836326265.png)

![image](https://user-images.githubusercontent.com/56295513/149037521-e863de0e-eac2-47cd-aa63-95066d416277.png)

## Conclusion:
- Based on the results, we can assert that the features with most importance for classification are Sex, Blood Pressure Levels (BP).

- The Algorithms of Decision Tree, Random Forest and SVM result in 100% Accuracy Score.

- Naive Bayes Algorithm has the least score with 87.5%.
