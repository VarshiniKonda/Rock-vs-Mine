# Rock vs Mine Prediction using Machine Learning

## 📌 Project Overview

This project uses Machine Learning to classify SONAR signals and predict whether an underwater object is a **Rock** or a **Mine**.

The project demonstrates the complete machine learning workflow, including data loading, preprocessing, exploratory data analysis, model training, evaluation, and prediction.

## 🎯 Objective

The main objective is to build a machine learning classification model that can identify whether the given SONAR signal represents a rock or a mine.

## 📊 Dataset

The project uses a SONAR dataset containing numerical features representing SONAR signal measurements.

- **Samples:** 208
- **Features:** 60 numerical features
- **Target:** Rock (R) or Mine (M)

The dataset is commonly used for binary classification using SONAR signal data.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab / Jupyter Notebook

## 🔄 Project Workflow

```text
SONAR Dataset
      ↓
Data Loading
      ↓
Data Exploration
      ↓
Data Preprocessing
      ↓
Train-Test Split
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Rock / Mine Prediction
```

## 🧹 Data Preprocessing

The dataset is loaded into a Pandas DataFrame and prepared for machine learning.

The preprocessing steps include:

- Loading the dataset
- Checking dataset shape and information
- Separating features and target labels
- Analyzing class distribution
- Splitting the data into training and testing sets

## 🤖 Machine Learning Model

A **Logistic Regression** model is used for binary classification.

The model is trained using the training dataset and then used to predict whether new SONAR input data represents a Rock or a Mine.

## 📈 Model Evaluation

The model performance is evaluated using **Accuracy Score**.

Additional classification evaluation can include:

- Accuracy
- Confusion Matrix
- Classification Report

## 🔮 Prediction

After training, the model can accept SONAR feature values as input and generate a prediction:

```text
R → Rock
M → Mine
```

## 📁 Project Structure

```text
Rock-Vs-Mine-Prediction/
│
├── sonar_data.csv
├── Rock_Vs_Mine_Prediction.ipynb
├── README.md
└── requirements.txt
```

> Update the file names above if your actual GitHub files have different names.

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Open the project

Open the Jupyter Notebook in **Google Colab** or **Jupyter Notebook**.

### 3. Install required libraries

```bash
pip install pandas numpy scikit-learn matplotlib
```

### 4. Run the notebook

Run the notebook cells sequentially to load the dataset, train the model, evaluate its performance, and generate predictions.

## 📚 Key Learning Outcomes

- Understanding supervised machine learning
- Working with SONAR datasets
- Data preprocessing and exploration
- Binary classification
- Logistic Regression
- Model evaluation
- Making predictions using a trained ML model

## ⚠️ Disclaimer

This project is developed for **educational and academic purposes** to demonstrate a machine learning classification workflow.

## 👩‍💻 Author

**Konda Naga Vinaya Sri Varshini**

GitHub: https://github.com/VarshiniKonda
