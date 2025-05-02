# 🌸 K-Nearest Neighbors (KNN) on Iris Dataset

## 📌 Objective
Build a K-Nearest Neighbors (KNN) model on the Iris dataset using only 2 features for simplicity and visualize decision boundaries.

## 🛠️ Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 📊 Dataset
- Iris dataset (available in `sklearn.datasets`)
- Used only two features: **sepal length** and **petal length** for 2D visualization

## 🔍 Workflow

### 1. Data Preparation
- Loaded the Iris dataset
- Selected two features for visualization
- Normalized features using `StandardScaler`
- Split the data into training and test sets (80/20)

### 2. Model Training
- Trained KNN models for different values of **K** (from 1 to 15)
- Evaluated accuracy for each K
- Found the best K based on accuracy

### 3. Evaluation
- Printed accuracy scores for each K
- Visualized accuracy vs. K
- Generated and plotted confusion matrix for the best K

### 4. Visualization
- Visualized decision boundaries for the best model
- Plotted class-wise data points for better understanding

## ✅ Best K Value
- Best accuracy achieved with **K = 13, 14, 15** (Accuracy = 100%)

## 📌 Output
- Accuracy scores
- Confusion matrix
- Decision boundary plot

## 🚀 Future Improvements
- Try with all 4 features using dimensionality reduction (e.g., PCA)
- Apply to other datasets
- Save the model using `joblib` or `pickle`

