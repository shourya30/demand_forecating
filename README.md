# Demand Forecasting

![Demand Forecasting](Demand_picture.webp)

This project focuses on time series forecasting using LightGBM, aiming to predict sales for 50 products across 10 stores over a three-month period. The dataset spans five years (2013-01-01 to 2017-12-31).

To enhance forecasting accuracy, various time series techniques were applied, including:

Time series decomposition (analyzing trend, seasonality, cyclical, and residual components).
Feature engineering (creating date-based features, lagged values, rolling window metrics, and exponentially weighted features).
Chronological train-test split and time series cross-validation (rolling/expanding windows).
Key Business Insights & Financial Results:
The forecasted total sales for the next three months amount to 2,558,788.02 items.
Top-performing stores: 2, 3, and 8.
Lower-performing stores: 5, 6, and 7.
Best-selling products: Items 15 and 28.
Least-sold product: Item 5.
These insights align with historical sales patterns, reinforcing the importance of seasonality, trends, and residual components in forecasting.

This project adheres to a real-world data science workflow, following the CRISP-DM framework from data collection and exploratory analysis to modeling. It also includes best practices such as exception handling, modular code structure, version control (Git/GitHub), virtual environments, and dependency management, ensuring reproducibility.

2. Technologies & Tools

The following tools and technologies were utilized:

Programming & Libraries: Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, Statsmodels, Optuna).
Development & Version Control: Jupyter Notebook, Git, and GitHub.
Machine Learning & Statistical Methods: Regression models and time series analysis.
Project Environment: Anaconda (terminal & virtual environments) and Visual Studio Code.
3. Project Structure

The project is organized into structured directories and files for clarity and maintainability:

input/ – Contains raw dataset files.
models/ – Stores trained models in .pkl format.
notebooks/ – Includes Jupyter notebooks for EDA and modeling.
reports/ – Stores project-related images and visualizations.
src/ – Houses Python scripts for core functionalities:
artifacts_utils.py – Handles data artifacts.
modelling_utils.py – Manages model development.
exception.py – Implements error handling.
Other essential files:
setup.py – Defines the project as a package with metadata.
requirements.txt – Lists dependencies for reproducibility.
.gitignore – Excludes irrelevant files from version control.
README.md – Provides documentation and project insights.
4. Business Problem & Objectives

A retail manager is tasked with optimizing inventory and investment decisions across 10 stores and 50 products. The goal is to leverage predictive analytics to:

Extract meaningful insights about sales trends and seasonal variations.
Develop an accurate forecasting model to predict sales over a three-month period.
Provide financial projections to aid decision-making.
These predictions will empower the manager to improve inventory planning, enhance customer satisfaction, and drive business growth.

5. Solution Pipeline

The project follows the CRISP-DM framework, structured into six key phases:

Business Understanding – Defining the problem and goals.
Data Understanding – Analyzing raw sales data.
Data Preparation – Cleaning and transforming data for modeling.
Modeling – Training and fine-tuning machine learning models.
Evaluation – Measuring model performance and accuracy.
Deployment – Presenting results for business use.
Each phase is detailed in the corresponding Jupyter notebooks for a comprehensive understanding.
