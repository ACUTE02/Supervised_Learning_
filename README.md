# 🚢 Titanic Survival Prediction using Multiple Machine Learning Models

### Comparing Machine Learning Algorithms on the Titanic Dataset

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

---

# 📖 Overview

This project predicts whether a passenger survived the Titanic disaster using multiple Machine Learning classification algorithms.

Instead of relying on a single model, this project compares the performance of several popular ML algorithms after applying data preprocessing and feature engineering.

The implementation is available in both:

- 📓 Google Colab Notebook (`titanic_multiple_model.ipynb`)
- 💻 Python Script (`titanic_multiple_model.py`)

making it easy to run in different development environments.

---

# 📂 Repository Structure

```text
Titanic-Multiple-ML-Models/
│
├── titanic_multiple_model.ipynb
├── titanic_multiple_model.py
└── README.md
```

---

# 📊 Dataset

The project uses the **Titanic dataset** provided by the Seaborn library.

The dataset contains passenger information such as:

- Passenger Class
- Age
- Gender
- Fare
- Number of Siblings/Spouses
- Parents/Children
- Embarkation Port

Target Variable

```
Survived
```

---

# ⚙ Data Preprocessing

The following preprocessing steps are performed before training the models:

✅ Remove unnecessary columns

```python
deck
embark_town
alive
adult_male
class
who
```

✅ Fill missing values

```python
Age → Mean Imputation
```

✅ Remove remaining missing records

```python
Embarked
```

✅ Label Encoding

- Sex
- Embarked

✅ Feature Scaling

Using

```python
StandardScaler
```

for algorithms that require normalized features.

---

# 🤖 Machine Learning Models

The following models are implemented and compared:

### ✅ Logistic Regression

Used as the baseline classification model.

---

### ✅ K-Nearest Neighbors (KNN)

- Feature Scaling
- Euclidean Distance
- K = 5

---

### ✅ Gaussian Naive Bayes

Fast probabilistic classifier.

---

### ✅ Decision Tree Classifier

Configured using

```python
random_state = 42
```

---

### ✅ Support Vector Machine (SVM)

Kernel Used

```python
RBF Kernel
```

---

# 📈 Model Evaluation

Each model is evaluated using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1 Score
- Classification Report

This allows easy comparison of model performance.

---

# 📚 Python Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/your-username/Titanic-Multiple-ML-Models.git
```

Move into the project

```bash
cd Titanic-Multiple-ML-Models
```

Install dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

Run the Python version

```bash
python titanic_multiple_model.py
```

Or open the notebook

```bash
jupyter notebook titanic_multiple_model.ipynb
```

---

# 📊 Workflow

```
Titanic Dataset
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Label Encoding
        │
        ▼
Feature Scaling
        │
        ▼
Train-Test Split
        │
        ▼
Train Multiple Models
        │
        ▼
Model Evaluation
        │
        ▼
Performance Comparison
```

---

# 📌 Skills Demonstrated

- Data Cleaning
- Missing Value Handling
- Label Encoding
- Feature Scaling
- Train-Test Split
- Classification Algorithms
- Model Comparison
- Performance Evaluation
- Machine Learning Pipeline
- Exploratory Data Analysis

---

# 🎯 Learning Outcomes

This project demonstrates how to:

- Prepare real-world datasets for machine learning
- Compare multiple classification algorithms
- Evaluate models using standard classification metrics
- Understand when feature scaling is required
- Build a complete end-to-end ML classification workflow

---

# 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

# 👨‍💻 Author

**Ayushmaan Gupta**

🎓 B.Tech CSE (AI & ML)

### Interests

- Artificial Intelligence
- Machine Learning
- Deep Learning
- Data Science
- Computer Vision

---

# ⭐ Support

If you found this project helpful,

⭐ Star this repository

🍴 Fork the project

📢 Share it with others

---

<div align="center">

**Made with ❤️ by Ayushmaan Gupta**

*"Machine Learning is not about choosing one algorithm—it's about understanding which one works best for your data."*

</div>
