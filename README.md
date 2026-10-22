# Decision Trees, LASSO, and Boosting for Regression

Homework 5 for DSCI-552. Covers interpretable decision tree models on the Acute Inflammations dataset, and LASSO / gradient boosting regression on the Communities and Crime dataset.

## Structure

- `data/`: Acute Inflammations and Communities and Crime data files.
- `notebook/`: Completed Jupyter notebook.
- `requirements.txt`: Python packages used by the notebook.

Run the notebook from the `notebook/` directory so the relative paths resolve to `../data`.

The notebook ends with an extra section, "Extra: verifying the fits with CVXPY and SciPy": it re-solves the scikit-learn LASSO and ridge fits as convex programs with CVXPY and compares coefficients and test MSE.
It also runs a paired Wilcoxon / t-test of per-fold MSE for XGBoost vs ridge using SciPy. Written with Claude Code assistance.

## Author

Sujendra Giri Prasad Bharadwaj
