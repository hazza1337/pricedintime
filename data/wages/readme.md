# Data Sources
If you have access to or can get access to better historical datasets, or if you believe any of the data here is incorrect: DM me on X.com: @hfletcherjones.

## United States
US Average Earnings [us_average_earnings.json]
- Personal income per capita (A792RC0Q052SBEA) from FRED: https://fred.stlouisfed.org/series/A792RC0Q052SBEA
  - Transformation: Assuming 233 days × 8 hours/day = 1,864 hours/year.  Per capita income / 1864 = Hourly earnings. Calculate the average for each year, and set it to the last day of the year. 
    - This aligns closely with BLS averages for full-time workers (~1,800–1,900 hrs/year depending on methodology and inclusion of part-time roles).
 
  
## New Zealand 
Earnings data is sourced from Stats NZ: https://explore.data.stats.govt.nz/
- I’m seeking datasets with a more comprehensive historical range.



# Instructions for Adding Wages Data

When contributing wage data (also known as hourly earnings data), follow these guidelines to ensure consistency and proper functionality in the application.

## ✅ Source Requirements
- Use only **reliable sources** such as official government statistics agencies or reputable institutions.
- Data must be traceable and accurate.

## 🚫 No Currency Symbols
- All wage and price values must be **numeric only**.
- **Do not include** any currency symbols (`$`, `£`, `€`, etc.).
- The application currently does **not support** currency symbols in data files.
- When adding wage data, ensure it is in the local currency. E.g. New Zealand data should have price data in NZD, United States data in USD, etc. 

## ✅ Valid JSON
- Always **validate your JSON** to ensure it is correctly formatted.
- Use tools like [JSONLint](https://jsonlint.com/) or similar online validators.

## 📅 Date Formatting
- Dates must be in the format: `YYYY-MM-DD`.
- For **monthly data**, use the **last day of the month**. Convert it to the last day of the month where required.
  - Example: `December 20, 2025` ➝ `2025-12-31`.
