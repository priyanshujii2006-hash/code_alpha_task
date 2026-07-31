# 🌸 Iris Flower Classification

## 📌 Overview

This project builds a Machine Learning model to classify Iris flowers into one of three species:

* Setosa
* Versicolor
* Virginica

The model is trained using the famous Iris dataset available in **Scikit-learn**. Based on four flower measurements, it predicts the species with high accuracy.

---

## 📂 Dataset

The dataset is loaded directly from the **Scikit-learn** library.

* **Source:** https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_iris.html
* **Number of Samples:** 150
* **Features:** 4
* **Classes:** 3

### Features

* Sepal Length (cm)
* Sepal Width (cm)
* Petal Length (cm)
* Petal Width (cm)

### Target Classes

* Setosa
* Versicolor
* Virginica

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Joblib

---

## 🚀 Project Workflow

1. Import required libraries.
2. Load the Iris dataset.
3. Perform basic Exploratory Data Analysis (EDA).
4. Check for missing values and dataset information.
5. Split the dataset into training and testing sets.
6. Train a Logistic Regression model.
7. Make predictions on the test dataset.
8. Evaluate the model using:

   * Accuracy Score
   * Confusion Matrix
   * Classification Report
9. Save the trained model as a `.pkl` file using Joblib.

---

## 📊 Model Used

* Logistic Regression

---

## 📈 Model Evaluation

The model is evaluated using:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1-Score

Typical accuracy on the Iris dataset is around **96%–100%**, depending on the train-test split.

---

## 💾 Saved Model

The trained model is saved as:

```text
iris_flower_model.pkl
```

You can load it later using:

```python
import joblib

model = joblib.load("iris_flower_model.pkl")
```

---

## ▶️ How to Run

1. Clone this repository.

```bash
git clone <repository-link>
```

2. Install the required libraries.

```bash
pip install pandas numpy matplotlib scikit-learn joblib
```

3. Run the Jupyter Notebook or Python script.

4. Train the model.

5. Generate predictions and evaluate the results.

6. Save or load the trained model using Joblib.

---

## 📁 Project Structure

```text
Iris-Flower-Classification/
│
├── Iris_Flower_Classification.ipynb
├── iris_flower_model.pkl
├── README.md
└── requirements.txt
```

---

## 📚 Learning Outcomes

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Classification using Logistic Regression
* Model evaluation
* Saving and loading machine learning models
* Working with the Scikit-learn library

---

## 👨‍💻 Author

Developed as a Machine Learning project using Python and Scikit-learn.