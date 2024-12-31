# Netflix Data Cleaning Project

Welcome to the **Netflix Data Cleaning Project**! This repository contains a Jupyter Notebook that prepares a raw Netflix dataset for further analysis by cleaning and formatting the data.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Data Cleaning Steps](#data-cleaning-steps)
6. [Contributing](#contributing)
7. [License](#license)

## Project Overview

This project focuses on:

- Cleaning raw Netflix data to remove inconsistencies and prepare it for analysis.
- Addressing issues like missing values, duplicates, and irrelevant columns.
- Renaming columns for clarity and consistency.
- Checking for additional transformations to optimize the dataset.
- Exporting the cleaned dataset for use in other projects or further analysis.

## Dataset

The dataset used in this project is sourced from Kaggle:
[Netflix Data Cleaning, Analysis, and Visualization](https://www.kaggle.com/datasets/ariyoomotade/netflix-data-cleaning-analysis-and-visualization)

## Installation

To use this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/mahfuzur-mafu/netflix-data-cleaning.git
   cd netflix-data-cleaning
   ```
2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook netflix_data_clean.ipynb
   ```
2. Follow the steps in the notebook to clean the dataset and export the cleaned data.

## Data Cleaning Steps

The notebook performs the following steps:

1. **Removing Unnecessary Columns:**
   - Drops irrelevant columns like `rating` to focus on meaningful data.

2. **Renaming Columns:**
   - Renames columns to ensure consistency and clarity.

3. **Handling Duplicates:**
   - Identifies and removes duplicate rows while keeping the first occurrence.

4. **Managing Missing Values:**
   - Drops rows with null values to ensure data consistency.

5. **Checking for Transformations:**
   - Evaluates and applies additional transformations to enhance data quality.

6. **Exporting Cleaned Data:**
   - Saves the cleaned dataset as a CSV file named `netflix_clean_data.csv` for future use.
