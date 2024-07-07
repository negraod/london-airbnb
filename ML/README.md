# london-airbnb - Machine Learning
Data Science personal project, using Kaggle's dataset: London Sep2022 Airbnb.

This is the Machine Learning part of this project.

<br><br>
* **ML01_Baseline.ipynb**  
  Establishing a framework for model evaluation and baseline reference, including the creation of tools:
    * A versatile feature engineering transformer enabling testing of various configurations within scikit-learn's pipeline.
    * Automatic column type detection, facilitating integration with the feature engineering transformer by accommodating dynamically created columns.

* **ML02_Tree Models.ipynb**  
  Evaluation of Tree-Based models using Optuna for hyperparameter optimization, including:
    * Implementation of RepeatPruner to prevent redundant tests of parameter combinations.
    * Analysis of Feature Importances.
