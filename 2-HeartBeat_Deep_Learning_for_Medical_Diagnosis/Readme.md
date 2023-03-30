# README

## HeartBeat: Deep Learning for Medical Diagnosis

### Problem Description

This project was done as a part of a Deep Learning Hackathon challenge on a Medical Dataset. The goal is to predict the presence of heart disease in the patient based on the given input columns.

### Dataset

The dataset contains the following features:

#### Independent Variables

1. age
2. sex
3. chest pain type (4 values)
4. resting blood pressure
5. serum cholestoral in mg/dl
6. fasting blood sugar > 120 mg/dl
7. resting electrocardiographic results (values 0,1,2)
8. maximum heart rate achieved
9. exercise induced angina
10. oldpeak = ST depression induced by exercise relative to rest
11. the slope of the peak exercise ST segment
12. number of major vessels (0-3) colored by flourosopy
13. thal: 0 = normal; 1 = fixed defect; 2 = reversable defect

The names and social security numbers of the patients were recently removed from the database, replaced with dummy values.

#### Dependent Variable

1. target - refers to the presence of heart disease in the patient. It is an integer valued 0 = no disease and 1 = disease.

### Methodology

We will apply suitable Deep Learning algorithms to predict the target variable based on the input columns. We will preprocess the dataset, including feature scaling and feature engineering, to prepare the data for the Deep Learning models. We will use various Deep Learning algorithms such as artificial neural networks, convolutional neural networks, and recurrent neural networks. We will use cross-validation and hyperparameter tuning to optimize the model's performance and evaluate the models' performance using various evaluation metrics such as accuracy, precision, recall, and F1-score.

### Conclusion

By the end of this project, we will have a Deep Learning model that can predict the presence of heart disease in a patient based on their medical information.
