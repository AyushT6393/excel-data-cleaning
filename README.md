# Raw-to-Clean Data Conversion & Automation

## Objective
Converted inconsistent, raw sample records (mixed formats, spacing, casing) into a clean, standardized dataset.

## Cleaning Steps Performed in Excel:
1. **Removing Extra Spaces:** Used the `=TRIM()` function to clean up leading and trailing spaces in names and emails.
2. **Standardizing Text Casing:** Used `=PROPER()` for Full Names to capitalize the first letter, and `=LOWER()` for Email Addresses.
3. **Data Validation:** Applied Dropdown Data Validation to the "Status" column to only accept "Paid" or "Unpaid".
4. **Auto-Calculation:** Used `=SUM()` to automatically calculate the total fee collected at the bottom of the sheet, ensuring zero manual calculation errors.

## Result
A fully formatted, professional spreadsheet ready for database import.
