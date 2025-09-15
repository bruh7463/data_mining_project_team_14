# Data Mining Project

This repository contains a data mining project following the **CRISP-DM** (Cross-Industry Standard Process for Data Mining) methodology.

## **1. Business Understanding**

### Problem Statement

Wikipedia pages related to Zambia have fewer local contributions than international ones. There is little understanding of where the contributors of Zambian-related pages come from, including the Zambia page. Without this information, it is difficult to create specific strategies that boost contributions from Zambian Wikipedians. The goal is to find out and categorize the origins of Wikipedia users who contribute to Zambian pages. This will help in planning actions that promote more local involvement.

### Business Objectives

- Provide practical advice to guide strategies for Zambian-based contributions.
- Identify the percentage of contributions to Zambian Wikipedia articles by users from Zambia compared to other nations.
- Enable long-term monitoring of contribution by country of origin.
- Support The University of Zambia's DataLab Research Group in advocating for greater representation of local perspectives on Wikipedia.

### What Success Looks Like In Practice

- An unambiguous evidence based report on the contributions by country.
- It was possible to identify trends of where most of edits are made.
- Lessons that could be shared with Wikimedia communities and policymakers incase of encouraging locals to contribute.


### Data Mining Goals
- Create a prediction model that can determine the most likely country of origin for each Wikipedia edit made to Zambian pages, using details like the user’s IP address (for anonymous edits), profile information, and the timing of edits.

- Analyze and visualize the data to show clear summaries of how contributions are distributed by country .



### Initial Project Success Criteria

- Produce a clear and accurate breakdown of Wikipedia contributions to Zambian pages by country of origin.
- Achieve at least 80% accuracy in classifying the country of origin for contributions.
- Visualize contribution patterns and trends over time through interpretable dashboards or charts.
- Provide actionable insights that can guide strategies to increase local Zambian participation.

## **2. Data Understanding**

In this section, the dataset is mounted from Google Drive and loaded into a Pandas DataFrame. The structure of the data is explored through inspection of column names, data types, and sample rows. Summary statistics are generated to understand the distribution of numerical variables, and visualizations are used to detect outliers, trends, and potential data quality issues such as missing values or duplicates.


## **3. Data Preparation**

This phase involves cleaning and transforming the raw data to prepare it for modeling. Missing values are handled, irrelevant columns are dropped, and categorical features are encoded into numerical form. The data is also scaled or normalized where necessary. Finally, the dataset is split into training and test sets to enable model evaluation on unseen data.


## **4. Modeling**

Several machine learning models are built and trained on the prepared dataset. Different algorithms are implemented and tuned to find the best-performing model. Hyperparameters are adjusted using cross-validation techniques, and model training results are compared to identify which approach yields the most accurate predictions.


## **5. Evaluation**

The trained models are assessed on the test dataset to measure their performance. Metrics such as accuracy, precision, recall, F1-score, or error-based scores (depending on the task) are computed. Visual evaluation tools like confusion matrices or performance plots are used to analyze the strengths and weaknesses of each model, ensuring robust results before deployment.


## **6. Deployment**

The best-performing model is finalized and saved for future use. Basic prediction scripts are provided to demonstrate how new, unseen data can be processed and fed into the model to generate outputs. This section also discusses how the model could be integrated into a production environment and notes potential areas for future improvement.

