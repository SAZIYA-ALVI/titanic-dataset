# Titanic Dataset - Data Cleaning & Preprocessing

## Project Overview

This project focuses on cleaning and preprocessing the Titanic dataset to prepare it for data analysis and machine learning.

The goal is to handle missing values, remove duplicates, convert data types, and create a clean dataset suitable for further analysis.

## Dataset

The dataset contains information about passengers aboard the Titanic, including:

* PassengerId
* Survived
* Pclass
* Name
* Sex
* Age
* SibSp
* Parch
* Ticket
* Fare
* Cabin
* Embarked

## Objectives

* Understand the dataset structure
* Identify missing values
* Handle null values
* Remove duplicate records
* Convert categorical data into numerical format
* Prepare the dataset for analysis

## Data Cleaning Steps

### 1. Load Dataset

Loaded the Titanic dataset using Pandas.

### 2. Check Missing Values

Used:

python
df.isnull().sum()

to identify missing values in each column.

### 3. Handle Missing Values

* Filled missing values in the Age column using the median value.
* Filled missing values in the Embarked column using the mode value.
* Removed the Cabin column due to a large number of missing values.

### 4. Remove Duplicates

Used:

python
df.drop_duplicates(inplace=True)

to remove duplicate rows.

### 5. Data Type Verification

Checked data types using:

python
df.info()


### 6. Save Cleaned Dataset

Saved the cleaned dataset as:

python
clean_titanic.csv


## Tools and Libraries

* Python
* Pandas
* NumPy
* Jupyter Notebook

## Results

* Missing values handled successfully.
* Duplicate records removed.
* Dataset cleaned and prepared for further analysis.

