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
- For **monthly data**, use the **last day of the month**:
  - Example: `December 20, 2025` ➝ `2025-12-31`.
