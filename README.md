# Income Prediction using Machine Learning

## Project Overview
This project presents an end-to-end machine learning classification pipeline to predict whether an individual makes over $50K a year, based on the **Adult Income Dataset**. It encompasses data preprocessing, exploratory data analysis (EDA), feature engineering (including PCA), and comparative modeling using various classification algorithms.

## Dataset
- **Name:** Adult Income Dataset (Adult.csv)
- **Target Variable:** Income (<=50K or >50K)
- **Features:** 14 demographic and employment-based features including age, education, occupation, working hours, and marital status.

## Technologies Used
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

## Pipeline Steps
1. **Data Preprocessing:** Handling missing values, label encoding, one-hot encoding, and feature scaling (Standardization).
2. **Feature Engineering:** Creating domain-based features (e.g., `age_group`, `work_intensity`), removing highly correlated features, and dimensionality reduction using Principal Component Analysis (PCA).
3. **Exploratory Data Analysis:** Visualizing feature distributions and relationships.
4. **Machine Learning Modeling:** Evaluating multiple classification algorithms.
5. **Evaluation:** Comparing models based on Accuracy, Precision, Recall, and F1-Score.

## How to Run
1. Clone the repository.
2. Install the necessary dependencies via:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the `income_prediction_ml.ipynb` notebook in Jupyter or Google Colab and run the cells sequentially.
