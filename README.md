
# 🌸 KNN Classification on Iris Dataset

## Objective

The objective of this project is to implement the **K-Nearest Neighbors (KNN)** algorithm for classification using the **Iris dataset**. The project covers the following tasks:

1. **Data Preprocessing**: Loading the dataset, storing it in an SQLite database, normalizing the features, and encoding labels.
2. **Model Implementation**: Training a KNN model using the scikit-learn library, and experimenting with different values of K to identify the best model.
3. **Model Evaluation**: Evaluating the model using metrics such as accuracy, confusion matrix, and visualizing decision boundaries.
4. **Visualization**: Visualizing the decision boundaries of the trained model using the first two features of the dataset.

This project helps understand **instance-based learning**, the role of **distance metrics**, and how KNN handles **multi-class classification** problems.

---

## 📁 Files in this Repository

- `KNN_Iris_Classification.ipynb`: Jupyter Notebook containing the full implementation of KNN for classification.
- `Iris.csv`: The Iris dataset in CSV format.
- `database.sqlite`: SQLite database storing the Iris dataset for easy access during model training.
- `README.md`: Project overview and instructions for setup and execution.

---

## ✅ Task Checklist

- [x] Loaded the Iris dataset and stored it in an SQLite database for efficient querying.
- [x] Preprocessed the data by normalizing features and encoding the target labels.
- [x] Implemented KNN using `KNeighborsClassifier` from scikit-learn.
- [x] Evaluated model accuracy for K values ranging from 1 to 10.
- [x] Displayed the confusion matrix for the best-performing K value.
- [x] Visualized decision boundaries using the first two normalized features.

---

## 📊 Tools & Libraries

- **Python**: Programming language used for implementation.
- **Pandas**: Data manipulation and analysis.
- **SQLite3**: Database for storing and querying the Iris dataset.
- **scikit-learn**: Machine learning library used for implementing KNN and model evaluation.
- **Matplotlib**: Used for plotting confusion matrices and decision boundaries.

---

## 🧠 Key Concepts Covered

- **Instance-based learning**: KNN is a non-parametric algorithm that makes predictions based on the closest training examples in the feature space.
- **Euclidean distance**: The primary distance metric used to measure similarity between data points in KNN.
- **Feature normalization**: Standardizing features to have zero mean and unit variance to ensure each feature contributes equally to the distance metric.
- **Multi-class classification**: KNN can handle problems where there are more than two classes.
- **Visualization**: Visualizing decision boundaries to understand how the model classifies different regions of the feature space.

---



---


---



---

