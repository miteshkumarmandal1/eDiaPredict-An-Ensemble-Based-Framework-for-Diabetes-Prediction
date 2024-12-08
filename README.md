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
- Python 3.10.12
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
git clone https://github.com/miteshkumarmandal1/eDiaPredict-An-Ensemble-Based-Framework-for-Diabetes-Prediction.git

Install required libraries:
pip install -r requirements.txt

---
##Model Training Code Files
Random Forest :
Neural NetworK and XBoost:
Decision Tree :
Ensemble Model and SVC: Team5_Mitesh_242IT020.ipynb

---
##Our Individual Contribution:
Nishant Sahu:-
Implemented a Decision Tree model using Recursive Feature Elimination (RFE),  without and with PCA (20 components).Developed an ensemble model combining Decision Tree and Neural Network using weighted and voting ensemble methods, achieving accuracies of 0.868 and 0.88, respectively.Successfully integrated the  model into a user interface (UI).

Akash Rohit:-
Developed and implemented a Random Forest model for Diabetes Prediction, utilizing both approaches with and without Recursive Feature Elimination (RFE) to analyze feature importance and optimize model performance. Achieved an accuracy of 0.7887, demonstrating the robustness and reliability of the model. The solution was seamlessly integrated into a user-friendly interface, enabling real-time predictions and providing an accessible tool for diabetes risk assessment.

Deobrat Jha:-
Implemented neural networks and the XGBoost model with and without RFE, utilizing ensemble techniques like bagging, stacking, and boosting. The boosting model achieved superior performance with an accuracy of 85.25% and an AUC of 85.48%. Integrated with a Gradio-based UI, allowing users to upload .csv files and get real-time predictions of diabetes status.

Mitesh Kumar Mandal:-
Implemented Ensemble
Learning(Stacking, Bagging and Boosting) with 0.99 highest Accuracy in Bagging and integrated with UI. Implmented for both, with and without RFE. Also trained SVM model using different kernels (Linear,Polynomial and RBF) and plotted combined AUC.
--

## Contribution Guidelines
We welcome contributions from the community to improve this project! If you'd like to contribute, please follow these steps:

1. **Fork the Repository**:  
   Click the "Fork" button at the top right of this repository to create a personal copy.

2. **Clone Your Forked Repository**:  
   Clone your fork to your local machine using the command:
   ```bash
   git clone https://github.com/miteshkumarmandal1/eDiaPredict-An-Ensemble-Based-Framework-for-Diabetes-Prediction.git


---
**##License**
This project is licensed under the MIT License. See the LICENSE file for more details.

