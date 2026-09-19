# Data Quality Profiling — Big Mac Index

## Objective

The purpose of this lab was to identify and correct coding and methodological errors using the Big Mac Index.

## What I Did

- Corrected a PPP valuation formula.
- Compared complete-panel results with results using all available countries.
- Measured the bias caused by removing incomplete countries.
- Created a function that profiles the structure and missingness of a dataset.

## Results

Switzerland was the most overvalued currency at approximately 41.8%. Removing incomplete countries overstated the average price by $0.081, or 2.1%, and produced a higher average in 33 of 45 periods. The data is an unbalanced panel with 57 units, 45 periods, and 25 complete units.
