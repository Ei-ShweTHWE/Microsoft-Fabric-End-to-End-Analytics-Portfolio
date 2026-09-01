# 04 - Data Science Lab (Microsoft Fabric)

## 📌 Objective
This lab demonstrates an end-to-end Machine Learning and Data Science workflow using Microsoft Fabric Notebooks (`Notebook_1`) and PySpark. It covers data splitting, model training using Random Forest, and automated tracking with MLflow.

## 🛠️ Key Components & Workflow
1. **MLflow Tracking:** Enabled `mlflow.autolog()` for automated logging of model parameters, metrics, and artifacts within the Fabric workspace.
2. **Data Preparation & Splitting:** Defined features ($X$) and target ($y$) variables, followed by splitting the dataset into training and testing sets ($80 / 20$) using `train_test_split`.
3. **Model Training:** Built and trained a **RandomForestRegressor** model (`n_estimators=100`) on the diabetes dataset.
4. **Performance Evaluation:** Evaluated model predictions on test data using Mean Squared Error (MSE) metrics.

## 📊 Lab Screenshot / Notebook Execution Preview
Below is a preview of the Jupyter Notebook showing the Python/PySpark code execution, Random Forest model training, and successful execution logs:

*(Drag and drop your screenshot here — the one showing the Notebook with Python code and execution success message)*

---
**Status:** Completed successfully ✅<img width="1912" height="920" alt="DataScienceLab" src="https://github.com/user-attachments/assets/b0bb593b-ec5b-4247-9e96-c93fdbd75ffd" />

