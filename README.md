# Heart Disease Prediction using XGBoost & ANN

## Project Overview
This project focuses on predicting the risk of heart disease using machine learning techniques, including XGBoost and Artificial Neural Networks (ANN). The goal was to analyze medical records, identify key risk factors, and develop an accurate predictive model.

## Key Features
✔ **Data Analysis**: Explored 300K+ medical records to uncover trends in heart disease risk factors  
✔ **Machine Learning**: Built and compared KNN, XGBoost, and ANN models, achieving 91.9% accuracy  
✔ **Deep Learning**: Designed a Neural Network with BatchNorm & Dropout to enhance generalization  
✔ **Model Evaluation**: Assessed performance using precision, recall, F1-score
✔ **Visual Insights**: Generated heatmaps, histograms, and count plots to highlight key findings  

## Technologies Used
### Programming Language
- Python

### Libraries
- **Data Handling**: Pandas, NumPy  
- **Machine Learning**: Scikit-learn, XGBoost  
- **Deep Learning**: TensorFlow/Keras  
- **Visualization**: Matplotlib, Seaborn  

## Project Workflow

### 1. Data Analysis & Preprocessing
- Conducted Exploratory Data Analysis (EDA) using correlation heatmaps and distribution plots  
- Applied Label Encoding for categorical variables and MinMax Scaling for normalization  
- Detected and removed duplicates to ensure clean, reliable data  

### 2. Model Development
- KNN, XGBoost, and ANN models were trained and compared  
- XGBoost was fine-tuned for optimal performance  

**ANN Architecture**:
- Input Layer (64 neurons, ReLU)  
- Hidden Layers (128 & 64 neurons, BatchNorm, Dropout)  
- Output Layer (Sigmoid for binary classification)  

### 3. Evaluation & Insights
- Evaluated models using precision, recall, F1-score
- Identified class imbalance issues (low recall for positive cases)  
- Visualized key risk factors (age, BMI, exercise) impacting heart disease  

## Results & Impact
- Achieved 91.9% accuracy in predicting heart disease risk  
- Demonstrated the ability to process large datasets and extract actionable insights  
- Highlighted opportunities for improving recall in medical diagnostics  
