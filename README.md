<H2>Heart Disease Prediction using Logistic Regression</H2> 
This project uses a Logistic Regression model to predict whether a person has heart disease based on various medical features. The dataset used is publicly available on Kaggle, and the implementation includes training, evaluation, prediction, and visualization of the results. <br><br>
<b> 📌 Overview </b><br>
Algorithm: Logistic Regression<br>
Dataset: Heart Disease dataset from Kaggle<br>
Tool: Jupyter Notebook<br>
Libraries Used: pandas, numpy, scikit-learn, matplotlib<br>
<br><br>
<b>📊 Features in the Dataset</b><br>
The dataset contains 1025 rows and 14 columns. Features include:<br>
age: Age of the person<br>
sex: Gender (1 = male; 0 = female)<br>
cp: Chest pain type (0–3)<br>
trestbps: Resting blood pressure (in mm Hg)<br>
chol: Serum cholesterol in mg/dl<br>
fbs: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)<br>
restecg: Resting electrocardiographic results (values 0,1,2)<br>
thalach: Maximum heart rate achieved<br>
exang: Exercise-induced angina (1 = yes; 0 = no)<br>
oldpeak: ST depression induced by exercise<br>
slope: The slope of the peak exercise ST segment<br>
ca: Number of major vessels (0–3) colored by fluoroscopy<br>
thal: Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect)<br>
target: 1 = Diseased heart, 0 = Healthy heart<br>
<br><br>
<b>🧪 Model Training and Evaluation</b><br>
Data split into training (80%) and test (20%) sets using train_test_split.<br>
Model trained using LogisticRegression from scikit-learn.<br>
Accuracy:<br>
Training Data: 85.24%<br>
Test Data: 80.49%<br>
<br><br>
<b>💡 Sample Prediction Logic</b><br>
Based on the prediction result:<br>
If 0: The person does NOT have heart disease<br>
If 1: The person HAS heart disease<br>
<br><br>
<b>📊 Visualization</b><br>
The prediction is also visualized using a simple bar chart:<br>
Green bar: Healthy Heart<br>
Red bar: Diseased Heart<br><br>

![Output](https://github.com/user-attachments/assets/a301ff2c-790d-47be-b3c4-45c703a9e8df)

<br>
<a href="https://heart-disease-prediction-0205.streamlit.app/"> Try the heart disease prediction model by clicking on this link </a>
