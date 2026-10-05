# Shopify: Pinpoint Sales Regime Shifts Using Change Detection and T-Tests

**Tools:** Python, Pandas, SciPy, Matplotlib

## Assignment

Please answer the questions below based on the data provided:

### 1. Plot daily sales for all 50 weeks.

### 2. It looks like there has been a sudden change in daily sales. What date did it occur?

### 3. Is the change in daily sales at the date you selected statistically significant? If so, what is the p-value?

### 4. Does the data suggest that the change in daily sales is due to a shift in the proportion of male-vs-female customers?

Please use plots to support your answer. A rigorous statistical analysis is not necessary.

### 5. Daypart Analysis

Assume a given day is divided into four dayparts:

- **Night:** 12:00 AM - 6:00 AM
- **Morning:** 6:00 AM - 12:00 PM
- **Afternoon:** 12:00 PM - 6:00 PM
- **Evening:** 6:00 PM - 12:00 AM

What is the percentage of sales in each daypart over all 50 weeks?

## Data Description

The `datasets/` directory contains fifty CSV files (one per week) of timestamped sales data.

Each row in a file has two columns:

- `sale_time` - The timestamp on which the sale was made, e.g. `2012-10-01 01:42:22`
- `purchaser_gender` - The gender of the person who purchased (`male` or `female`)

## Practicalities

- Please work on the questions in the displayed order.
- Make sure that the solution reflects your entire thought process.
- It is more important how the code is structured rather than the final answers.
- You are expected to spend no more than 1-2 hours solving this project.