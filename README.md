# Predicting Diabetes Risk Using Random Forests

Binary classification of diabetes risk using Random Forest Classifier.


## Overview

This project focuses on predicting diabetes risk (High/Low) using the Random Forest Classifier. The model uses a publicly available diabetes dataset from Scikit-learn and evaluates performance using metrics like accuracy, precision, recall, and F1-score.


## Technologies Used

- **Python 3.x**
- **Libraries**:
  - `pandas`: Data manipulation and analysis
  - `scikit-learn`: Machine learning algorithms and evaluation metrics
  - `matplotlib`: Plotting and visualization


## How It Works

1. **Dataset Loading**  
   The Scikit-learn `load_diabetes` dataset is loaded, and a target column is created for binary classification:
   - Target = 1 (High) if the value is greater than the median.
   - Target = 0 (Low) otherwise.

2. **Data Preprocessing**  
   Features and target values are separated, and the data is split into training and testing sets (80% training, 20% testing).

3. **Model Training**  
   A Random Forest Classifier is trained with 100 decision trees for robust prediction.

4. **Evaluation**  
   Model performance is evaluated using:
   - Accuracy
   - Precision
   - Recall
   - F1-Score  
   A confusion matrix is also plotted for better visualization.


## Code Execution

To run the code:
1. Clone this repository.
2. Ensure Python and the required libraries (`pandas`, `scikit-learn`, `matplotlib`) are installed.
3. Execute the script to view model evaluation metrics and the confusion matrix.


## Key Results

- **Accuracy**: Measure of overall correctness.
- **Precision**: How many predicted "High" cases were correct.
- **Recall**: Proportion of actual "High" cases correctly identified.
- **F1-Score**: Balance between Precision and Recall.

The confusion matrix plot offers insights into the classification results.


## Future Improvements

- Experimenting with other machine learning algorithms.
- Hyperparameter tuning for Random Forests.
- Adding feature importance visualization to understand the impact of each feature.


## Sample Output

**Metrics**
- Accuracy: 0.85
- Precision: 0.82
- Recall: 0.88
- F1-Score: 0.85

