# Excel Basics Learning Journey

## Overview
This repository documents my journey in learning **Microsoft Excel** by applying key functions and formulas to real-world datasets. The goal is to build a solid foundation in Excel for data analysis, reporting, and automation.

## Skills Covered
- **Logical Functions**: `IF`, `IFS`, `AND`, `OR`
- **Aggregate Functions**: `SUM`, `AVERAGE`, `MAX`, `MIN`, `PERCENTAGE`
- **Conditional Functions**: `SUMIF`, `SUMIFS`, `COUNTIF`, `COUNTIFS`, `AVERAGEIF`, `AVERAGEIFS`
- **Text Functions**: `LEFT`, `RIGHT`, `LEN`, `TRIM`, `FIND`, `SEARCH`, `TEXT TO COLUMNS`

## Dataset Used
The dataset contains employee details such as:
- **Employee Name**
- **Employee ID**
- **Department**
- **Salary**
- **Bonus %**
- **Total Sales**
- **Region**
- **Experience (Years)**
- **Age**
- **Gender**
- **Performance Rating**
- **Email**

## Key Applications
Here are some real-world Excel challenges I solved:
1. **Basic Calculations & Aggregations**:
   - Calculated the **Bonus Amount** for each employee.
   - Found the **total salary expense** using `SUM()`.
   - Counted the **number of employees in each department** using `COUNTIF()`.
   - Found the **average salary of employees in each region** using `AVERAGEIF()`.
   
2. **Text & Data Extraction**:
   - Extracted **first three letters** of employee names using `LEFT()`.
   - Extracted **last three letters** of employee names using `RIGHT()`.
   - Extracted **first names from emails** using `TEXT TO COLUMNS()`.
   - Trimmed unnecessary spaces from names using `TRIM()`.
   - Converted all names to **uppercase** and **lowercase** using `UPPER()` and `LOWER()`.

3. **Conditional & Logical Functions**:
   - Identified employees whose **Performance Rating is above 4.5** and tagged them as `"Top Performer"` using `IF()`.
   - Identified employees with **Salary above 55,000** and labeled them `"High Salary"` using `IF()`.
   - Labeled employees in **Sales or IT** as `"Core Business"` using `IF(OR())`.
   - Tagged employees as **Top Performer, Average, or Needs Improvement** based on their Performance Rating using `IFS()`.
   - Identified employees under **30 years old** as `"Young Employee"` using `IF()`.
   - Labeled employees with **at least 5 years of experience** as `"Senior Employee"` using `IF()`.

4. **Counting & Summing Based on Conditions**:
   - Counted employees in **Sales department** using `COUNTIF()`.
   - Counted employees with a **Performance Rating above 4.5** using `COUNTIF()`.
   - Counted employees with **experience greater than 5 years** using `COUNTIF()`.
   - Counted employees who are **Female** using `COUNTIF()`.
   - Counted employees whose **name contains the letter 'a'** using `COUNTIF()` with `SEARCH()`.
   - Counted employees with a **Performance Rating > 4.5 in the IT department** using `COUNTIFS()`.
   
5. **Summing & Averaging with Multiple Criteria**:
   - Calculated the **total sales** made by employees in the **East region** using `SUMIF()`.
   - Calculated the **total sales** made by **IT employees** using `SUMIF()`.
   - Found the **average performance rating** of employees in the **Finance department** using `AVERAGEIF()`.
   - Found the **total bonus paid** to employees in the **HR department** using `SUMIFS()`.
   - Found the **average salary** of employees with **more than 5 years of experience** using `AVERAGEIF()`.
   - Found the **average salary** of employees with a **Performance Rating > 4.5 in the Finance department** using `AVERAGEIFS()`.

6. **Other Analytical Insights**:
   - Calculated the **percentage of employees in each region** using `COUNTIF()` and division.
   - Identified the **employee with the longest name** using `LEN()` and `MAX()`.
   - Identified the **employee with the shortest name** using `LEN()` and `MIN()`.
   - Found the **total salary of employees in the Sales department** using `SUMIF()`.

## How to Use
1. Download or clone this repository.
2. Open `basics_questions.xlsx` in Excel.
3. Review the formulas applied in different sheets (`Data Employee`, `Data 2`).
4. Experiment with the dataset by modifying conditions and applying new formulas.

## Contributing
If you have any suggestions or additional Excel challenges to try, feel free to open an issue or submit a pull request.

## Connect With Me
I'm actively learning and open to feedback! Let's connect on **[LinkedIn](https://www.linkedin.com/in/nidhi-kachhi)** and grow together. 🚀
