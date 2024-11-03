# cloud_hosted_nb_data_manipulation
[![CI](https://github.com/aoaow/cloud_hosted_nb_data_manipulation/actions/workflows/main.yml/badge.svg)](https://github.com/aoaow/cloud_hosted_nb_data_manipulation/actions/workflows/main.yml)

## Overview
This project is a cloud notebook on Google Colab platform that demonstrates basic data manipulation on the breast cancer data provided by `scikit-learn`. The notebook contains data wrangling and visualizations, with writing the data into pandas dataframes and investigate the target distribution as well as correlations between predictors.

## Features
- Connect to Google Colab
- Investigate on breast cancer dataset
- Perform EDA on the target variable and predictors

## Installation
1. Clone the repository:
   ```bash
   git clone <https://github.com/aoaow/cloud_hosted_nb_data_manipulation>
   ```
2. Navigate to the project directory:
   ```bash
   cd cloud_hosted_nb_data_manipulation
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## CI/CD Implementation
This project also includes a simple CI/CD action to ensure the smooth adaptation, in checking the python version, installing dependencies, and pytesting the notebook.

