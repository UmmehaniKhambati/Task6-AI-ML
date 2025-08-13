# Task6-AI-ML
# K-Nearest Neighbors (KNN) Classification 

#Objective
Implemented the K-Nearest Neighbors algorithm to classify iris flowers into three species based on sepal and petal measurements.

#Dataset
Source: Iris Dataset (Kaggele)
Features: sepal_length, sepal_width, petal_length, petal_width
Target: species

#Steps
1. Loaded and explored dataset.
2. Split into train (80%) and test (20%).
3. Normalized features using StandardScaler.
4. Trained KNN with k=5.
5. Evaluated using accuracy, confusion matrix, and classification report.
6. Tested multiple K values (1–20).
7. Visualized decision boundaries for both sepal and petal features.

#Results
Accuracy: 1.00 (100%)
Confusion Matrix:

All K values from 1 to 20 achieved perfect accuracy on this dataset.

#Decision Boundary Insights
Sepal features show more class overlap.
Petal features provide clear separation between species.
