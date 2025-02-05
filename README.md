# 📊 Spreadsheet Automation with Python
**Automating Excel Data Processing & Visualization**

## 🔹 Overview
This Python project automates spreadsheet processing by **modifying price data** and **visualizing results**. The script reads an Excel file, applies a price correction, adds a new column with adjusted values, and generates a bar chart to visually represent the data. The final output is saved as a new spreadsheet.

## 🎯 Purpose
- Automate **bulk price adjustments** in an Excel sheet.
- Demonstrate **data manipulation and visualization** using Python.
- Provide a **structured and efficient approach** for modifying spreadsheet data.

## 🛠 Methods & Approach
1. **Read Data:** Load the Excel file (`transactions.xlsx`) using `openpyxl`.
2. **Modify Prices:** Reduce all prices by **10%** and store them in a new column.
3. **Generate Bar Chart:** Create a **visual representation** of the adjusted prices.
4. **Save Output:** Store the modified data and chart in a new file (`transactions2.xlsx`).

## 📂 Project Structure
```
spreadsheet-automation-python/
│── app.py               # Main Python script
│── transactions.xlsx    # Original spreadsheet
│── transactions2.xlsx   # Processed spreadsheet with modifications & chart
│── README.md            # Project documentation
```

## 🚀 Technologies Used
- **Python** 🐍
- `openpyxl` (for reading/writing Excel files)
- `BarChart` from `openpyxl.chart` (for visualization)

## 📸 Example Output
✔ **Updated Prices Column**  
✔ **Auto-Generated Bar Chart**  
_(See screenshot below)_  

![Spreadsheet Output](https://github.com/Pouria-Samadi/spreadsheet-automation-python/issues/1#issue-2833316784)  


## 📥 Installation & Usage
### 🔧 Prerequisites
Ensure you have Python installed. Install the required library:
```bash
pip install openpyxl
```

### ▶️ Running the Script
Execute the script to process the spreadsheet:
```bash
python app.py
```

## 📝 Future Improvements
- Add **dynamic user input** for price adjustment percentage.
- Support **multiple sheets** in an Excel file.
- Expand visualization with **additional chart types**.
```
