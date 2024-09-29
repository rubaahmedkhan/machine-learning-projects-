# Heart Disease Prediction Model

## Overview
This project implements a logistic regression model to predict heart disease. The model takes input values and predicts whether an individual is likely to have heart disease or not.

## Libraries Used
- `scikit-learn`: A machine learning library for building the logistic regression model.
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical computing.

## Input Features
The model requires the following features to make predictions. These should be provided in a comma-separated format:

1. **age**: Age (years)
2. **sex**: Gender (0 = female, 1 = male)
3. **cp**: Chest pain type (0-3)
4. **trestbps**: Resting blood pressure (mm Hg)
5. **chol**: Serum cholesterol (mg/dl)
6. **fbs**: Fasting blood sugar (> 120 mg/dl, 1 = true, 0 = false)
7. **restcg**: Resting electrocardiographic results (0-2)
8. **thal**: Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect)
9. **thalach**: Maximum heart rate achieved
10. **exang**: Exercise induced angina (1 = yes; 0 = no)
11. **oldpeak**: ST depression induced by exercise relative to rest
12. **slope**: Slope of the peak exercise ST segment (0-2)
13. **ca**: Number of major vessels (0-3)

### Example Input
45,1,2,130,250,0,1,2,150,0,2.3,1,0


## Model Training
This model is trained using the logistic regression class from scikit-learn. A training dataset is used to fit the model.

## Prediction
To make a prediction, input values can be passed to the `predict` function, returning a result. If the prediction is `1`, it indicates the presence of heart disease; if `0`, it indicates no heart disease.

## How to Use
1. **Install Dependencies**:
   ```bash
   pip install pandas scikit-learn numpy streamlit

## View the Prediction Result: 
if prediction[0] == 1:
    print("Heart Disease detected")
else:
    print("No Heart Disease")


