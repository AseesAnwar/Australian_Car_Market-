# Australian Used Car Depreciation Analysis

## Overview
This project analyses Australian used vehicle listing data to understand how **vehicle age impacts price** and how depreciation patterns differ across brands. The analysis focuses on **depreciation risk and value retention**, which are relevant for inventory and pricing decisions.

## Business Questions
- How does vehicle age affect resale price in today’s market?
- Do all brands depreciate at the same rate?
- How do conclusions change when comparing **absolute vs relative** value loss?

## Dataset
- Source: Australian used vehicle listings
- Rows: ~16,000 vehicles
- Key fields: Brand, Year, Price, Kilometres, FuelType, Location, BodyType

> Note: The dataset does not include acquisition cost, holding time, or maintenance costs.  
> Findings are framed as **price-based depreciation risk**, not profit.

## Key Insight
Absolute price drops can make lower-priced brands appear “safer” by default.  
Relative value loss (percentage) provides a more reliable comparison of depreciation risk across brands.

## Example Output
![Relative Value Loss by Brand](Carbrandchart.png)

## Limitations
- No buy price or time-to-sell data
- Results should be interpreted as market price behaviour, not profitability

## Next Steps
- Compare mileage vs age to test which explains price better
- Extend analysis using SQL/Python for automation

