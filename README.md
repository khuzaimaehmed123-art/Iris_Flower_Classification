🌸 Iris Flower Classification using Machine Learning

📌 Project Overview

This project is part of CodeAlpha Internship – Task 1 and focuses on building a Machine Learning classification model to predict the species of an Iris flower based on its sepal and petal measurements.

The project follows a complete Machine Learning workflow, including data loading, data exploration, cleaning, visualization, model training, evaluation, feature importance analysis, model saving, and sample prediction.

🛠️ Technologies & Libraries

* Python
* Pandas – Data manipulation and analysis
* NumPy – Numerical operations
* Matplotlib – Data visualization
* Seaborn – Statistical visualization
* Scikit-learn – Machine Learning
* Joblib – Saving the trained model

📊 Dataset

The project uses the Iris dataset, containing measurements of:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

The model classifies flowers into three species:

* Iris-setosa
* Iris-versicolor
* Iris-virginica

🔍 Project Workflow

1. Loaded the Iris dataset using Pandas.
2. Explored the dataset using head(), shape, info(), and describe().
3. Checked for missing values and unique flower species.
4. Removed the unnecessary Id column.
5. Performed Exploratory Data Analysis (EDA).
6. Created species count plots, pair plots, and a correlation heatmap.
7. Split the dataset into 80% training and 20% testing data.
8. Built a Random Forest Classifier with 100 estimators.
9. Trained the Machine Learning model.
10. Evaluated the model using:

* Accuracy Score
* Classification Report
* Confusion Matrix

11. Analyzed feature importance.
12. Saved the trained model as model.pkl using Joblib.
13. Performed a sample prediction using new flower measurements.

🤖 Machine Learning Model

The project uses the Random Forest Classifier, an ensemble learning algorithm that combines multiple decision trees to make reliable classification predictions.

📈 Visualizations

The project generates the following visualizations:

* Species Count Plot
* Pair Plot
* Correlation Heatmap
* Confusion Matrix
* Feature Importance Chart

🧪 Sample Prediction

The trained model is tested with sample measurements:

Sepal Length: 5.1
Sepal Width: 3.5
Petal Length: 1.4
Petal Width: 0.2

The model predicts the corresponding Iris species based on these measurements.

📁 Project Files

Iris-Flower-Classification/
│
├── Iris.csv
├── iris_classification.py
├── model.pkl
├── species_count.png
├── pairplot.png
├── heatmap.png
├── confusion_matrix.png
├── feature_importance.png
└── README.md

🎯 Learning Outcomes

Through this project, I strengthened my practical understanding of the Machine Learning pipeline, including data preprocessing, EDA, classification, model evaluation, feature importance, and model persistence.

This project also helped me gain hands-on experience with Python-based Data Science tools and understand how Machine Learning can be applied to real-world classification problems.

🚀 Future Improvements

* Build a user-friendly prediction interface.
* Deploy the model as a web application.
* Add more datasets and classification algorithms.
* Compare Random Forest with other Machine Learning models.
* Create an interactive dashboard for predictions and analysis.

⸻

Developed as part of CodeAlpha Internship – Task 1.
Author: Khuzaima Ehmed
