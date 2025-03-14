# Excel Price Correction and Chart Generator

## Overview
This project processes an Excel workbook using the `openpyxl` library to apply a price correction and generate a bar chart based on the corrected prices.

## Features
- Reads an Excel file (`.xlsx`) containing a sheet named "Sheet1".
- Applies a 10% discount to the prices in the third column.
- Writes the corrected prices in the fourth column.
- Generates a bar chart representing the corrected prices.
- Saves the modified workbook.

## Requirements
Ensure you have Python installed along with the following dependencies:
```bash
pip install openpyxl
```

## Usage
1. Prepare an Excel file with a sheet named `Sheet1`, where:
   - Column 3 contains original prices.
   - Column 4 will store corrected prices.
2. Run the script by calling the `process_workbook` function with the filename:
   ```python
   process_workbook('yourfile.xlsx')
   ```
3. The script will generate a new column with discounted prices and add a bar chart in the sheet.

## Notes
- Ensure the Excel file is properly formatted before running the script.
- The function modifies the original file; create a backup if needed.

## Author
Minhazur Rahman



