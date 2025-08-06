# Dengue Prediction using Machine Learning

A dengue prediction ML project for CSE422 (Artificial Intelligence) in Brac University.
This project aims to predict Dengue diagnoses based on patient demographics, test results (NS1, IgG, IgM), and living conditions. The objective is to classify whether a person is likely to have dengue (Outcome: 1) or not (Outcome: 0) using machine learning models trained on clinical and environmental data.

---

## 📁 Project Structure

Group06_Dengue_Prediction.ipynb # Main analysis notebook

dengue dataset.csv # Dataset

README.md # Project documentation

Group06_Dengue_Prediction.pdf # Detailed Report of the Analysis

## 🚀 How to Run

1. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

2. Load and run the notebook:

```bash
jupyter notebook Group06_Dengue_Prediction.ipynb
```

---

## 📚 Dataset Description

- **Source**: https://www.kaggle.com/datasets/kawsarahmad/dengue-dataset-bangladesh
- **Rows**: 1000
- **Features**:
  - `Gender`, `Age`
  - `NS1`, `IgG`, `IgM` (test indicators)
  - `Area`, `AreaType`, `HouseType`, `District`
  - `Outcome` (Target variable: 0 = No Dengue, 1 = Dengue)

---

## 🧠 Models Used

1. **K-Nearest Neighbors (KNN)**

2. **Logistic Regression**

3. **Random Forest Classifier**

---

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix (Visualized using Seaborn heatmaps)

---

## Group Members

Jannatul Ferdaus

Tangena Islam
