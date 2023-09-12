# Zillow-Project

<img width="470" alt="Screenshot 2023-09-08 at 4 12 57 PM" src="https://github.com/NISHAKUNWAR053/Zillow-Project/assets/136507682/7f416aa5-03c1-4602-9ad5-f1baaa0eca08">


# Project Description

This attempt seeks to predict housing prices using Zillow's dataset. The ultimate objective is to craft a robust machine learning model that enterprises can deploy for accurate house price predictions.

# Project Goals 🥅
- The project aims to create a machine learning model to predict the value of single-family homes accurately, using key property details.
- Another goal is to find out what major factors affect the tax values of single-family homes sold in 2017.
- Finally, the results will be shared with Zillow's lead data scientist and other important team members.

# Initial Questions ⁉️
1. Why do some properties have a much higher value than others when they are located so close to each other?
2. Why are some properties valued so differently from others when they have nearly the same physical attributes but only differ in location?
3. Is having 1 bathroom worse for property value than having 2 bedrooms?

# Data Dictionary 👩‍💻
| Variable    | Data Type |  Description    | Unit|
| --------  | -------  |  ------- |-------|
| Bedroom | Integer | Number of bedroom in home| Count|
| Bathroom| Float | Number of bathrrom in home including fractional bathroom| Count|
|Square Feet| Float number| The total square footage of the property| Square feet|
| Lotsize| Integer| The size of the land on which the property is built| Square feet|
| Age| Integer| The age of the property calculate from the year it was built to the current year| Years|
| Assesses Value| Float| The value of the property as assessed for tax purposes| Currency(USD)
| TaxAmount| Float| the total annual property tax amount| currency(USD)
| County| String| the county where the property is located| Text| Text|
| Latitude| Float| Indicating north-south position on earth's surface| Degrees(Decimal)|
| Longitude| Float| Indicating east-west position on earth's surface| Degrees(Decimal)|



# Project Plan
Data Acquisition
- Gather data from mySQL database

Data Preparation
- Data cleaning
- Data splitting

Exploratory Analysis
- Pose inquiries to identify the pivotal attributes linked to the property's assessed valuation.
- Investigate the correlation between each feature and the assessed property value.
- Employ visual aids to gain a nuanced understanding of the relationships between various attributes.


Modeling Evaluation

- Train and evaluate various model like Linear Regression, Selection Operato(LASSO), Least Angle Regression (LARS), Ordinary Least Squares (OLS) utilizing Random seed value of 123 and alpha = 0.5.
- Train the models using the available data.
- Validate the models to assess their performance.
- Select the most effective model fro further testing.

Product Delivery

- Prepare the final notebook that integrates the best models, visuals and applicable data to present comprehensive insights.

Steps to reproduce

- Read this README.md documents to familiarize yourself with the project details and key findings.
- You have to have access to data I used MYSQL server but data are also availabele in Kaggle (data science and AI platform)
- Confirm .gitignore to hide your important file that you wish not to get public.
- Libraries used are pandas, matplotlib, seaborn, plotly, sklearn, scipy.
- Ensure that all necessary libraries or dependent programs are installed. You may need to install additional package it they are not already presnt in your environment.
- Run the final_report.ipynb notebook to execute te project code and generate the results.

Key Findings, Recommendations and Takeaways:

- 
