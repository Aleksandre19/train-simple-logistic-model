# Train Simple Logistic Model

This project demonstrates the implementation of a simple logistic regression model for predicting school admissions based on test scores. The model amies to demonstrate the minimal crusial steps involved in training a machine learning model, including data preprocessing, model architecture, and model evaluation.

## Dataset
The dataset used in this project is sourced from [UCLA Academic Technology Services](http://www.ats.ucla.edu/stat/data/binary.csv). It contains student admission records with the following features:
- `admit`: Binary variable indicating admission decision (0 = rejected, 1 = admitted)
- `gre`: Graduate Record Exam scores (ranges from 200 to 800)
- `gpa`: Grade Point Average (ranges from 0 to 4.0)
- `rank`: Undergraduate institution rank (1 = highest prestige, 4 = lowest prestige)

The dataset provides a realistic example for binary classification, where we aim to predict student admission based on their academic performance metrics.

## Installation
To run this project, you'll need:
1. Python 3.x
3. Jupyter Notebook
4. NumPy
5. Pandas

Install the required packages using:
```bash
pip install numpy pandas jupyter
```

## Usage
1. Clone this repository
2. Open the Jupyter notebook `simple_logistic_model.ipynb`
3. Run the cells sequentially to train and evaluate the model
