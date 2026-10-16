# Automobile Sales Dashboard with Plotly Dash

This project builds an interactive web dashboard to explore automobile sales data from 1980 to 2023. Users can view two sets of statistics: recession‑period sales and yearly sales for a selected single year.

## Research Question

How do automobile sales change during economic recessions, and what are the yearly and monthly sales trends across different vehicle types? We also look at advertising spending and how unemployment rates affect vehicle sales.

## Dataset Source and Usage Permissions

The dataset `automobile‑sales.csv` is loaded from IBM course public cloud storage. It is open educational data for learning and assignment purposes only. Do not use this dataset for commercial work.

## Methods and Tools

- **Python**: Main programming language
- **Pandas**: Clean, filter and group the raw dataset
- **Plotly Express**: Generate interactive line charts, bar charts and pie charts
- **Dash**: Build interactive web dashboard with dropdown controls and callback functions

## Key Findings and Limitation

### Key Findings

During recession periods, average automobile sales tend to drop. Different vehicle types receive different shares of advertising budget. Unemployment rate also has visible influence on sales performance for each car type. For yearly view, we can observe full‑period sales trends, monthly sales distribution and vehicle‑level advertising costs for any chosen year.

### Limitation

The dataset does not include inflation adjustment. Sales numbers are raw values and cannot reflect real purchasing power over decades.

## How to Run the Analysis

1. Install required packages:

```
pip install dash pandas plotly
```

2. Save the Python script as `DV0101EN‑Final_Assign_Part_2_Questions.py`
3. Run the script in your local terminal.
4. Open the local web link shown in terminal (usually `http://127.0.0.1:8050`) in your browser.
5. Use the dropdown menus:
   - Choose `Recession Period Statistics` to view recession‑related charts.
   - Choose `Yearly Statistics`, then pick one target year to load yearly‑report visualizations.

> 
> Note: No private keys, passwords or personal information are included in this repository.
