🌸 Iris Flower Classification - ML Journey with KNN & Decision Tree
My first Machine Learning project where I explore the Iris flower dataset using two classic classification algorithms:
- Decision Tree and
- K-Nearest Neighbors (KNN)
- I’ve documented every improvement step-by-step, from basic output to clean, readable, and human-friendly results.

📁 Repository Structure
| File                                 | Description                                                            |
| ------------------------------------ | ---------------------------------------------------------------------- |
| 1_iris_decision_tree.ipynb           | First attempt using "DecisionTreeClassifier"                           |
| 2_iris_knn_classifier.ipynb          | Switched to "KNeighborsClassifier" (KNN)                               |
| 3_knn_output_flower_names.ipynb      | Improved KNN by converting predicted numbers to actual flower names    |
| 4_knn_clean_output.ipynb             | Removed "np.str_()" for cleaner text output                            |
| 5_knn_comparison_with_pandas.ipynb   | Final version showing results in a table using "pandas" for comparison |
| iris_predictions.csv                 | Output of actual vs predicted flower types                             |
| README.md                            | Project overview & evolution                                           |

🧠 What is the Iris Dataset?
It’s a classic dataset used in ML containing:
- 150 rows of flower data
- 3 classes of flowers: setosa, versicolor, virginica
- 4 features: sepal length/width, petal length/width

💡 Project Evolution (and Learning)
| Version | Whats New                                      | Why It Matters                             |
| v1      | ✅ Used DecisionTreeClassifier                | Got first working model with high accuracy |
| v2      | 🔄 Switched to KNN                            | Explored another popular algorithm         |
| v3      | 📝 Converted output numbers to flower names   | Made results human-readable                |
| v4      | 🧹 Removed np.str_()                          | Cleaned the output formatting              |
| v5      | 📊 Used pandas to show a side-by-side table   | Professional & presentation-ready          |

| Version | What's New                                    | Why It Matters                             |
| ------- | --------------------------------------------- | ------------------------------------------ |
| `v1`    | ✅ Used `DecisionTreeClassifier`               | Got first working model with high accuracy |
| `v2`    | 🔄 Switched to `KNN`                          | Explored another popular algorithm         |
| `v3`    | 📝 Converted output numbers to flower names   | Made results human-readable                |
| `v4`    | 🧹 Removed `np.str_()` artifacts              | Cleaned the output formatting              |
| `v5`    | 📊 Used `pandas` to show a side-by-side table | Professional & presentation-ready          |



📊 Model Performance
-Accuracy: 100% on test set
-Visualization: Side-by-side scatter plots for actual vs predicted flower types
-Table view: Added using "pandas" for clearer comparison

🔧 How to Run
- Clone this repo or download ZIP
- Install the required libraries:
"pip install scikit-learn pandas matplotlib"
- Open any notebook in Jupyter:
jupyter notebook
- Explore different versions to see how the project evolves


⚙️ Tech Stack
- Python
- scikit-learn
- Jupyter Notebook

📊 Algorithms Tried
- Decision Tree Classifier ✅
- K-Nearest Neighbors Classifier ✅

🔍 Results
Achieved up to **100% accuracy** on test data 🎯

📝 How to Run
1. Clone this repo
2. Open the `.ipynb` notebook in Jupyter
3. Run the cells one by one
