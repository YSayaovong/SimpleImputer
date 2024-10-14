# Imputing Missing Values using SimpleImputer

## Project Overview

This project demonstrates how to handle missing values in a dataset using the `SimpleImputer` class from scikit-learn. Specifically, it focuses on imputing missing values in the 'sex' column, a categorical feature, by replacing missing values with the most frequent (mode) value.

The code removes rows with more than one missing value and imputes the 'sex' column with the most frequent value, ensuring the dataset is clean for further analysis or machine learning tasks.

## Technologies Used
- Python 3.x
- pandas
- scikit-learn (SimpleImputer)

## Getting Started

### Prerequisites

To run this code, you need to have Python installed along with the following libraries:

```bash
pip install pandas scikit-learn
