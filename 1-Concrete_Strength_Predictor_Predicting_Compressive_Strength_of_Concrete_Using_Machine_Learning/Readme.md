# Read me 

## Concrete Strength Predictor: Predicting Compressive Strength of Concrete Using Machine Learning

### Problem Description
Concrete is the most important material in civil engineering. The concrete compressive strength is a highly nonlinear function of age and ingredients. The goal of this project is to predict the compressive strength of concrete based on its components.

### Dataset
The training and test dataset is attached in the mail. The dataset contains the following features:

### Independent Variables
1. Cement (component 1) -- kg in a m3 mixture
2. Blast Furnace Slag (component 2) -- kg in a m3 mixture
3. Fly Ash (component 3) - kg in a m3 mixture
4. Water (component 4) -- kg in a m3 mixture
5. Superplasticizer (component 5) -- kg in a m3 mixture
6. Coarse Aggregate (component 6) -- kg in a m3 mixture
7. Fine Aggregate (component 7) -- kg in a m3 mixture
8. Age -- Day (1~365)

### Dependent Variable
1. Concrete compressive strength -- MPa

### Methodology
We will explore the dataset and perform data cleaning, data preprocessing, feature engineering, and feature selection to prepare the data for the machine learning model. We will then train several regression models to predict the compressive strength of concrete, such as linear regression, polynomial regression, and random forest regression. We will use cross-validation and hyperparameter tuning to optimize the model's performance and evaluate the models' performance using various evaluation metrics such as mean squared error, mean absolute error, and R-squared.

### Conclusion
By the end of this project, we will have a machine learning model that can predict the compressive strength of concrete based on its components. This model can be useful for civil engineers and construction companies to optimize their concrete mixture design and reduce costs while ensuring the concrete's required strength.