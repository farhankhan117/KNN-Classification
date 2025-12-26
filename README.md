# 🌸 K-Nearest Neighbors (KNN) Classification

## 🎯 Objective
Implement and understand the **K-Nearest Neighbors (KNN)** algorithm for classification using the **Iris dataset**.  
This project focuses on feature normalization, experimenting with different values of **K**, evaluating model performance, and visualizing decision boundaries.

---

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- SQLite

---

## 🔍 Summary of Steps
### 1. Data Handling
- Loaded the Iris dataset from CSV
- Stored the dataset in an **SQLite database**
- Retrieved data from SQLite for processing

### 2. Data Preprocessing
- Encoded the categorical target variable (**Species**) using **Label Encoding**
- Normalized feature columns using **StandardScaler**

### 3. Train-Test Split
- Split the dataset into training and testing sets

### 4. Model Training & Evaluation
- Trained KNN classifiers with **K values from 1 to 10**
- Evaluated each model using **accuracy score**
- Selected the optimal K based on performance
- Generated a **confusion matrix** for detailed evaluation

### 5. Visualization
- Visualized **decision boundaries** using the first two normalized features
- Illustrated how KNN separates different classes in feature space

---

## 📊 Results & Insights
- Achieved **perfect classification accuracy** on the Iris test set for all tested K values
- Feature normalization proved essential for accurate distance-based classification
- Confusion matrix confirmed zero misclassifications
- Decision boundary plots provided intuitive insight into KNN behavior

---

## ✅ Conclusion
The KNN classifier demonstrated excellent performance on the Iris dataset, validating the effectiveness of **instance-based learning** for well-separated classes.  
This project reinforces:
- The importance of **feature scaling**
- The impact of **K selection**
- The interpretability of distance-based classifiers through visualization

---

## 📁 Project Files
- `Iris.csv` — Raw dataset  
- `KNN_classification.ipynb` — Complete KNN implementation  
- `README.md` — Project documentation  

---

## 🚀 Future Improvements
- Apply KNN to higher-dimensional datasets
- Use cross-validation for optimal K selection
- Compare KNN with other classifiers (SVM, Logistic Regression)
- Implement weighted KNN



---
