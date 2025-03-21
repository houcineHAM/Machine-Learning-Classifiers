# Machine Learning Classifiers

## 📝 Description  
This project includes three machine learning classifiers:  
- **Decision Tree**: A model based on decision rules in the form of a tree, classifying data by following logical branches.  
- **K-Nearest Neighbours (KNN)**: An algorithm that classifies a point based on the majority classes of its k nearest neighbors.  
- **Naive Bayes**: A probabilistic model based on Bayes' theorem, assuming independence between features.  

Each algorithm is implemented in a separate file, with a dataset to train and evaluate the models.  

---

## 📂 Project Content  
- **decision_tree_classifier.py**: Implementation of the Decision Tree classifier.  
- **k_nearest_neighbours_classifier.ipynb**: Implementation of the K-Nearest Neighbours classifier.  
- **naive_bayes_classifier.ipynb**: Implementation of the Naive Bayes classifier.  
- **car_evaluation.csv**: Dataset used for the Naive Bayes model.  

---

## ⚙️ Prerequisites  
- Python 3.x  
- Required Libraries:  
  - numpy  
  - pandas  
  - sklearn  
  - matplotlib (for visualization)  

To install the dependencies:  
```bash
pip install numpy pandas scikit-learn matplotlib
```

---

## 🚀 Usage  

1. **Decision Tree**  
   - Run the main script:  
     ```bash
     python decision_tree_classifier.py
     ```  
   - Analyze the displayed results:  
     - Visualization of the decision tree.  
     - Classification report and confusion matrix to evaluate performance.  

2. **K-Nearest Neighbours**  
   - Open the notebook:  
     ```bash
     jupyter notebook k_nearest_neighbours_classifier.ipynb
     ```  
   - Follow the steps:  
     - Load the data.  
     - Train the model with different values of k.  
     - Evaluate using the confusion matrix and error curve based on k.  

3. **Naive Bayes**  
   - Open the notebook:  
     ```bash
     jupyter notebook naive_bayes_classifier.ipynb
     ```  
   - Follow the steps:  
     - Load the **car_evaluation.csv** file.  
     - Preprocess the data.  
     - Train the Naive Bayes model.  
     - Visualize the results: accuracy score, confusion matrix, and error analysis.  

---

## 📊 Results  
Each model is evaluated using metrics like:  
- Accuracy.  
- Confusion matrix.  
- Classification report.  

The results allow for a comparison of the performance of the three algorithms on the same dataset.  

---

