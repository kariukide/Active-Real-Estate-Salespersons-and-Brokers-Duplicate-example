# Data Analyst II Interview Excercise
### Question: 
  Our department has huge datasets that have duplicate records. What is one you could help with deduping these datasets that are      now handled in spreadsheets?

## Active-Real-Estate-Salespersons-and-Brokers-Duplicate-example
## The data
The data was obtained from; https://data.ny.gov/Economic-Development/Active-Real-Estate-Salespersons-and-Brokers/yg7h-zjbf. The database was collected in December - 2015 to October - 2023.

This data contains active Real Estate Salesperson and Broker Licenses from New York State Department of State (DOS). Each line will be either an individual or business licensee which holds business address and license number information. If the license type is an individual, the business name that the individual works for will be listed.

## Solution
I utilized pandas in jupyter to read and dedupe the active real estate salespersons and brokers data.

Technology; Python, Jupyter, Pandas, drop_duplicates() method


