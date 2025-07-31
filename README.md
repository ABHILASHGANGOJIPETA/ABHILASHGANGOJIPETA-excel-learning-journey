
# 📘 Daily Excel Learning Journey

This repository documents my **day-by-day learning progress in Microsoft Excel**. I am starting from the basics and practicing important functions, uploading one Excel file each day.

---

## 📂 Files Included

| Day     | File Name                                           | Topic                                                                |
|----------|----------------------------------------------------|------------------------------------------------------------------------|
| Day 1   | excel_day1_basic_functions.xlsx                     | Basic formulas: SUM, AVERAGE, IF, COUNT                               |
| Day 2   | excel_day2_date_time_functions.xlsx                 | Date and time functions: TODAY, NOW, TEXT, DATEDIF                    |
| Day 3   | excel_day3_workdays_deadlines.xlsx                  | Working with workdays, holidays, deadlines                            |
| Day 4   | excel_day4_text_logical_series.xlsx                 | Text formulas, name extraction, LEFT, RIGHT, MID, FIND, PASTE SPECIAL, TRANSPOSE, SPACE ADDRESS, SERIES (rows, step value, date unit) |
| Day 5   | excel_day5_text_cleaning_referencing.xlsx           | Text cleaning (TRIM, CLEAN, SUBSTITUTE, REPLACE), Cell Referencing (Relative, Absolute, Mixed), Masked Phone Numbers |
| Day 6   | excel_day6_text_coloumn_tools_Flashfill_sorting.xlsx| Text to Columns, Flash Fill, Find & Replace, and Sorting Techniques (Single, Multilevel, Custom) |
| Day 7   | excel_day7_filters.xlsx                             | Filters in Excel: Number Filters, Date Filters, Relative Date Filters, Text Filters, Copy to Another Location |
| Day 8   | excel_day8_logical_operators.xlsx                   | Logical Operators (AND, OR, NOT), Bonus & PT Eligibility, Extra Pay and Allowances |
| Day 9   | excel_day9_conditional_formatting.xlsx              | Conditional Formatting: Color Scales, Data Bars, Icon Sets, New Rule Types, and Data Validation |
| Day 10  | excel_day10_data_validation_weekend_logic.xlsx      | Data Validation: Drop-down lists, gender entry, weekend-aware date correction using `=IF(WEEKDAY(T2,2)>5, T2+2, T2)` |
| Day 11  | excel_day11_lookup_functions.xlsx                   | Lookup functions: LOOKUP, VLOOKUP, XLOOKUP, INDEX, MATCH              |
| Day 12  | excel_day12_advanced_lookup_dynamic.xlsx            | Advanced Lookup Techniques: VLOOKUP with CHOOSE, OFFSET-MATCH dynamic range, HLOOKUP with MATCH, and preparing for future data entries |
| Day 13  | excel_day13_Dataextraction_Pivotetables.xlsx        | Data Extraction, Pivot Table Analysis, Region-wise Summary, Manager Mapping, Return Status Integration |
| Day 14  | excel_day14_powerquery_cleaning_pivot.xlsx          | Power Query Editor: Data Cleaning, Merging Returns/People/Orders Tables, and Pivot Table Summaries on Orders, Returns, and Sales by Person |
| Day 15  | excel_day15_vba_macros_udf.xlsm                     | VBA Macros (Recorded), User Defined Functions (UDFs), Custom Automation Tasks |

---

## ✅ Topics Practiced

### ➕ Math and Statistical Functions
- SUM, AVERAGE, MEDIAN, MODE, MAX, MIN.

### 🔢 Counting Functions
- COUNT, COUNTA, COUNTBLANK, COUNTIF, COUNTIFS

### ❓ Conditional Logic
- IF, SUMIF, AVERAGEIF, SUMIFS, AVERAGEIFS, MINIFS, MAXIFS

### 📅 Date and Time Functions
- TODAY, NOW, TEXT, WEEKDAY, WEEKNUM, EDATE, EOMONTH, DATEDIF, YEARFRAC

### 🗓️ Workday and Calendar Functions
- NETWORKDAYS, NETWORKDAYS.INTL, WORKDAY, WORKDAY.INTL

### 🔄 Number Formatting
- ROUND, ROUNDDOWN, ROUNDUP, TEXT

### 🔤 Text and Logical Functions
- LEFT, RIGHT, MID, LEN, FIND, SEARCH, CONCAT, LOWER, UPPER, PROPER

### ✂️ Text Cleaning and Replacement
- TRIM, CLEAN, SUBSTITUTE, REPLACE

### 📌 Cell Referencing Techniques
- Relative, Absolute, and Mixed Referencing

### 🔐 Data Masking Examples
- Masking and formatting phone numbers using formulas

### 🧰 Utility Features
- PASTE SPECIAL, TRANSPOSE, SPACE ADDRESS, SERIES dialog box (Rows, Columns, Linear, Step value, Date unit)

### 📊 Text to Columns
- Delimited Characters, Fixed Width

### 🔍 Find & Replace
- CTRL + F (Find), CTRL + H (Replace)

### ⚡ Flash Fill
- Auto-fill initials and email patterns using CTRL + E

### 🔽 Sorting
- Ascending/Descending, Multilevel, Custom Sorting

---

## 🧼 Filters

- Number Filters (greater than, top 10, between)
- Date Filters (before, after, this month, last week)
- Relative Date Filters (today, yesterday, next week)
- Text Filters (contains, begins with, ends with)
- Copy to Another Location (using Advanced Filter)

---

## 🔗 Logical Operators

Used `AND`, `OR`, and `NOT` to:
- Calculate bonus eligibility
- Check employment status
- Apply conditions to multiple salary components (PT, HRA, EXTRA PAY)

---

## 🎨 Conditional Formatting (Day 9)

- Format all cells based on their values
- Format only cells that contain specific text, numbers, or dates
- Highlight Top/Bottom N ranked values
- Highlight above or below average values
- Highlight duplicates and unique entries
- Custom formula-based formatting (e.g., `=A1>100`)

### 🔵 Advanced Visual Formatting
- **2-Color Scales:** Apply gradients between two colors  
- **3-Color Scales:** Add a midpoint color to the gradient  
- **Data Bars:** Visual bars representing value magnitude within cells  
- **Icon Sets:** Use icons (arrows, flags, etc.) based on cell thresholds  

---

## ✔️ Data Validation

- Restrict inputs using:
  - Drop-down lists (e.g., gender selection)
  - Number ranges
  - Date ranges
  - Custom validation formulas

- Skip weekends using:
```excel
=IF(WEEKDAY(T2,2)>5, T2+2, T2)
```

---

## 📊 Data Extraction & Pivot Tables

In the file demonstrates:

📌 Pivot Tables: Average Sales summarized by Region and Segment  
🔍 Data Filtering: Segment/Region-specific extraction using filters  
👤 Manager Mapping: Region-wise manager added using a lookup table  
🔁 Return Status Integration: Merged order return data for analysis  
🧹 Final Dataset: Clean, enriched summary with new columns (Manager_name, return_status)

---

## 🔧 Power Query Editor

- Cleaned multiple sheets (Orders, Returns, People) using Power Query Editor  
- Applied data transformations:
  - Removed nulls, renamed columns, ensured correct data types  
  - Merged Returns into Orders by Order ID  
  - Mapped region managers from the People table  
- Transferred cleaned data to Excel  
- Built pivot tables to summarize:
  - Order quantity, sales, and profit by region and segment  
  - Return trends by category and responsible person

---

## 👨‍💻 About Me

I am Abhilash Gangojipeta, currently learning Excel with the goal of mastering data handling, logic building, and project planning.  
This repository is my daily log and showcases my consistency and dedication to self learning.

---

## 💡 How to Use

- Download any `.xlsx` file from the repository  
- Open the file in Microsoft Excel  
- Explore the formulas, formatting, and logic used in each sheet  
- Practice or reuse the methods to improve your own Excel skills

---

## 📣 Note

This is an open learning project.  
Feel free to explore, clone, or use these files for your own Excel learning journey.
