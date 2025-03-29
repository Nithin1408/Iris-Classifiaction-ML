# Iris-Classifiaction-ML
📌 Overview

This project implements Machine Learning techniques to classify the famous Iris dataset into three species:

Setosa

Versicolor

Virginica

The dataset contains sepal length, sepal width, petal length, and petal width as features to predict the species.

📂 Dataset
The dataset used is the Iris dataset, which is publicly available on the UCI Machine Learning Repository.

Feature	Description
Sepal Length	Length of the sepal (cm)
Sepal Width	Width of the sepal (cm)
Petal Length	Length of the petal (cm)
Petal Width	Width of the petal (cm)
Species	Target variable (Setosa, Versicolor, Virginica)

⚙️ Tech Stack
🔹 Python
🔹 Pandas, NumPy
🔹 Scikit-Learn (Machine Learning)
🔹 Matplotlib, Seaborn (Visualizations)

🛠️ Installation & Setup
🔹 1. Clone the Repository
git clone https://github.com/Nithin1408/Iris-Classification-ML.git
cd Iris-Classification-ML
🔹 2. Install Dependencies
pip install pandas numpy scikit-learn matplotlib seaborn
🔹 3. Run the Jupyter Notebook
jupyter notebook
Then, open Iris_Classification.ipynb and run all cells.

🚀 Features & Implementation
🔹 1. Data Exploration
Loaded dataset using pandas

Checked for missing values and outliers

Performed visualizations (Pair plots, histograms)

🔹 2. Preprocessing & Feature Engineering
Standardized numerical features using StandardScaler

Split data into training (80%) and testing (20%)

🔹 3. Model Training & Evaluation
Trained multiple models: ✅ Logistic Regression
✅ K-Nearest Neighbors (KNN)
✅ Support Vector Machine (SVM)
✅ Random Forest

Evaluated models using:
✅ Accuracy Score
✅ Confusion Matrix
✅ Classification Report

📊 Results
After training, the best-performing model achieved an accuracy of 100% on the test set.
