🌳 Decision Tree & Random Forest Classifier --- Practice Project 03

A hands-on Machine Learning practice notebook comparing Decision
Tree and Random Forest classifiers on two Seaborn datasets:
Iris and Tips.

📌 Project Overview:

This project demonstrates a basic classification workflow, from
exploring data and preparing features to training models and evaluating
their performance.

Datasets:
-> Iris: Predicts the flower species using sepal and petal
measurements (3 classes).

-> Tips: Predicts the meal time (Lunch or Dinner) using bill,
tip, party-size, and encoded categorical features.

🎯 Objectives:

- Load and inspect datasets using Pandas and Seaborn.
- Check dataset dimensions, data types, and missing values.
- Separate independent features (X) and target (y).
- Split data into training and testing sets.
- Train Decision Tree and Random Forest classifiers.
- Evaluate models using accuracy, classification reports, and
  confusion matrices.
- Compare all four model/dataset combinations.

🧰 Tools & Technologies:

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

🤖 Machine Learning Models:

1. Decision Tree Classifier:
   A tree-based model that makes predictions by learning feature-based
decision rules.

2. Random Forest Classifier:
   An ensemble model that combines predictions from multiple decision
trees. In this notebook, the Random Forest uses 100 estimators.

🔬 Workflow:

1. Import required libraries.
2. Load the Iris and Tips datasets from Seaborn.
3. Explore dataset shape, data types, and missing values.
4. Prepare features and target variables.
5. Encode categorical features in the Tips dataset.
6. Split each dataset into 80% training and 20% testing data,
   using random_state=42 and stratification.
7. Train both classifiers.
8. Generate predictions.
9. Evaluate using:
   - Accuracy Score
   - Classification Report (precision, recall, F1-score)
   - Confusion Matrix
10. Compare the four model results.

📊 Evaluation:

The notebook calculates and prints the accuracy of each model: -
Decision Tree --- Iris - Random Forest --- Iris - Decision Tree ---
Tips - Random Forest --- Tips

Note: The actual accuracy values depend on the notebook execution.
Run all cells to see the results; no fixed score is claimed here.

🚀 How to Run:

1. Clone or download this repository.
2. Open the notebook ML_Practice-3 (DT & RF).ipynb in Jupyter
   Notebook, JupyterLab, or Google Colab.
3. Install the required libraries:
    -> pip install pandas numpy seaborn matplotlib scikit-learn jupyter
4. Run the notebook cells from top to bottom.
The datasets are loaded using Seaborn's load_dataset() function, so an
internet connection may be required the first time the datasets are
fetched.

📁 Repository Structure:

├── ML_Practice-3 (DT & RF).ipynb
└── README.md

💡 Key Learnings:

- Understanding the difference between a single Decision Tree and an
  ensemble Random Forest.
- Preparing numerical and categorical data for classification.
- Using stratified train-test splitting.
- Interpreting classification metrics and confusion matrices.
- Comparing model performance across different datasets.

👨‍💻 Author
Krishna Sahoo

Machine Learning Practice Project 03

Learning • Building • Growing

If you find this project useful, feel free to ⭐ the repository and
share feedback!
