# eDiaPredict-An-Ensemble-Based-Framework-for-Diabetes-Prediction
## Overview
This project aims to predict diabetes based on patient data using various machine learning and neural network techniques. It employs machine learning algorithms (Random Forest, SVC, Decision Tree), ensemble learning(Bagging, Boosting and Stacking), advanced deep learning models, and feature selection methods to enhance prediction accuracy.

---
## Features
- Recursive Feature Elimination (RFE) for Feature Elimination.
- Random Forest and Decision Tree Models
- Principal Component Analysis (PCA) for dimensionality reduction
- Residual Neural Network with advanced techniques (gradient clipping, focal loss)
- Ensemble learning using bagging, boosting, and stacking
- SVC and Logistic Regression Model for Stacking. Decision Tree for Bagging and Boosting.
- Model evaluation with metrics like Accuracy, Precision, MER, GI, AUCH, AUC, sensitivity, specificity, and confusion matrices
- User interface for predictions via **Gradio**

---
## Dataset
The project uses patient Diet and glucose data. Merge operations on datasets are based on the `SEQN` key. Datasers are available at https://wwwn.cdc.gov/nchs/nhanes/continuousnhanes/default.aspx?Cycle=2021-2023
- **Dietary Data**: `DR1TOT_L.xpt
- **Glucose Data**: `GLU_L.XPT

Preprocessing includes:
1. Handling missing values
2. Feature selection with RFE or PCA
3. Scaling and encoding

---

## Requirements
- Python 3.8 or later
- Libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `torch`
  - `joblib`
  - `seaborn`
  - `matplotlib`
  - `gradio`

Install dependencies using:
```bash
pip install -r requirements.txt

---

**## Setup Instructions**
Clone the Repository:
git clone https://github.com/miteshkumarmandal1/eDiaPredict-An-Ensemble-Based-Framework-for-Diabetes-Prediction

Install required libraries:
pip install -r requirements.txt

---
##Model Training Code Files
Random Forest :
Neural NetworK and XBoost:
Decision Tree :
Ensemble Model and SVC: Team5_Mitesh_242IT020.ipynb

---
## Contribution Guidelines
We welcome contributions from the community to improve this project! If you'd like to contribute, please follow these steps:

1. **Fork the Repository**:  
   Click the "Fork" button at the top right of this repository to create a personal copy.

2. **Clone Your Forked Repository**:  
   Clone your fork to your local machine using the command:
   ```bash
   git clone https://github.com/miteshkumarmandal1/eDiaPredict-An-Ensemble-Based-Framework-for-Diabetes-Prediction/


---
**##License**
This project is licensed under the MIT License. See the LICENSE file for more details.

