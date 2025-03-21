# ML Model for Circuit Failure Prediction 🔧📊

## Objective 🎯  
This project aims to build a machine learning model to predict circuit failure based on temperature values, voltage values, and radiation measurements of different circuit components. The model will assist in early failure detection, ensuring proactive maintenance and improved system reliability.  

## Dataset 📁  
The dataset is provided in CSV format(available in the same directory) and contains the following columns:  

1. **V1 (Vaux Auxiliary Supply):** Expected value 1.8V  
2. **V2 (Vddr3 DDR Supply):** Expected value 1.35V  
3. **V3 (Vcore Core Supply):** Expected value 1V  
4. **V4 (Vtt):** Expected value 0.675V  
5. **V5 (Vcco Board Voltage):** Expected value 3.3V  
6. **T1 (Temperature of FPGA):** Temperature readings from FPGA  
7. **T2 (Temperature of PMIC):** Temperature readings from PMIC  
8. **Annotation:** Binary classification (0 -> OK, 1 -> Failure)  
9. **Timestamp:** Time of measurement  
10. **Radiation Rate (Gy/h):** Radiation exposure rate  

## Tasks ✅  
Each of the following target task is implemented in the jupyter notebook, codes available in the same directory.

### 1. Data Exploration 🔍  
- Explore the dataset to understand feature distributions.  
- Check for missing values in the dataset, if any, handle them appropriately.  
- Visualize relationships between different features and the target variable (failure status).  

### 2. Data Preprocessing 🛠️  
- Standardized or normalized numerical features.  

### 3. Feature Selection 🎯  
- Identify important features contributing to circuit failure prediction.  

### 4. Model Building 🤖  
- Split dataset into training and testing sets.  
- Implement and train at least two classification algorithms, such as Random Forest, Logistic Regression, or K-Nearest Neighbors.  

### 5. Model Evaluation 📊  
- Assess the performance of each model using metrics including:  
  - **Accuracy**  
  - **Precision**  
  - **Recall**  
  - **F1-score**  
- A comparison of different models was conducted.  

### 6. Hyperparameter Tuning ⚙️  
- Perform hyperparameter tuning to optimize model performance.  

### 7. Model Interpretation 🧐  
- Provide insights into the factors affecting the model's predictions.  
- Discuss challenges encountered during model development, along with potential solutions.  
 
