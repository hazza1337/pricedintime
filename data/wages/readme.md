#Instructions for adding wages data

Wage data (aka hourly earnings data) should have a reliable source - government stats, or other institutions that can accurately track this data. 

No Currency Symbols: The price and wage values should be numeric only. Do not include currency symbols (e.g., $, £, €). The application does not currently support currency symbols in the data files.
Valid JSON: Always validate your JSON files to ensure they are correctly formatted. You can use online JSON validators for this purpose.
Date Format: Adhere strictly to the YYYY-MM-DD date format.
Date Cleaning: Ensure that the date used for wage data is the last date of the month. e.g. December 20th, 2025 should be converted to 2025-12-31.
