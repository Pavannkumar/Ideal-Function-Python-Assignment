# Ideal Function Selection and Test Data Mapping (Python)

This project implements a Python-based analytical system to identify ideal mathematical functions that best approximate given training datasets and map independent test observations to the selected ideal functions.

The system uses the **least squares method** to determine optimal functions and applies a deviation threshold rule to map test observations.

---

## Project Features

- Ideal function selection using Least Squares
- Test data mapping using deviation threshold
- SQLite database integration
- Interactive visualization using Bokeh
- Object-Oriented Python implementation
- Unit testing using Python unittest
- Version control using Git

---

## Project Structure
Ideal-Function-Python-Assignment
│
├── src/
│ ├── main.py
│ ├── exceptions.py
│ └── tests.py

├── data/
│ ├── train.csv
│ ├── ideal.csv
│ └── test.csv

├── results/
│ ├── functions.db
│ └── function_mapping.html

├── report/
│ └── Python_Assignment_Report.pdf

├── README.md
├── requirements.txt
└── .gitignore

---

## Technologies Used

- Python
- Pandas
- NumPy
- SQLAlchemy
- SQLite
- Bokeh

---

## Algorithm Overview

1. Load training, ideal, and test datasets.
2. Store datasets in a SQLite database.
3. Compare training functions with candidate ideal functions using least squares.
4. Select ideal functions with minimum deviation.
5. Calculate maximum deviation threshold.
6. Evaluate test observations against the selected ideal functions.
7. Store valid mappings in the database.
8. Generate visualization of results.

---

## Visualization

The system generates an interactive visualization showing:

- Training functions
- Selected ideal functions
- Mapped test observations


