# Pre-Doctoral Data Analysis Task - UIUC

This repository contains the coding task for a pre-doctoral research position at the University of Illinois Urbana-Champaign. It focuses on simulating and analyzing data to understand the impact of Facebook ad campaigns on COVID-19 vaccine uptake.

## Project Overview

The project involves a hypothetical field experiment where 5,000 participants across the US are exposed to two different types of Facebook ads - one appealing to reason and the other to emotions. The experiment aims to evaluate which strategy is more effective in increasing COVID-19 vaccine uptake.

## Repository Structure

- `Stimulation.ipynb`: Script for simulating the survey and assignment data.
- `Output.py`: Script for analyzing the simulated data, including logistic regression.
- `baseline_survey_data.csv` : Baseline Survey
- `random_assignment_data.csv`: Treatment Assignment
- `baseline_survey_data.csv`: Endline Survey
## Data Simulation

The simulation process involves:
- Generating baseline survey data with demographics and vaccine attitudes.
- Randomly assigning participants to one of three groups (reason ad, emotion ad, or control).
- Simulating endline survey data post-exposure to the ads.

## Installation and Usage

# Libraries Used in the Project

## 1. Faker
- **Purpose**: Generates fake data such as names, addresses, numbers, etc. 
- **Common Uses**: Testing, database population for simulation purposes.

## 2. Pandas
- **Purpose**: Provides data manipulation and analysis capabilities.
- **Features**: Data structures like DataFrames and Series, functions for data importing, cleaning, manipulation, and aggregation.

## 3. NumPy
- **Purpose**: Fundamental package for numerical computation in Python.
- **Features**: Support for large, multi-dimensional arrays and matrices, and a collection of mathematical functions.

## 4. Statsmodels
- **Purpose**: Used for statistical modeling and hypothesis testing.
- **Application**: Likely used for logistic regression analysis in the project.

## 5. Random
- **Purpose**: Implements pseudo-random number generators for various distributions.
- **Usage**: Generating random data or for random sampling processes.


## bash
git clone https://github.com/yujie-xue/Coding-task_pre-doc_UIUC/
cd Coding-task_pre-doc_UIUC
pip install -r requirements.txt

## Analysis Approach
Use logistic regression to assess the effectiveness of each ad campaign strategy.
Conduct subgroup and sensitivity analyses for more in-depth insights.
Interpret the results in the context of public health messaging and campaign strategies.
## Results
The analysis aims to reveal:
The overall effectiveness of the ad campaigns.
Differences in vaccine uptake based on demographics and ad strategy.
Insights into optimizing public health campaigns for vaccine promotion.
Contributing
Contributions to improve the simulation and analysis are welcome. Please follow the standard procedure for pull requests.

## License
This project is open-source and available under the MIT License.

## Contact
For any queries, suggestions, or contributions, please contact Yujie Xue.

## Acknowledgments
