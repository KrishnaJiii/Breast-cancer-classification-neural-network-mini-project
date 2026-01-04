

# 🧠 Breast Cancer Classification with Neural Network (NN)

This project implements a **Neural Network–based classification model** to predict whether a breast tumor is **malignant or benign** using the **Breast Cancer Wisconsin dataset** provided by sklearn.

The work is done entirely in a **Jupyter Notebook** and demonstrates an end-to-end machine learning workflow using Python.

---

## 📌 Project Description

The objective of this project is to build and evaluate a **Neural Network classifier** that can accurately classify breast cancer cases based on medical features extracted from digitized images of breast mass tissue.

The dataset is loaded using:

```python
sklearn.datasets.load_breast_cancer
```

It contains real-world medical data and is widely used for binary classification tasks.

---

## 📊 Dataset Details

* **Total Samples:** 569
* **Features:** 30 numerical features
* **Classes:**

  * `0` → Malignant
  * `1` → Benign

### Class Distribution

* **Malignant:** 212 samples
* **Benign:** 357 samples

### Dataset Attributes

* `data` → Feature matrix of shape `(569, 30)`
* `target` → Class labels
* `feature_names` → ['mean radius',
 'mean texture',
 'mean perimeter',
 'mean area',
 'mean smoothness',
 'mean compactness',
 'mean concavity',
 'mean concave points',
 'mean symmetry',
 'mean fractal dimension',
 'radius error',
 'texture error',
 'perimeter error',
 'area error',
 'smoothness error',
 'compactness error',
 'concavity error',
 'concave points error',
 'symmetry error',
 'fractal dimension error',
 'worst radius',
 'worst texture',
 'worst perimeter',
 'worst area',
 'worst smoothness',
 'worst compactness',
 'worst concavity',
 'worst concave points',
 'worst symmetry',
 'worst fractal dimension']
* `target_names` → Class labels (`malignant`, `benign`)

---

## ⚙️ Workflow Followed

1. Importing required libraries
2. Loading the breast cancer dataset
3. Data exploration and understanding
4. Data preprocessing and scaling
5. Building a Neural Network model
6. Training the model
7. Evaluating model performance
8. Analyzing results

---

## 🛠️ Technologies & Libraries Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Scikit-learn
* TensorFlow, Keras 
* Matplotlib, Seaborn 

---

## 📂 Project Structure

```
├── Breast_Cancer_Classification.ipynb
├── README.md
```

---


## 📈 Results & Conclusion

The Neural Network model successfully learns patterns from the dataset and is able to classify tumors as **malignant or benign** with good accuracy.
This project demonstrates the effectiveness of neural networks in **medical diagnosis–related classification problems**.

---

## 🎯 Learning Outcomes

* Understanding real-world medical datasets
* Hands-on experience with Neural Networks
* Practical use of `sklearn` datasets
* Model training and evaluation techniques
* Improved confidence in ML project implementation

