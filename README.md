# antibiotic-resistance-prediction
S or R? Unveiling E. Coli’s Cefepime Resistance Patterns

Antibiotic resistance is a critical global health challenge, and effective predictive models can aid in understanding and combating it.

In this project I built predictive models for Cefepime Susceptibility (S) vs. Resistance (R) in Escherichia coli.

## Models Used

This project explores and compares the performance of three different machine learning models:

*   **Random Forest:** A versatile ensemble learning method that constructs a multitude of decision trees at training time and outputs the class that is the mode of the classes (classification) of the individual trees.  Random Forests are known for their robustness and ability to handle high-dimensional data.
*   **Gradient Boosting:**  Another ensemble method that builds trees sequentially, with each tree correcting the errors of its predecessors.  Gradient Boosting algorithms like XGBoost and LightGBM are often highly accurate.
*   **LightGBM (Light Gradient Boosting Machine):** A gradient boosting framework that uses tree-based learning algorithms. LightGBM is known for its speed and efficiency, particularly with large datasets, and often achieves state-of-the-art results.



