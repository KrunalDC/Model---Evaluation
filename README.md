# Breast Cancer Diagnosis Using Logistic Regression

## Introduction

This Code discribe to create a machine learning model to classify breast tumors as malignant (cancerous) or benign (non-cancerous) using the Breast Cancer Wisconsin (Diagnostic) dataset from the UCI Machine Learning Repository. The dataset includes 569 samples with 30 features extracted from images of breast tissue.

## Data Preparation

1. **Loading Data:** We fetched the dataset and examined its features and details.
2. **Checking for Missing Values:** There were no missing values in the dataset.
3. **Splitting Data:** The data was divided into two parts: 80% for training the model and 20% for testing it.
4. **Scaling Features:** Features were standardized to have a mean of 0 and a standard deviation of 1.

## Model Training

- **Algorithm Used:** Logistic Regression was selected for its simplicity and effectiveness in binary classification tasks.
- **Training:** The model was trained using the training data.

## Model Evaluation

- **Making Predictions:** The trained model made predictions on the test data.
- **Accuracy:** The model achieved an accuracy of 97%, correctly identifying the tumors in most cases.
- **Detailed Results:** The model showed strong performance in precision, recall, and F1-score for both malignant and benign tumors.

## Results

The logistic regression model performed excellently, correctly classifying 97% of the tumors. It demonstrated high performance across various evaluation metrics.

## Conclusion

The logistic regression model is effective for classifying tumors in this dataset, with high accuracy and strong performance metrics. Future work could explore using other algorithms, fine-tuning the model, and additional data preprocessing techniques to further improve the results.

# Breast Cancer Diagnosis Using Random Forest Classifier

## Introduction

This Code aims to create a machine learning model to classify breast tumors as malignant (cancerous) or benign (non-cancerous) using the Breast Cancer Wisconsin (Diagnostic) dataset from the UCI Machine Learning Repository. The dataset includes 569 samples with 30 features extracted from images of breast tissue.

## Data Preparation

1. **Loading Data:** We fetched the dataset and examined its features and details.
2. **Checking for Missing Values:** There were no missing values in the dataset.
3. **Splitting Data:** The data was divided into two parts: 80% for training the model and 20% for testing it.
4. **Scaling Features:** Features were standardized to have a mean of 0 and a standard deviation of 1.

## Model Training

- **Algorithm Used:** We used a Random Forest Classifier due to its robustness and effectiveness for classification tasks.
- **Training:** The model was trained using the training data.

## Model Evaluation

- **Making Predictions:** The trained model made predictions on the test data.
- **Accuracy:** The model achieved an accuracy of 97%, correctly identifying the tumors in most cases.
- **Detailed Results:** The model showed strong performance in precision, recall, and F1-score for both malignant and benign tumors.

## Results

The Random Forest Classifier performed excellently, correctly classifying 96% of the tumors. It demonstrated high performance across various evaluation metrics.

## Conclusion

The Random Forest Classifier is effective for classifying tumors in this dataset, with high accuracy and strong performance metrics. Future work could explore using other algorithms, fine-tuning the model, and additional data preprocessing techniques to further improve the results.

