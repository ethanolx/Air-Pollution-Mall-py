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

An alternative is to use pip to install the required dependencies from `requirements.txt`

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
     |-- out ---- kaggle_submission.csv
     |
     |-- .gitignore
     |-- ai.ipynb
     |-- Pipfile
     |-- Pipfile.lock
     `-- README.md
```

##