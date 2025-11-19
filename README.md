# Iris_Classification
This project implements a Machine Learning model to classify Iris flowers into three species — Setosa, Versicolor, and Virginica — based on their petal and sepal measurements. The dataset used is the famous Iris dataset by Ronald Fisher, widely used for introductory ML tasks.

Objectives
Analyze and understand the Iris dataset.
Visualize feature distributions and relationships.
Build and train different ML models.
Evaluate model performance using accuracy and metrics.
Save and deploy the final model.

Dataset Description
The dataset contains 150 samples with 4 input features and 1 target label.
Feature
Description
Sepal Length
Length of the sepal (cm)
Sepal Width
Width of the sepal (cm)
Petal Length
Length of the petal (cm)
Petal Width
Width of the petal (cm)

Target Labels:
0 → Iris Setosa
1 → Iris Versicolor
2 → Iris Virginica

Technologies Used
Python
NumPy, Pandas
Matplotlib, Seaborn
Scikit-Learn
Jupyter Notebook

Data Preprocessing
Steps involved:
Load dataset
Handle missing values (if any)
Encode target labels
Train-test split
Feature scaling (optional)

Exploratory Data Analysis
Common visualizations:
Pairplot to see feature relationships
Heatmap for feature correlation
Distribution plots

Model Training
Machine Learning models used:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
K-Nearest Neighbors
Trained using train_test_split.
Evaluated using metrics like:
Accuracy
Confusion Matrix
Classification Report

Best Model
Model Name: Random Forest Classifier (example)
Accuracy: 96-99% (approx)
Pros: Robust, handles feature variance, low overfitting

Model Saving
import joblib
joblib.dump(model, 'iris_model.pkl')
This saves the model for future deployment.

Deployment (Future Scope)
You can deploy this model using:
Flask / FastAPI (Web API)
Streamlit / Gradio (UI-based apps)
Docker (Containerization)

Results Summary
Model
Accuracy
Logistic Regression
95%
Decision Tree
93%
Random Forest
97%
KNN
96%




# Run the notebook
jupyter notebook notebooks/iris.ipynb

Conclusion
Iris classification is a classic ML project suitable for beginners. It introduces EDA, model comparison, and deployment fundamentals. Random Forest performed best with near-perfect accuracy.


