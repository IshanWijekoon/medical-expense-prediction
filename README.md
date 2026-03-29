# Medical Insurance Cost Prediction

A simple machine learning project to predict **annual medical insurance charges** based on customer information such as:

- Age
- Sex
- BMI
- Number of children
- Smoking status
- Region

This project focuses on **data analysis, visualization, and linear regression modeling** using Python.

---

## 📌 Project Objective

The goal of this project is to build a model that can estimate a person's **medical insurance charges** using historical customer data.

---

## 📂 Dataset Features

The dataset contains the following columns:

- `age` – Age of the customer
- `sex` – Gender
- `bmi` – Body Mass Index
- `children` – Number of dependents
- `smoker` – Smoking status
- `region` – Residential region
- `charges` – Annual medical cost (**target variable**)

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn

---

## 📊 Project Workflow

### 1. Data Loading
- Loaded the insurance dataset
- Inspected rows, columns, and data types

### 2. Data Exploration
- Checked basic statistics
- Analyzed feature distributions
- Observed target variable behavior

### 3. Data Visualization
Visualized relationships between features and charges using:

- Histograms
- Box plots
- Scatter plots
- Correlation analysis

### 4. Key Insights
Some important findings from the analysis:

- **Smokers have significantly higher medical charges**
- **Age has a positive relationship with charges**
- **BMI also affects insurance cost**
- The `charges` column is **right-skewed**

### 5. Model Building
- Built a simple **Linear Regression** model
- Used **age** as the input feature for initial prediction
- Predicted insurance charges for non-smokers

### 6. Model Evaluation
- Compared predicted vs actual values
- Used **RMSE (Root Mean Squared Error)** to measure performance

---

## 🤖 Machine Learning Model

Model used:

- **Linear Regression**

This project demonstrates the basics of how regression can be used to estimate real-world costs.

---

## 📈 Example Output

The model predicts medical charges based on input values and compares them against actual customer charges.

Example:
- Age: 23 → Predicted insurance charge
- Age: 37 → Predicted insurance charge
- Age: 61 → Predicted insurance charge

---

## 📁 Project Structure

```bash
Medical-Insurance-Cost-Prediction/
│
├── prediction.ipynb
├── README.md
└── dataset.csv   # if included