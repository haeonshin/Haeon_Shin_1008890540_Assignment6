# CME538 Assignment 6 — Linear Regression

This repository contains the completed Assignment 6 Jupyter Notebook and its HTML export.

## Files

- `assignment6_completed.ipynb` — completed notebook, with all code cells executed and outputs saved
- `assignment6_completed.html` — static HTML export of the completed notebook
- `ames_data.csv` — dataset used by the notebook
- `ames_data_cleaned.csv` — additional dataset included in the original assignment package
- `codebook.txt` and `documentation.txt` — original dataset references
- `images/` — original assignment asset folder

## Run the notebook

Keep `ames_data.csv` in the same directory as the notebook. Open `assignment6_completed.ipynb` in Jupyter, then select **Kernel > Restart Kernel and Run All Cells**. The notebook was tested successfully end-to-end with Python 3, pandas, numpy, matplotlib, seaborn, and scikit-learn.

The notebook uses `train_test_split(..., random_state=0)` and shuffled 5-fold cross-validation with `random_state=0`. The held-out test data is evaluated only after choosing the final model.

## Submitting

Rename **both** the `.ipynb` and `.html` files to match the required naming convention:

`firstname_lastname_studentnumber_assignment6.ipynb`

`firstname_lastname_studentnumber_assignment6.html`

Submit these two renamed files and the link to your GitHub assignment repository in Quercus. Push the identical notebook and HTML files to your GitHub repository, along with `ames_data.csv` so that the notebook can run.
