# CodTech Internship - Task 2: Machine Learning Predictive Model

This repository contains Task 2 of the CodTech Data Analysis Internship: a predictive machine learning model to determine whether a customer is likely to purchase insurance.

## 🎯 Objective
To apply classification techniques for predictive analytics using a synthetic dataset.

## 🧾 Dataset Description
The dataset is synthetically generated using Python and contains demographic and behavioral features related to insurance purchase behavior.

### 📌 Columns:
- `age` – Age of the customer
- `gender` – Male or Female
- `income` – Annual income (in ₹)
- `education` – Highest educational qualification
- `marital_status` – Single or Married
- `insurance_bought` – Target variable (1 = Yes, 0 = No)

The dataset is generated and processed within the same notebook (`predictive_model.ipynb`), so no external files are required.

## ⚙️ Workflow
1. **Data Generation** – Create a realistic synthetic dataset in Python
2. **Preprocessing** – Label encode categorical columns
3. **Model Building** – Train a Random Forest classifier
4. **Evaluation** – Use accuracy, confusion matrix, and classification report

## 📁 Files Included
- `predictive_model.ipynb` – Complete notebook containing data creation, model training, and evaluation

## 🚀 How to Run
1. Open the notebook in Jupyter:
   ```bash
   jupyter notebook predictive_model.ipynb
