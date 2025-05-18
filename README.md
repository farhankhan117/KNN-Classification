# K-Nearest Neighbors (KNN) Classification

## Objective  
Implement and understand the K-Nearest Neighbors (KNN) algorithm for classification using the Iris dataset. Normalize features, experiment with different values of K, evaluate model performance, and visualize decision boundaries.

## Tools & Libraries  
Python, Pandas, NumPy  
Scikit-learn  
Matplotlib

## Summary of Steps  
- Loaded Iris dataset from CSV and stored it in SQLite database  
- Loaded data back from SQLite for processing  
- Encoded categorical target variable (Species) using Label Encoding  
- Normalized feature columns using StandardScaler  
- Split data into training and testing sets  
- Trained KNN classifiers with different K values (1 to 10) and evaluated accuracy  
- Selected best K based on accuracy and generated confusion matrix  
- Visualized decision boundaries using first two normalized features

## Conclusion  
The KNN model achieved perfect accuracy on the Iris test set for all values of K tested, demonstrating the effectiveness of the algorithm on this dataset. Normalization proved essential for accurate distance calculations. Confusion matrix confirmed the model's classification performance, and decision boundary plots provided a visual understanding of how KNN separates classes. This project reinforces key concepts of instance-based learning, the importance of K selection, and feature scaling.

## Project Files  
- Iris.csv — Raw dataset  
- KNN_classification.ipynb — Complete KNN implementation code  
- README.md — This summary file


