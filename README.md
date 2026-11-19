# Supervised Machine Learning: Regression and Classification

Practice notebooks from **Course 1** of Andrew Ng's
[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction)
(DeepLearning.AI and Stanford Online on Coursera).

Each notebook builds a core algorithm **from scratch with NumPy** (no ML libraries)
and then compares it with scikit-learn where that helps.

## Contents

| # | Notebook | Topics |
|---|----------|--------|
| 01 | [Cost Function](01_cost_function.ipynb) | Squared-error cost for univariate linear regression, cost surface |
| 02 | [Gradient Descent for Linear Regression](02_gradient_descent_linear_regression.ipynb) | Computing gradients, the update loop, learning-rate divergence |
| 03 | [Multiple Variable Linear Regression](03_multiple_variable_linear_regression.ipynb) | Vectorization with NumPy, multi-feature gradient descent |
| 04 | [Feature Scaling and Learning Rate](04_feature_scaling_and_learning_rate.ipynb) | Z-score normalization, choosing alpha, convergence |
| 05 | [Gradient Descent for Logistic Regression](05_gradient_descent_logistic_regression.ipynb) | Sigmoid, log loss, decision boundary |
| 06 | [Logistic Regression with scikit-learn](06_logistic_regression_scikit_learn.ipynb) | `LogisticRegression`, fitting and scoring |
| 07 | [Regularized Cost and Gradient](07_regularized_cost_and_gradient.ipynb) | L2 regularization for linear and logistic regression, overfitting |

## Running locally

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate    macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

Some notebooks use `%matplotlib widget` for interactive plots, which needs `ipympl`
(already in `requirements.txt`).

## Repository layout

```
├── 01_...ipynb – 07_...ipynb   # my lab notebooks
├── lab_utils_*.py, plt_*.py     # plotting/helper code provided by the course
├── deeplearning.mplstyle        # course matplotlib style
└── data/houses.txt              # housing dataset used in notebook 04
```

## Academic integrity

This repo has only the ungraded practice labs. I've left out my solutions to the
graded programming assignments, in line with the
[Coursera Honor Code](https://www.coursera.org/about/terms/honorcode).

## License

My own code and notes are released under the [MIT License](LICENSE).
The helper files and dataset listed in `LICENSE` come from DeepLearning.AI /
Stanford Online and remain their property.
