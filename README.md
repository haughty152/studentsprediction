# Adaptability Level Prediction in Online Education

## Project Overview
This project analyzes students' adaptability levels in online education using machine learning models. The dataset contains various demographic and academic factors affecting adaptability. The goal is to classify students into different adaptability levels (High, Moderate, Low) using supervised learning techniques.

## Dataset Information
- **Source**: `students_adaptability_level_online_education.csv`
- **Features**: Gender, Age, Education Level, Institution Type, IT Student, Location, Load-shedding, Financial Condition, Internet Type, Network Type, Class Duration, Self LMS, Device
- **Target Variable**: Adaptivity Level (High, Moderate, Low)

## Steps in the Analysis
### 1. Data Collection & Preparation
- Imported necessary libraries and loaded the dataset.
- Checked for missing values and data types.
- Performed exploratory data analysis (EDA) using visualizations.

### 2. Data Processing & Feature Engineering
- Encoded categorical features using Label Encoding.
- Standardized numerical features using `StandardScaler`.
- Split the dataset into training and test sets.

### 3. Model Training & Evaluation
- Implemented multiple classification models:
  - **Logistic Regression**
  - **Decision Tree Classifier** (with GridSearchCV for hyperparameter tuning)
  - **Random Forest Classifier**
  - **Neural Network Model** (using TensorFlow/Keras)
- Evaluated models using accuracy, confusion matrices, and classification reports.

### 4. Hyperparameter Tuning
- Used GridSearchCV to optimize hyperparameters for the best model (Random Forest).
- Compared accuracy across models.

## Installation & Requirements
Ensure you have the following dependencies installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn plotly tensorflow
```

## How to Run the Code
1. Load the dataset in a Jupyter Notebook or Python script.
2. Run each section of the code sequentially:
   - Data Import & Exploration
   - Data Preprocessing & Feature Engineering
   - Model Training & Evaluation
   - Hyperparameter Tuning
3. Compare the results and interpret the findings.

## Results Summary
| Model                 | Accuracy  |
|----------------------|----------|
| Logistic Regression | ~X.XX%  |
| Decision Tree       | ~X.XX%  |
| Random Forest      | ~X.XX%  |
| Neural Network     | ~X.XX%  |

- The **Random Forest Classifier** with optimized hyperparameters performed the best.
- Neural Networks provided competitive results but required longer training times.
- Logistic Regression showed lower accuracy due to non-linearity in the dataset.

## Future Enhancements
- Experiment with other advanced models like XGBoost.
- Perform feature selection to remove less relevant features.
- Collect more diverse data to improve generalization.


