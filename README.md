﻿# KEMSA-2025PRICES-Notebook

 ## Summary
- **Objective:** Built a machine learning model to forecast pharmaceutical product prices for KEMSA in 2025, using 2017 data.
- **Approach:** Cleaned and engineered features from the KEMSA price list, applied a Random Forest regression model, and tuned hyperparameters for optimal performance.
- **Key Features:** Dosage, pack size, and product category were among the most influential factors in price prediction.

## Key Findings
- The tuned model achieved strong predictive performance (see RMSE, MAE, and R² scores above).
- **Dosage** and **pack size** are the most significant drivers of price, followed by product category.
- There is substantial price variation across product categories (e.g., tablets/capsules vs. oral liquids).
- The model’s forecasts can help KEMSA anticipate 2025 prices for budgeting and procurement.

## Limitations
- The analysis used 2017 data; market conditions, inflation, and new products may affect 2025 prices.
- Some product features (e.g., formulation specifics, supplier differences) were not included due to data limitations.
- The model assumes historical patterns will generally hold in the future.

## Recommendations
- **Use these forecasts** as a guide for procurement planning, but update the model regularly with new data for greater accuracy.
- **Monitor key drivers** (dosage, pack size, category) when negotiating prices or evaluating supplier quotes.
- **Expand the dataset** with more recent price lists and additional product attributes for future analyses.

