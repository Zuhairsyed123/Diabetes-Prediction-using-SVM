# Diabetes-Prediction-using-SVM
This project predicts whether a patient is likely to have diabetes based on medical attributes using a Support Vector Machine (SVM) model.

# Tech Stack
 - Python
 - NumPy
 - Pandas
 - Scikit-learn

# Workflow
 1) Data Preprocessing using Pandas
 2) Feature Scaling using StandardScaler
 3) Train Test Split
 4) Model Training using SVM
 5) Model Evaluation using Accuracy and Classification Metrics
     
# Model Details
 - Algorithm: Support Vector Machine (SVM)
 - Kernel: linear
# Results
Accuracy: 77%

## Key Insights
- Some health features show strong correlation with diabetes outcome  
- Feature scaling improved model performance  
- SVM performed effectively for classification

## Visualizations & Analysis

### Correlation Heatmap
The correlation heatmap illustrates the relationships between different medical features in the dataset.

- Features like **Glucose**, **BMI**, and **Age** show a stronger correlation with the diabetes outcome.
- Some features have weak correlation, indicating they contribute less to prediction.
- This analysis helps in understanding which variables are more important for the model.

### Class Distribution
The dataset contains two classes:
- **0 → Non-Diabetic**
- **1 → Diabetic**

The distribution plot helps identify whether the dataset is balanced or imbalanced.

- A balanced dataset ensures better model performance.
- If imbalanced, it may require techniques like resampling.

### Feature Distribution
Histograms of features show how the data is spread.

- Some features are normally distributed, while others are skewed.
- Skewed data may impact model performance and may require normalization.

### Confusion Matrix
The confusion matrix evaluates model performance by comparing actual vs predicted values.

- **True Positives (TP):** Correctly predicted diabetic cases  
- **True Negatives (TN):** Correctly predicted non-diabetic cases  
- **False Positives (FP):** Incorrectly predicted diabetic cases  
- **False Negatives (FN):** Missed diabetic cases  

Key insights:
- Lower false negatives are important in medical diagnosis.
- The model performs well if diagonal values (correct predictions) are high.
