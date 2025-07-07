# 🎓 Student Performance Prediction using Linear Regression

This project presents a supervised machine learning solution for predicting student performance based on study hours using a simple **linear regression model**. The implementation is structured in a Jupyter Notebook and serves as a foundational example for understanding regression techniques in data science.

---

## 📌 Problem Statement

The objective is to predict the **percentage score of a student** given the number of hours they study per day. This is a classic single-variable linear regression problem, ideal for demonstrating core ML workflows — from data preprocessing to model evaluation.

---

## 📁 Project Files

* `project.ipynb` – Main notebook containing:

  * Data exploration and visualization
  * Model training using `LinearRegression` from scikit-learn
  * Evaluation and prediction

---

## 🔧 Technologies Used

| Tool/Library     | Purpose                             |
| ---------------- | ----------------------------------- |
| Python (3.x)     | Core programming language           |
| Pandas           | Data manipulation and analysis      |
| NumPy            | Numerical computations              |
| Matplotlib       | Data visualization                  |
| Scikit-learn     | Machine learning model & evaluation |
| Jupyter Notebook | Interactive notebook environment    |

---

## 📊 Workflow Overview

1. **Data Loading**

   * The dataset is read using `pandas`.
   * Basic data inspection is performed.

2. **Exploratory Data Analysis (EDA)**

   * A scatter plot is used to understand the relationship between hours studied and scores.

3. **Model Training**

   * The data is split into training and test sets.
   * A linear regression model is fitted on the training data.

4. **Prediction & Evaluation**

   * Predictions are made on test data.
   * Performance is evaluated using metrics like Mean Absolute Error and R² Score.
   * A sample prediction is performed (e.g., for 9.25 hours of study).

---

## 📈 Sample Output

```
Predicted Score for 9.25 hours of study: 93.89%
Model R² Score: 0.95
Mean Absolute Error: 4.18
```

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

* Python 3.x
* Jupyter Notebook
* pip (Python package manager)

### Installation

```bash
git clone https://github.com/yourusername/student-performance-linear-regression.git
cd student-performance-linear-regression
pip install -r requirements.txt
jupyter notebook
```

> *Alternatively, open the notebook in [Google Colab](https://colab.research.google.com/) for an in-browser experience.*

---

## 📌 Use Case

This project is suitable for:

* Beginners in machine learning
* Students exploring regression models
* Academic demonstrations
* Portfolio building

---

## ✅ Results & Observations

* There is a **positive linear relationship** between study time and performance.
* The linear regression model demonstrates high accuracy for this dataset.
* Suitable for extending to multivariable regression and other supervised models.

---

## 📃 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙋‍♂️ Acknowledgements

This project is inspired by simple regression use-cases in academic ML curricula and publicly available datasets used for educational purposes.

---

