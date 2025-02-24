# Underwater Mine vs Rock Classification

This project focuses on developing and evaluating machine learning models to classify underwater objects as either mines or rocks using sonar data. The goal is to improve the accuracy and interpretability of detection systems, which is crucial for real-world applications.

## Project Overview

- **Objective**: Binary classification to distinguish between underwater mines and rocks.
- **Models Evaluated**:
  - Logistic Regression
  - Random Forest
  - Support Vector Machine (SVM)
- **Performance Metrics**:
  - Logistic Regression: 76.19% accuracy
  - Random Forest: 71.43% accuracy
  - SVM: 80.95% accuracy

## Code Explanation

### 1. Classification Report and Confusion Matrix
- **Classification Report**: Provides precision, recall, F1-score, and support for each class.
- **Confusion Matrix**: Visualizes the model's performance with True Positives, True Negatives, False Positives, and False Negatives.

### 2. Feature Impact Analysis
- **Logistic Regression Coefficients**: Identifies the importance and direction (positive or negative) of each feature.
- **Visualization**: Scatter plot to show the impact strength of each feature, with color coding for mines (blue) and rocks (red).

### 3. Adding Value Labels
- **Value Labels**: Adds numerical values to the scatter plot for better interpretability.
- **Legend**: Explains how to read the plot, indicating the importance and direction of each feature.


Dependencies
Python 3.x

scikit-learn

pandas

numpy

matplotlib

seaborn

Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

License
This project is licensed under the MIT License.
