# Product-Orders-Analysis-and-Demand-Forecasting

## Project Objective
Demand forecasting plays a vital role in supply chain management, enabling businesses to optimize procurement, inventory, and production while identifying market trends and planning for future operations. This project focuses on analyzing order quantities for various products, uncovering trends and relationships with influencing factors, and developing a predictive model to accurately forecast future demand. By doing so, it aims to enhance organizational efficiency and support more effective future planning.

## Project Overview
This project focuses on analyzing product order data and forecasting demand.

Part 1 involves visualization and analysis of the order_train1.csv file, addressing:
1. Impact of Product Prices on Demand: Analyzing how various pricing strategies affect product demand.
2. Regional Influence on Product Demand: Exploring how the sales region impacts demand and identifying characteristics across different regions.
3. Demand Characteristics by Sales Method: Comparing product demand between online and offline sales channels.
4. Demand Differences Among Product Categories: Identifying similarities and differences in demand across various product categories.
5. Temporal Demand Patterns: Examining how product demand fluctuates during different periods of the month (e.g., beginning, middle, end).
6. Impact of Holidays on Product Demand: Assessing how holidays influence product demand.

Part 2 entails developing a predictive model to forecast product demand using the predict_sku1.csv file. A Gradient Boosting model has been rigorously developed to predict product demand, utilizing daily, weekly, and monthly time granularities.

Note: Due to GitHub's file size limitations, order_train1.csv has been split into two parts for uploading.

## Requirements

To run these notebooks, you will need:

Python 3.8 or later
Jupyter Notebook
Libraries: pandas, numpy, matplotlib, seaborn, and scikit-learn.

## Running Instructions

1. Clone the repository to your local environment.
2. Download the required dataset files and place them in your local directory.
3. Open the notebooks in Jupyter Notebook or JupyterLab.
4. Update the file paths in the scripts to point to the location of the downloaded datasets.
5. Install the required libraries using pip install -r requirements.txt (if provided).
6. Follow the instructions within each notebook to run the analyses and models.

## Data Analysis and Modeling Notebook
For a detailed understanding of the data preprocessing and the predictive model, check out the Jupyter notebook named 

## Data sources

The data used for this project is from BdRace, which can be found [here]([https://agriculture.canada.ca/en/market-information-system/rp/index%2Deng.cfm?action=ePR&R=243&PDCTC=#clfinput_err](https://www.tipdm.org:10010/#/competition/1620719578957127680/introduce)). 

## Contributors
- Aaron Liu
