## Consumer Behavior Predictor

A Data Mining project utilizing Python to build and evaluate Decision Tree, Random Forest, and Gradient Boosting models. This analysis focuses on predictive classification using the scikit-learn and dmba libraries.

## Project Overview 
The goal of this project was to utilize ensemble learning techniques, specifically Gradient Boosting, to identify the key demographic drivers of consumer behavior. By analyzing feature importance, I determined that Income and Education were the primary predictors, allowing for a model with over 98% classification accuracy. This analysis applies data mining techniques to predict consumer ownership patterns by building and comparing multiple classification models to identify the most effective predictive methods.
 
## Key Features

**Predictive Classification**: Implemented Decision Trees to categorize ownership based on demographic variables.

**Ensemble Learning**: Evaluated advanced models including Random Forest and Gradient Boosting to optimize performance.

**Statistical Evaluation**: Used classification summaries and accuracy metrics to validate model reliability.

**Model Visualization**: Generated visual tree diagrams to interpret complex decision-making paths.

## Key Findings & Model Results

**Primary Predictor**: Through decision tree analysis, Income was identified as the most critical feature in determining ownership, with the initial split occurring at the **$59,700** threshold.

**High Training Accuracy**: The fully grown Decision Tree achieved a perfect **1.0000 Accuracy** on the training dataset, correctly classifying all 19 samples.

**Strong Validation Performance**: On unseen data (validation set), the model maintained an **98% Accuracy** rate.

**Classification Balance**: The model correctly identified 100% of the "Owners" in the validation set, though it had a slight tendency to misclassify one "Nonowner" as an "Owner".

## Technologies Used
 
**Programming**: Python

**Machine Learning**: scikit-learn

**Specialized Analytics**: dmba (Data Mining for Business Analytics)

**Data Handling**: Pandas

