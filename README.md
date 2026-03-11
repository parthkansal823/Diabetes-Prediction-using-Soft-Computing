# Diabetes Prediction using Soft Computing Algorithms

##  Project Description
Diabetes is a chronic disease that affects millions of people worldwide. Early prediction of diabetes can help in timely treatment and prevention of severe complications.  

This project aims to develop a **Diabetes Prediction System** using **Soft Computing and Machine Learning Algorithms**.  
The system analyzes medical diagnostic parameters to predict whether a patient is diabetic or non-diabetic.

The project involves **data preprocessing, exploratory data analysis (EDA), handling missing values, managing class imbalance, model training, evaluation, and feature importance analysis**.

---

##  Objectives
- To analyze the diabetes dataset using statistical and visualization techniques  
- To handle missing or invalid data values effectively  
- To address class imbalance for better prediction performance  
- To implement Soft Computing / Machine Learning classification algorithms  
- To evaluate model performance using standard metrics  
- To identify important features influencing diabetes prediction  

---

##  Dataset Information
- **Dataset:** Pima Indians Diabetes Dataset  
- **Total Instances:** 768  
- **Number of Features:** 8 input features + 1 output feature  

###  Feature Details

| Feature Name | Description |
|-------------|------------|
| Pregnancies | Number of times pregnant |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure (mm Hg) |
| SkinThickness | Triceps skin fold thickness (mm) |
| Insulin | 2-Hour serum insulin (mu U/ml) |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes hereditary influence |
| Age | Age in years |
| Outcome | 0 → Non-Diabetic, 1 → Diabetic |

---

##  Methodology

###  Data Preprocessing
- Checked dataset information and statistical summary  
- Replaced invalid zero values in key medical features  
- Prepared dataset for training and testing  

###  Exploratory Data Analysis
- Distribution plots and correlation heatmap  
- Identification of feature relationships  
- Detection of data imbalance  

###  Handling Imbalanced Data
- Applied resampling techniques to balance diabetic and non-diabetic classes  

###  Model Implementation
- Random Forest Classifier used for prediction  
- Hyperparameter tuning performed for better accuracy  

###  Feature Importance
Important predictors identified:
- Glucose  
- BMI  
- Age  
- Insulin  

---

##  Model Evaluation

Evaluation metrics used:
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

**Achieved Model Accuracy:** ~77%

---

##  Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

##  Steps to Run the Project

```bash
# Clone the repository
git clone https://github.com/parthkansal823/Diabetes-Prediction-using-Soft-Computing.git

# Go to project directory
cd Diabetes-Prediction-using-Soft-Computing

# Install required libraries
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook
