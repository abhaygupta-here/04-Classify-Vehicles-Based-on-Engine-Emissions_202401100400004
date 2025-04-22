# 04-Classify-Vehicles-Based-on-Engine-Emissions_202401100400004
# 🚗 Vehicle Emission Category Classification

This project aims to classify vehicles into emission categories based on features such as engine size, fuel type, and CO2 emissions using machine learning.

## 📁 Files Included

- `vehicle_emissions.csv` – The dataset used for training and testing.
- `emission_classification.ipynb` – Jupyter notebook containing the code.
- `report.pdf` – Full report with methodology, code, output, and conclusion.
- `README.md` – Project overview and instructions.

## 📌 Problem Statement

To build a classification model that predicts the emission category (e.g., A, B, C) of a vehicle using provided features.

## 🛠️ Methodology

- Preprocessing with label encoding for categorical features
- Model: Random Forest Classifier
- Evaluation: Confusion Matrix, Accuracy, Precision, Recall

## ✅ Results

- **Accuracy:** 40%
- Visualized using a confusion matrix heatmap
- ![Screenshot 2025-04-22 145933](https://github.com/user-attachments/assets/1079810e-c2bc-4571-a3ac-7f418755eea7)


## 📊 Requirements

- Python 3.x
- Libraries: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

Install dependencies using:

```bash
pip install -r requirements.txt
