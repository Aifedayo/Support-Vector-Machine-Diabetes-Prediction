
# Support Vector Machine: Diabetes Prediction

## Overview
This project uses a Support Vector Machine (SVM) model to predict the likelihood of diabetes in patients based on various health metrics. Using a dataset of medical information, the SVM model classifies individuals as diabetic or non-diabetic, providing a useful tool for early detection and intervention.

## Dataset
- **Source**: The dataset contains features such as blood pressure, glucose levels, BMI, and age.
- **Target**: Binary classification indicating **diabetic** or **non-diabetic**.

## Project Structure
- **Data Preprocessing**: Includes handling missing values, data normalization, and feature scaling.
- **Model Training**: An SVM model is trained and tuned to optimize predictive accuracy.
- **Evaluation**: Model performance is evaluated using metrics like accuracy, precision, recall, and F1 score.

## Requirements
- Python libraries: `pandas`, `scikit-learn`, `numpy`, and `matplotlib`

Install dependencies with:
```bash
pip install -r requirements.txt
```

## How to Run
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Aifedayo/Support-Vector-Machine-Diabetes-Prediction.git
   ```
2. **Run the Notebook**:
   Open and execute the Jupyter notebook to view the data analysis, model training, and evaluation steps.

## Results
- The model achieves an accuracy of 75% on the test data, making it a useful classifier for diabetes prediction.
