# Retrieve-Company-Fundamentals
Python Script to Retrieve Company Fundamentals
The main goal of the code is to get company financials from the last 5 years. Then, calculate some growth metrics and export to an Excel file.
Request data from the free financial API financialmodelingprep. It is free up to 250 requests per month. You just need to sign up to start using the api Key. If 250 requests a month are not enough, you can use the following discount code to get a yearly subscription for a bit more than $100 per year.
Load into a Python variable the main financial data requested from the API. That is, IS, BS, CF and main financial ratios
Create an empty dictionary in order to store the values using the respective year as the key.
Transform the dictionary into a Pandas DataFrame
Calculate a few growth measures as new columns
Export to Excel
