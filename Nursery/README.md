# 👨‍💻 Nursery Admission Prediction – Machine Learning Project

A Machine Learning project that predicts nursery school admission decisions based on family, financial, and social conditions using classification algorithms.

---

# 📌 Project Overview

This project uses the **Nursery Dataset** to build machine learning models that classify nursery school applications into different recommendation categories.

The dataset was originally created to evaluate and rank nursery school applicants when demand exceeded available seats.

The goal of this project is to:

- Perform data preprocessing
- Train multiple ML classification models
- Evaluate performance
- Compare algorithms
- Identify the best-performing model

---

# 📂 Dataset Information

**Dataset:** Nursery Dataset  
**Source:** UCI Machine Learning Repository

### Key Details

- Instances: **12,960**
- Features: **8 categorical attributes**
- Task: **Multi-class Classification**

---

# 📊 Features

| Feature | Description |
|---|---|
| parents | Parents' occupation |
| has_nurs | Child's previous nursery |
| form | Family structure |
| children | Number of children |
| housing | Housing conditions |
| finance | Financial status |
| social | Social conditions |
| health | Health conditions |

---

# 🎯 Target Variable

Admission recommendation categories:

- `not_recom`
- `recommend`
- `very_recom`
- `priority`
- `spec_prior`

---

# ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 🧠 Machine Learning Models

Models that can be used in this project:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors
- Naive Bayes
- Gradient Boosting

---

# 🔬 Project Workflow

## 1. Data Loading
- Import dataset
- Assign column names
- Inspect dataset

## 2. Data Preprocessing
- Encode categorical variables
- Train-test split
- Feature scaling (if required)

## 3. Exploratory Data Analysis
- Class distribution
- Feature analysis
- Visualizations

## 4. Model Training
Train different machine learning models.

## 5. Evaluation

Evaluation metrics used:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## 6. Model Comparison
Select the best-performing model.

---

# 📈 Example Results

| Model | Accuracy |
|---|---|
| Logistic Regression | ~90–95% |
| Decision Tree | ~99% |
| Random Forest | ~98% |
| SVM | ~97% |

*Results may vary depending on preprocessing and tuning.*

---

# 📁 Project Structure

```
Nursery/
│
├── Nursery.ipynb
├── nursery.csv
├── README.md
└── requirements.txt
```

---

# ▶️ How to Run

### 1 Clone Repository

```bash
git clone https://github.com/XC0ID/ML-Projects.git
cd ML-Projects/Nurse
```

### 2 Install Dependencies

```bash
pip install -r requirements.txt
```

### 3 Run Notebook

```bash
jupyter notebook
```

Open the notebook and run all cells.

---

# 🚀 Future Improvements

- Hyperparameter tuning
- Deep learning models
- Model deployment
- Web application (Streamlit / Flask)
- Better feature engineering

---
