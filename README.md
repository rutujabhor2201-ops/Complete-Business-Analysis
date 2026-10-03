\# Complete Business Analysis: Customer Churn, Property Pricing \& Sales Performance



\## Project Overview



This project presents an end-to-end business analysis using customer, property, and sales datasets.



The project applies data cleaning, exploratory data analysis, statistical analysis, hypothesis testing, correlation analysis, and machine learning to identify business patterns and support data-driven decision-making.



The analysis is divided into three business modules:



1\. Customer Churn Analysis

2\. Property Price Analysis

3\. Sales Performance Analysis



\---



\## Business Objectives



The main objectives of the project are:



\* Identify factors associated with customer churn.

\* Develop a model to predict customer churn.

\* Analyze factors associated with property prices.

\* Develop a property price prediction model.

\* Evaluate product and regional sales performance.

\* Examine relationships between important sales variables.

\* Statistically validate regional sales differences.

\* Translate analytical findings into business recommendations.

\* Develop an implementation plan with measurable success metrics.



\---



\## Datasets



\### Customer Churn Dataset



\* Records: 500

\* Features: 9

\* Main variables:



&#x20; \* CustomerID

&#x20; \* Tenure

&#x20; \* MonthlyCharges

&#x20; \* TotalCharges

&#x20; \* Contract

&#x20; \* PaymentMethod

&#x20; \* PaperlessBilling

&#x20; \* SeniorCitizen

&#x20; \* Churn



\### Property Dataset



\* Records: 300

\* Features: 8

\* Main variables:



&#x20; \* Property\_ID

&#x20; \* Area

&#x20; \* Bedrooms

&#x20; \* Bathrooms

&#x20; \* Age

&#x20; \* Location

&#x20; \* Property\_Type

&#x20; \* Price



\### Sales Dataset



\* Records: 100

\* Features: 7

\* Main variables:



&#x20; \* Date

&#x20; \* Product

&#x20; \* Quantity

&#x20; \* Price

&#x20; \* Customer\_ID

&#x20; \* Region

&#x20; \* Total\_Sales



The customer churn dataset contains the required 500 records. The property and sales datasets are used as supplementary analytical modules.



\---



\## Technologies Used



\* Python

\* Pandas

\* NumPy

\* Matplotlib

\* Seaborn

\* SciPy

\* Scikit-learn

\* Jupyter Notebook



\---



\## Analysis Techniques



The project uses multiple analytical techniques:



\### Exploratory Data Analysis



\* Descriptive statistics

\* Missing-value analysis

\* Distribution analysis

\* Categorical analysis

\* Group-based analysis

\* Correlation analysis



\### Statistical Analysis



\* Pearson correlation

\* One-way ANOVA

\* Hypothesis testing

\* Statistical significance testing



\### Machine Learning



\#### Customer Churn



Logistic Regression was used to predict whether a customer is likely to churn.



Performance:



\* Accuracy: 93.0%

\* Precision: 75.0%

\* Recall: 54.5%

\* F1 Score: 63.2%

\* ROC-AUC: 0.982



\#### Property Pricing



Linear Regression was used to estimate property prices.



Performance:



\* MAE: 2,188,736.34

\* RMSE: 2,907,633.21

\* R²: 0.941



\---



\## Sales Statistical Analysis



A one-way ANOVA test was performed to compare average sales across East, North, South, and West regions.



Results:



\* F-statistic: 2.164

\* P-value: 0.097

\* Significance level: 0.05

\* Decision: Fail to reject H0



The result provides insufficient statistical evidence to conclude that average sales differ significantly across the four regions at the 5% significance level.



\---



\## Visualizations



The project includes visualizations covering:



\* Customer churn distribution

\* Churn by customer characteristics

\* Correlation heatmaps

\* Property price distributions

\* Property price relationships

\* Actual vs predicted property prices

\* Sales by product

\* Sales by region

\* Quantity sold by product

\* Average transaction value by region

\* Product × Region sales heatmap

\* Sales correlation heatmap



\---



\## Business Recommendations



\### Customer Retention



\* Use churn probability to identify customers who may require retention attention.

\* Develop targeted retention campaigns.

\* Monitor churn prediction performance.

\* Investigate contract and billing-related customer behavior.



\### Property Pricing



\* Use model-based price estimates as a supporting reference.

\* Consider area, bedrooms, bathrooms, age, location, and property type.

\* Compare predicted prices with actual market prices.

\* Retrain the model as new property data becomes available.



\### Sales Optimization



\* Monitor product-level sales performance.

\* Investigate lower-performing products.

\* Use product-region analysis for sales planning.

\* Monitor average transaction value.

\* Use sales relationships to support pricing and inventory decisions.



\---



\## Implementation Plan



\### Phase 1 — Customer Retention



\*\*Timeline:\*\* Month 1



\* Calculate customer churn probabilities.

\* Segment customers based on risk.

\* Launch targeted retention activities.

\* Monitor monthly churn and retention rates.



\### Phase 2 — Property Pricing



\*\*Timeline:\*\* Month 1–2



\* Use the regression model as a pricing support tool.

\* Generate estimated prices for new properties.

\* Compare predictions with actual prices.

\* Monitor prediction errors.



\### Phase 3 — Sales Optimization



\*\*Timeline:\*\* Month 2–3



\* Monitor product and regional performance.

\* Review product-region combinations.

\* Adjust inventory based on demand.

\* Evaluate targeted promotional activities.



\### Phase 4 — Continuous Monitoring



\*\*Timeline:\*\* Ongoing



\* Maintain monthly business dashboards.

\* Track key business KPIs.

\* Compare actual results with model predictions.

\* Retrain models when sufficient new data becomes available.



\---



\## Key Performance Indicators



The following KPIs can be monitored:



\* Customer churn rate

\* Customer retention rate

\* Churn prediction recall

\* Property price prediction error

\* Total sales

\* Average transaction value

\* Product sales

\* Regional sales



\---



\## Project Structure



```text

Complete-Business-Analysis/

│

├── business\_analysis.ipynb

├── requirements.txt

├── README.md

│

├── data/

│   ├── customer\_churn.csv

│   ├── house\_prices.csv

│   └── sales\_data.csv

│

├── report/

│

└── visualizations/

```



\---



\## Conclusion



This project demonstrates an end-to-end business analytics workflow, from data preparation and exploratory analysis to statistical validation, machine learning, business insights, and implementation planning.



The analysis demonstrates how data-driven techniques can support decisions related to customer retention, property pricing, and sales performance.



