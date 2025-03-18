# 🌸 Iris Flower Classification

## 📌 Project Overview  
This project builds a **machine learning model** to classify **Iris flowers** into three species/varieties:  
- **Setosa**  
- **Versicolor**  
- **Virginica**  

### 🚀 Key Objectives:
✔ Train multiple ML models and compare their accuracy.  
✔ Identify **most significant features** influencing classification.  
✔ Analyze **feature importance for tree-based models**.  
✔ Present a **clear evaluation of model performance**.

---

## 📊 Dataset Information  
- **Source**: `iris.csv`  
- **Features**:
  - `sepal_length`
  - `sepal_width`
  - `petal_length`
  - `petal_width`
- **Target**: `variety` (Setosa, Versicolor, Virginica)

---

## ⚙️ Models Used
The following models were trained and compared:
1. **Random Forest**
2. **Support Vector Machine (SVM)**
3. **K-Nearest Neighbors (KNN)**
4. **Logistic Regression**
5. **Decision Tree**
6. **AdaBoost**
7. **XGBoost**
8. **Neural Network (MLPClassifier)**

---

## 📌 Steps in the Notebook
1️⃣ **Data Preprocessing**  
   - Encode categorical labels (`species`).  
   - Split data into **training (80%)** and **testing (20%)**.  
   - Standardize features using `StandardScaler`.  

2️⃣ **Model Training & Evaluation**  
   - Train and compare **multiple classifiers**.  
   - Evaluate models using:  
     - **Accuracy Score**
     - **Classification Report**  
   - Identify **best-performing models**.  

3️⃣ **Feature Importance Analysis**  
   - Extract feature importance from **tree-based models**.  
   - **Visualize** which features contribute most.

---

## 📈 Results
- The **best-performing models** are displayed.  
- Feature importance is analyzed for **top tree-based models**.  
- The notebook provides **clear evaluation metrics and visualizations**.

---

## 📁 File Structure
📂 Iris
│── 📜 Iris_classifier.ipynb # Jupyter Notebook with full implementation
│── 📜 iris.csv # Dataset
│── 📜 README.md # Project documentation

## 🛠️ Installation & Usage  
### **🔹 Install Dependencies**  
pip install pandas numpy scikit-learn matplotlib seaborn xgboost jupyter
🔹 Run the Notebook: jupyter notebook Iris_classifier.ipynb
