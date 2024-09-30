# Diabetes Prediction Model

This project implements a diabetes prediction model using Support Vector Machine (SVM) to assist in the early detection of diabetes based on various health metrics.

## Features

The model uses the following input features:

1. **Pregnancies**: Number of times pregnant (0-17).
2. **Glucose**: Plasma glucose concentration (0-199 mg/dL).
3. **Blood Pressure**: Diastolic blood pressure (0-122 mm Hg).
4. **Skin Thickness**: Triceps skin fold thickness (0-99 mm).
5. **Insulin**: 2-Hour serum insulin (0-846 mu U/ml).
6. **BMI**: Body mass index (0.0-67.1 kg/m²).
7. **Diabetes Pedigree Function**: A function that scores the likelihood of diabetes based on family history (0.078-2.42).
8. **Age**: Age in years (21-81).

## How to Use

1. **Install Required Libraries**: Make sure you have Streamlit and the necessary libraries installed.
   ```bash
   pip install streamlit scikit-learn pandas numpy

2. **Run the Application**: Navigate to the directory containing the script and run:streamlit run app.py
     streamlit run app.py

3. **Input Features**: Use the sidebar to input the required health metrics for prediction:
   Adjust the sliders for each feature according to your data.
  The model will process the input and predict the likelihood of diabetes.

4.**View Results**: After entering the data, the model will display the prediction result, indicating whether there is a risk of diabetes.

## Model Description
The SVM model was trained on a dataset that includes various health metrics. The model's performance was evaluated and tuned for optimal accuracy in predicting diabetes.


