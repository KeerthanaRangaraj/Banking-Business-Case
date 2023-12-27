# Banking-Business-Case

Problem Statement: A major bank asking for help in analysing its current
customer base and its marketing campaigns. It wants to understand which customers are most likely
to take a term deposit (fixed deposit), and then send this list to their call centre.

The data has been provided in attached excel sheet. You as NeoStats employee are tasked with
carrying out this project. Please carry out the analysis and answer the questions given below.
Make suitable assumptions, define the steps clearly and document your code when required.

Guidelines for Submission:
1. Data Analysis Tool:
 Use python for all the analysis. Share the Jupyter notebook or Google Colab link for data pre-
processing, analysis, visualization, and model training.
2. Presentation:
 Prepare a crisp PowerPoint presentation summarizing your findings, approach, and results.
Keep it within a 10-minute timeframe to maintain engagement.
3. Question &amp; Answer Session:
 After your presentation, be prepared for a 5-minute Q&amp;A round. Ensure you understand
every aspect of your analysis and approach, as the panel might ask in-depth or technical
questions.

Analysis Questions:
 Data Analysis &amp; Visualization:
1. Income Insights:
 How many customers have no annual income? Plot and present the data distribution
of these customers.
2. Loan-less Customers Profile:
 Filter out customers who don’t have any type of loan. Plot the distribution of their
Income, balance, and profession. How do these metrics differ from those with
loans?
3. Loan and Insurance Analysis:
 Calculate the percentage of customers with a loan who have taken out insurance.
Visualize this data and discuss potential implications.

4. Communication Strategy Insights:
 Analyse and summarize the best Contact method (with the highest success
percentage) to contact people to ascertain the status of term deposit subscriptions.
5. Age and Home Loans:
 Determine which age group has the highest percentage of home loans. Present this
data visually and discuss possible reasons.
6. Income and Age Relationship:
 Investigate any relationships between annual income and age group. Use
appropriate plots and statistics to present the findings.

Modeling:
1. Term Deposit and Related Variables:
 Identify variables strongly related to Term Deposit. Discuss your approach when the
variable is categorical. Which tests or metrics will you employ?
2. Predictive Model Building:
 Train a prediction model of your choice to estimate the probability that a customer
will opt for a term deposit. Adhere to an 80:20 train:test split. Report and present
the model&#39;s performance metrics on both the train and test datasets.
3. Model Improvement Strategies:
 Discuss potential methods or approaches to enhance model performance. This could
include feature engineering, different algorithms, or refining the data preprocessing
steps.


## Approach

The folder contains necessary Python files and data for the analysis and solutions of the NeoStats Banking Case.

## Included Dataset
- `Banking Case-Data.xlsx`: Excel file containing the original dataset used for analysis.
- `TransactionData.csv`: CSV file containing the data for Banking Transactions after Cleaning.
- `CustomerData.csv`: CSV file containing the data for Customer Demographics after Cleaning.


## Included Notebooks

### 1. BankingCase_Preprocessing.ipynb
- Focuses on handling junk values and cleaning categorical and numerical columns within the dataset. The cleaned data are saved as 'TransactionData.csv' and 'CustomerData.csv'.

### 2. BankingCase_AnalysisQuestions.ipynb
- Provides visualizations and answers analytical questions pertaining to the dataset.

### 3. BankingCase_Modelling.ipynb
- Focuses on modeling to classify Term Deposit using various machine learning models.
- Includes a comparative analysis of the models' performance.

The notebooks sequentially address data preprocessing, exploratory analysis, and modeling phases to achieve solutions and insights for the Banking Case.

## Usage
1. Ensure the required libraries are installed (e.g., pandas, numpy, matplotlib, scikit-learn).
2. Open and run the notebooks sequentially: Preprocessing → Analysis Questions → Modelling.
3. Modify the code and paths as needed for your specific dataset or analysis.

## Note
Ensure the necessary dataset files or data sources are available and correctly referenced within the notebooks.

### Author
Keerthana R
keerthanarangaraj812@gmail.com
