# Alzheimer's Disease Detection Using Machine Learning 🧠

This project uses machine learning classification models to predict the progression stages of Alzheimer's disease based on patient data. The goal is to support early diagnosis and improve healthcare outcomes.

## 🧪 Project Overview

Alzheimer's is a progressive neurological disorder. Detecting it early can significantly improve the effectiveness of treatments. This project applies ML techniques to classify the stage of Alzheimer's based on various features such as brain volume measurements and clinical scores.

### ✅ Key Steps:
- Data cleaning and exploratory analysis
- Label encoding of categorical variables
- Model training using:
  - Decision Tree Classifier
  - Random Forest Classifier
- Model evaluation and accuracy comparison

## 📊 Dataset Features

Some of the input features include:
- Gender
- Age
- MMSE (Mini-Mental State Examination)
- eTIV (Estimated Total Intracranial Volume)
- nWBV (Normalized Whole Brain Volume)
- ASF (Atlas Scaling Factor)
- Group (Target variable indicating disease stage)

> **Target**: Classification of cognitive condition (e.g., Nondemented, Demented)

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/alzheimers-detection-ml.git
   cd alzheimers-detection-ml
(Optional) Create a virtual environment:

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

pip install -r requirements.txt
Run the notebook:

jupyter notebook Copy_of_ML_Mini_Project.ipynb
