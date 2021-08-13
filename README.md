# Predicting Air Pollution

|               |                       |
|---------------|-----------------------|
|   Author      |   Ethan Tan Wee En    |
|   Admin       |   p2012085            |
|   Class       |   DAAA/FT/2A/03       |
|   Language    |   Python (py)         |
|   Date        |   August 2021         |

## Setup

Pipenv is the package/dependency manager of choice

To create a virtual environment with all the required packages (in `.venv`):
1.  Install pipenv locally (using `pip install pipenv`)
2.  Create the virtual environment (using `pipenv install`)
3.  Activate the virtual environment (using `pipenv shell`)

To connect the Jupyter notebook (`ai.ipynb`) to use the above virtual environment,
1.  Change kernel
2.  Select the `.venv` environment

To produce the output,
1.  Select `Run all cells` in ai.ipynb

## File Structure

```
CA2 ---- .venv (empty directory)
     |
     |-- data ---- Kaggle_sample_submission.csv
     |         |-- Mall_Customers.csv
     |         |-- test.csv
     |         `-- train.csv
     |
     |-- doc ---- CA2_Brief.pdf
     |        |-- part-a.pptx
     |        `-- part-b.pptx
     |
     |-- models ---- best_models.p
     |           |-- evaluation-results.p
     |           |-- gs-expsmth-results.p
     |           |-- gs-sarima-results.p
     |           |-- gs-sarimax-1-results.p
     |           `-- gs-sarimax-2-results.p
     |
     |-- out ---- kaggle ---- dirty-1.csv
     |        |           `-- dirty-2.csv
     |        |
     |        |-- baseline.csv
     |        |-- clean.csv
     |        `-- customer-clustering-model.p
     |
     |-- .gitignore
     |-- ai.ipynb
     |-- Pipfile
     |-- Pipfile.lock
     `-- README.md
```

## See Also

*   Assignment Brief: `doc/CA2_Brief.pdf`
*   Part A highlights: `doc/part-a.pptx`
*   Part B highlights: `doc/part-b.pptx`