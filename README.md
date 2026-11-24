Diabetes Prediction Using Machine Learning

 1. Project Description

Diabetes Prediction is a Machine Learning project that aims to predict whether a person is diabetic or non-diabetic based on medical diagnostic information.

This project uses the Pima Indians Diabetes Dataset to train and evaluate different machine learning algorithms. The dataset contains medical attributes such as Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function and Age.

The project compares multiple machine learning models to identify which algorithm provides better prediction performance.

 2. Algorithms Used

The following four machine learning algorithms are implemented:

1. **Logistic Regression:** Used for predicting diabetes by classifying data into two categories.
2. **K-Nearest Neighbors (KNN):** Classifies a person based on the nearest data points.
3. **Decision Tree:** Uses decision rules to predict whether a person is diabetic.
4. **Random Forest:** Combines multiple decision trees to improve prediction performance.

 3. Technologies Used

- Python
- Jupyter Notebook
- Pandas – Data manipulation and analysis
- NumPy – Numerical operations
- Matplotlib – Data visualization
- Seaborn – Statistical visualization
- Scikit-learn – Machine learning model implementation and evaluation

 4. Dataset

**Dataset:** Pima Indians Diabetes Dataset

The dataset contains medical information used to predict the diabetes outcome.

- 0 – Non-Diabetic
- 1 – Diabetic

5. Model Performance

The models are evaluated using Accuracy, Precision, Recall and F1-Score.

| Algorithm | Accuracy |
|---|---:|
| Logistic Regression | 70.8% |
| K-Nearest Neighbors | 75.3% |
| Decision Tree | 68.2% |
| Random Forest | 76.6% |

Random Forest achieved the highest accuracy among the four evaluated models in this experiment.

 6. Evaluation and Visualization

The project includes:
- Classification reports
- Confusion matrices
- Model performance comparison
- Feature importance visualization
- Graphical representation of results

7. Conclusion

This project demonstrates how machine learning algorithms can be applied to diabetes prediction using medical data. Among the four models tested, Random Forest achieved the highest accuracy of approximately 76.6%.

The project provides a comparison of different classification algorithms and demonstrates the importance of machine learning in healthcare-related data analysis.

 8. Project Files

- `ml case study.html` – Notebook exported as an HTML file.
- `ml case study-checkpoint.ipynb` – Jupyter Notebook.
- `Dataset 1` – Pima Indians Diabetes Dataset.
