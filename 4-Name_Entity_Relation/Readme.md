# README

## Extracting Knowledge from Text: Entity and Relation Prediction in Large Datasets

### Problem Statement

The goal of this project is to find entities and relations in a dataset. The training and test datasets are provided, and the task is to populate the `h_name`, `t_name`, and `relation` columns in the test dataset.

### Shared Files

The following files are provided for this project:

- `nyt10m_rel2id`: a JSON file containing the relation to id mappings
- `nyt10m_val`: a validation dataset
- `nyt10m_train`: the training dataset
- `nyt10m_test`: the test dataset

Please note that the order of the columns and the data in the test dataset should not be changed.

### Methodology

We will use natural language processing and machine learning techniques to extract entities and relations from the provided dataset. We will preprocess the data, including text normalization, tokenization, and named entity recognition, to prepare the data for the machine learning models. We will use various machine learning models, such as logistic regression, support vector machines, and neural networks, to predict the entity and relation in the test dataset. We will use cross-validation and hyperparameter tuning to optimize the model's performance and evaluate the models' performance using various evaluation metrics such as accuracy, precision, recall, and F1-score.

### Conclusion

By the end of this project, we will have extracted entities and relations from the provided dataset using natural language processing and machine learning techniques. The `h_name`, `t_name`, and `relation` columns in the test dataset will be populated with the predicted values.
