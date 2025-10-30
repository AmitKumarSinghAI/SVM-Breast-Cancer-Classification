# 🧠 Support Vector Machines (SVM) – Breast Cancer Classification

## 📌 Overview
This project implements **Support Vector Machines (SVM)** for both **linear** and **non-linear classification** using the **Breast Cancer dataset**.  
The notebook covers **EDA, hyperparameter tuning, cross-validation**, and **PCA-based decision boundary visualization**.

---

## 📂 Project Structure
SVM-Breast-Cancer-Classification/
│-- svm_task7.py # Main Python script
│-- README.md # Project documentation
│-- requirements.txt # Required Python packages
│-- dataset/ # Dataset (optional, sklearn loads it internally)
│-- screenshots/ # Plots & outputs


---

## 🛠 Technologies Used
- **Python 3**
- **Scikit-learn**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**

---

## 📊 Exploratory Data Analysis (EDA)
- Class distribution visualization  
- Correlation heatmap  
- Summary statistics of features  

---

## ⚙️ Model Training
- SVM with **Linear Kernel**
- SVM with **RBF Kernel**
- Hyperparameter tuning using **GridSearchCV**
- Model evaluation using **classification report** & **confusion matrix**
- Cross-validation for performance validation

---

## 🎯 PCA-based Decision Boundary
Since the dataset is high-dimensional, **PCA (Principal Component Analysis)** is used to reduce features to 2 dimensions for visualization.  
The decision boundary plot shows how the SVM separates the two cancer classes.

---

## 📈 Results
- Best accuracy achieved with **RBF Kernel** after hyperparameter tuning.
- Model performs well on both train and test data with minimal overfitting.

---

## 📥 Installation & Usage
```bash
# Clone the repository
git clone https://github.com/<your-username>/SVM-Breast-Cancer-Classification.git

# Navigate into the folder
cd SVM-Breast-Cancer-Classification

# Install dependencies
pip install -r requirements.txt

