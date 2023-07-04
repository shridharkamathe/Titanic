# Titanic
# Titanic Passengers Dataset Analysis
![df0gjg6-4b1b7525-9a79-43c3-b27e-58371db4fb94](https://github.com/shridharkamathe/Titanic/assets/124047047/0063beb0-d567-4fbf-af19-d4bda8502d31)

This repository contains an analysis of the Titanic passengers dataset, focusing on the correlation between various parameters such as passenger class, gender, and age for survival rate. Additionally, a Power BI dashboard has been created to visualize the findings.

## Dataset

The dataset used for this analysis is the famous Titanic dataset, which includes information about passengers aboard the RMS Titanic. It provides details such as passenger class, gender, age, and survival status. The dataset is available in CSV format and can be found [here](https://www.kaggle.com/c/titanic/data).

## Dataset Description

Overview

The data has been split into two groups:

training set (train.csv)
test set (test.csv)
The training set should be used to build your machine learning models. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. Your model will be based on “features” like passengers’ gender and class. You can also use feature engineering to create new features.

The test set should be used to see how well your model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.

We also include gender_submission.csv, a set of predictions that assume all and only female passengers survive, as an example of what a submission file should look like.

<img width="788" alt="Screenshot 2023-07-04 at 11 43 50 AM" src="https://github.com/shridharkamathe/Titanic/assets/124047047/faa4c598-2283-47b4-a3cb-106b23d0913c">

Variable Notes

pclass: A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower

age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

sibsp: The dataset defines family relations in this way...
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)

parch: The dataset defines family relations in this way...
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.

## Analysis

The analysis aims to uncover insights into the factors that influenced survival rates among Titanic passengers. The following correlations are examined:

1. **Passenger Class:** The correlation between passenger class (First, Second, Third) and survival rate is explored. This will help determine if there was a significant difference in survival rates based on class.

2. **Gender:** The correlation between gender (male, female) and survival rate is examined. This analysis will shed light on whether gender played a role in the chances of survival.

3. **Age:** The correlation between age and survival rate is analyzed. This investigation will reveal if age had any impact on the likelihood of survival.

## Power BI Dashboard

A Power BI dashboard has been created to visualize the findings of the analysis. Power BI is a business analytics tool that provides interactive visualizations and business intelligence capabilities. The dashboard offers an intuitive interface to explore and understand the correlations between different parameters and survival rates among Titanic passengers.

The Power BI dashboard includes various charts and graphs that present the data in a comprehensive manner. Users can interact with the dashboard to filter and drill down into specific segments of the dataset, enabling a deeper understanding of the correlations.

## Repository Structure

The repository is organized as follows:

- **data**: This directory contains the Titanic passengers dataset in CSV format.

- **notebooks**: This directory contains Jupyter notebooks used for data preprocessing, analysis, and visualization. The notebooks are numbered in the order they should be executed.

- **powerbi**: This directory includes the Power BI file (.pbix) containing the dashboard visualization.

- **README.md**: This file provides an overview of the repository and its contents.

## Usage

To reproduce the analysis and explore the Power BI dashboard, follow these steps:

1. Clone or download this repository to your local machine.

2. Open the Power BI file in the `powerbi` directory using Power BI Desktop or upload it to the Power BI service for online access.

3. Interact with the Power BI dashboard to explore the correlations between passenger class, gender, age, and survival rate.

## Contributing

Contributions to this repository are welcome. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## Acknowledgments

The Titanic dataset used in this analysis is provided by Kaggle. We acknowledge the original data source and thank the Kaggle community for their contributions.

Please refer to the Kaggle Titanic competition page for more information about the dataset and any usage restrictions.
