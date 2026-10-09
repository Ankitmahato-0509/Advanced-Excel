# Advanced Excel: Learning Notes and Practice

This repository contains my **personal notes and practice files for Excel**.
Each section includes the **Excel file name, key concepts, practical exercises, and screenshots of the results for quick reference**.

# 01. SUMPRODUCT

**File:** `01.SUMPRODUCT.xlsx`

### Concepts Covered

- SUMPRODUCT Function
- Array Multiplication
- Multiplying corresponding values
- Calculating total sales
- Calculating total revenue
- Conditional Calculations
- Applying multiple conditions
- Sales data analysis
- Revenue calculations
- Performing calculations without helper columns


## Array Multiplication

This exercise demonstrates how the **SUMPRODUCT function** can be used to multiply corresponding values in two arrays and return the sum of the resulting products.

### Dataset

The dataset includes:

- Product
- Price
- Quantity

### Calculation

This exercise calculates total product sales by multiplying the corresponding **Price** and **Quantity** values.

### Screenshot

![Array Multiplication](https://github.com/Ankitmahato-0509/Advanced-Excel/blob/main/Images/Screenshot%202026-09-05%20183409.png?raw=true)


## Revenue Calculations

This exercise demonstrates how **SUMPRODUCT** can calculate revenue from sales data.

### Dataset

The dataset includes:

- Order ID
- Product
- Region
- Salesperson
- Quantity
- Unit Price

### Calculations

The exercise calculates:

- Revenue from all orders
- Revenue for specific products
- Revenue using Quantity and Unit Price

### Screenshot

![Revenue Calculations](https://github.com/Ankitmahato-0509/Advanced-Excel/blob/main/Images/Screenshot%202026-09-05%20183431.png?raw=true)


## Conditional Calculations

This exercise demonstrates how **SUMPRODUCT** can be combined with conditions to perform conditional calculations.

### Dataset

The dataset includes:

- ID
- Country
- Salesperson
- Total

### Conditions Covered

- Checking salesperson conditions
- Checking country conditions
- Applying multiple conditions
- Counting orders based on conditions
- Calculating total sales based on conditions

### Screenshot

![Conditional Calculations](https://github.com/Ankitmahato-0509/Advanced-Excel/blob/main/Images/Screenshot%202026-09-05%20183420.png?raw=true)


## Data Analysis

The exercise uses **SUMPRODUCT** for array multiplication, revenue calculations, and conditional calculations.

The analysis covers:

- Calculating total product sales
- Calculating total revenue
- Calculating product-specific revenue
- Analyzing sales by salesperson
- Analyzing sales by country
- Applying multiple conditions
- Performing conditional calculations

# 02. Advanced XLOOKUP and XMATCH

**File:** `02.Advanced XLOOKUP & XMATCH.xlsx`

### Concepts Covered

- XMATCH Function
- XLOOKUP Function
- Multiple-Criteria XLOOKUP
- Reverse XLOOKUP
- Exact Match
- Wildcard Match
- Multiple Conditions
- Searching from Last to First
- Dynamic Lookup
- Advanced Data Retrieval

---

## XMATCH Function

The **XMATCH function** returns the relative position of a value within a range or array.

### Dataset

The dataset contains student information:

- Student_ID
- Student_Name
- Course
- Subject
- City
- Marks
- Grade

### Exercises

- Find the position of a student name using a wildcard.
- Find the position of a value within a range.
- Use wildcard matching for partial text.

### Concepts Covered

- Exact Match
- Wildcard Match
- Finding the position of a value
- Using `*` wildcard
- Dynamic position lookup

### Screenshot

![XMATCH Function](https://github.com/Ankitmahato-0509/Advanced-Excel/blob/main/Images/Screenshot%202026-10-08%20063658.png?raw=true)

---

## Multiple-Criteria XLOOKUP

**XLOOKUP** can be combined with multiple conditions to retrieve a value when more than one criterion must be met.

### Dataset

The dataset contains employee information:

- Employee_ID
- Employee_Name
- Department
- Job_Title
- City
- Experience_Years
- Salary
- Performance_Rating

### Exercises

- Find the **Salary** of an employee who works in **IT** and **Delhi**.
- Find the **Department** of an employee based on **Employee Name** and **City**.
- Find the **Employee** where **Department = Finance** and **Experience = 6**.

### Concepts Covered

- Multiple-Criteria XLOOKUP
- Combining multiple conditions
- Concatenating lookup criteria
- Retrieving data using multiple conditions
- Advanced employee data lookup

### Screenshot

![Multiple-Criteria XLOOKUP](https://github.com/Ankitmahato-0509/Advanced-Excel/blob/main/Images/Screenshot%202026-10-08%20063713.png?raw=true)

---

## Reverse XLOOKUP

**Reverse XLOOKUP** searches from the **last occurrence to the first occurrence**.

This is useful when you need to find the **latest or last matching record**.

### Dataset

The dataset contains order information:

- Order_ID
- Customer_Name
- Product
- Category
- City
- Salesperson
- Amount

### Exercises

- Find the **last customer who bought a Laptop**.
- Find the **last customer handled by salesperson Amit**.
- Find the **Order ID of the last order from Delhi**.
- Find a customer who bought a **Laptop from Delhi**.

### Concepts Covered

- Reverse XLOOKUP
- Last occurrence lookup
- Searching from bottom to top
- Finding the latest matching record
- XLOOKUP Search Mode
- Dynamic lookup

### Screenshot

![Reverse XLOOKUP](https://github.com/Ankitmahato-0509/Advanced-Excel/blob/main/Images/Screenshot%202026-10-08%20063729.png?raw=true)

---

# XLOOKUP and XMATCH Summary

| Function / Technique | Purpose |
|---|---|
| **XMATCH** | Finds the position of a value in a range |
| **XMATCH Wildcard** | Finds a position using wildcard matching |
| **XLOOKUP** | Searches for a value and returns a related result |
| **Multiple-Criteria XLOOKUP** | Performs lookups using multiple conditions |
| **Reverse XLOOKUP** | Finds the last matching occurrence |
| **Wildcard `*`** | Matches any number of characters |
| **Search Mode `-1`** | Searches from last to first |

---

# Data Analysis

These exercises demonstrate how **XLOOKUP and XMATCH** can be used for advanced Excel data analysis.

The practice includes:

- Finding the position of values
- Using wildcard matching
- Performing multiple-condition lookups
- Finding employee salary
- Finding employee department
- Finding employees based on multiple conditions
- Finding the last matching customer
- Finding the last order from a specific city
- Searching from bottom to top
- Performing advanced lookups without helper columns

## Key Takeaways

**XLOOKUP** and **XMATCH** are powerful modern Excel functions for performing flexible and dynamic lookups.

By combining these functions with **multiple criteria, wildcard matching, and reverse searching**, complex lookup requirements can be handled efficiently in Excel.

# 03. Dynamic Array Functions

**File:** `03.Dynamic Array Functions.xlsx`

## Concepts Covered

* Dynamic Array Functions
* FILTER Function
* SORT Function
* SORTBY Function
* UNIQUE Function
* SEQUENCE Function
* Combining Dynamic Array Functions
* Filtering data based on conditions
* Sorting data dynamically
* Extracting unique values
* Generating sequential numbers
* Creating dynamic reports
* Working with spilled arrays
* Performing calculations without helper columns

---

# Dataset

The exercises use a **One Piece Characters dataset** containing information about different characters.

### Dataset Columns

* Character
* Gender
* Affiliation
* Role
* Bounty_M
* Age
* Devil_Fruit
* Haki
* Origin
* Status
* Rank
* Height_cm
* First_Appearance

This dataset is used throughout the exercises to demonstrate how Dynamic Array Functions can return multiple results automatically.

### Dataset Screenshot

![Dataset](Images/Screenshot%202026-10-08%20064520.png)

---

# FILTER Function

The **FILTER function** is used to return only the rows or columns that meet a specified condition.

### Exercise

Find the crew members of the **Straw Hat Pirates** from the dataset.

### Concepts Covered

* Filtering rows based on a condition
* Using a text condition
* Returning multiple matching records
* Dynamic spilling of results
* Filtering an entire dataset

### Example

The FILTER function is used to return characters whose **Affiliation** is:

`Straw Hat Pirates`

### Screenshot

![FILTER Function](Images/Screenshot%202026-10-08%20064536.png)

---

# SORT Function

The **SORT function** is used to dynamically sort a dataset based on a selected column.

### Exercise

Sort the dataset based on **Bounty**, from:

**Highest to lowest**

### Concepts Covered

* Sorting data dynamically
* Sorting based on a specific column
* Descending order
* Returning the complete sorted dataset
* Dynamic array sorting

### Example

The dataset is sorted using the **Bounty_M** column in descending order.

### Screenshot

![SORT Function](Images/Screenshot%202026-10-08%20064558.png)

---

# SORTBY Function

The **SORTBY function** is used to sort one array based on the values in another array.

### Exercise

Sort the dataset based on **Age**, from:

**Highest to lowest**

### Concepts Covered

* Sorting using another range
* Sorting by Age
* Descending order
* Dynamic sorting
* Sorting an entire dataset based on a selected column

### Example

The dataset is dynamically sorted using the **Age** column.

### Screenshot

![SORTBY Function](Images/Screenshot%202026-10-08%20064623.png)

---

# UNIQUE Function

The **UNIQUE function** is used to extract distinct values from a dataset.

### Exercise

Find all unique **Affiliations** from the dataset.

### Concepts Covered

* Extracting unique values
* Removing duplicate values
* Creating dynamic lists
* Working with text data
* Dynamic spilling of unique results

### Example

The UNIQUE function is used to create a list of all unique affiliations such as:

* Marines
* Whitebeard Pirates
* Straw Hat Pirates
* Revolutionary Army
* Big Mom Pirates
* and other affiliations

### Screenshot

![UNIQUE Function](Images/Screenshot%202026-10-08%20064637.png)

---

# SEQUENCE Function

The **SEQUENCE function** is used to generate a sequence of numbers automatically.

### Exercise

Generate a sequential number for each character in the dataset.

### Concepts Covered

* Generating sequential numbers
* Automatic numbering
* Dynamic arrays
* Creating serial numbers
* Using SEQUENCE with other data

### Example

The SEQUENCE function generates numbers such as:

`1, 2, 3, 4, 5, ...`

for the characters in the dataset.

### Screenshot

![SEQUENCE Function](Images/Screenshot%202026-10-08%20064650.png)

---

# Combining Dynamic Array Functions

Dynamic Array Functions can be combined to perform more advanced data analysis.

### Exercise

Find **Straw Hat Pirates** and sort them based on their **Bounty**.

### Concepts Covered

* Combining FILTER and SORT
* Filtering data first
* Sorting filtered results
* Creating dynamic reports
* Working with multiple dynamic arrays
* Performing analysis without helper columns

### Example

The exercise first filters the dataset to find members of the following affiliation:

`Straw Hat Pirates`

The filtered results are then sorted based on **Bounty**.

### Screenshot

![Combining Dynamic Array Functions](Images/Screenshot%202026-10-08%20064711.png)

---

# Dynamic Array Functions: Summary

| Function | Purpose |
|----------|---------|
| **FILTER** | Returns data that meets specified conditions |
| **SORT** | Sorts an array based on a selected column |
| **SORTBY** | Sorts an array based on another range |
| **UNIQUE** | Returns unique values from a range |
| **SEQUENCE** | Generates a sequence of numbers |
| **Combined Functions** | Performs advanced dynamic data analysis |

---

# Data Analysis

These exercises demonstrate how Dynamic Array Functions can make Excel analysis more efficient and flexible.

The analysis covers:

* Filtering characters based on affiliation
* Sorting characters by bounty
* Sorting characters by age
* Extracting unique affiliations
* Generating automatic sequence numbers
* Creating dynamic filtered reports
* Combining FILTER and SORT
* Working with automatically expanding results
* Reducing the need for helper columns

## Key Takeaways

Dynamic Array Functions allow Excel formulas to **return multiple results automatically** and let those results **spill into adjacent cells**.

These functions are especially useful for:

* Data cleaning
* Data analysis
* Dynamic reports
* Dashboard preparation
* Creating automated lists
* Sorting and filtering large datasets
* Reducing manual work in Excel

# 04. Excel Tables and Structured References

**File:** `04.Excel Tables and Structured References.xlsx`

## Concepts Covered

- Excel Tables
- Structured References
- Table Column References
- SUM Function with Structured References
- AVERAGE Function with Structured References
- SUMIF Function with Structured References
- COUNTIF Function with Structured References
- AVERAGEIF Function with Structured References
- Calculated Columns
- Dynamic Ranges
- Hospital Data Analysis
- Department-Wise Analysis
- Doctor-Wise Analysis
- Total Treatment Cost
- Insurance Payment Analysis
- Patient Stay Analysis
- Dynamic Summary Reports

---

## 1. Dataset

This exercise uses a hospital dataset containing patient admission information, treatment costs, insurance payments, and patient status.

### Dataset Columns

- Patient ID
- Admission Date
- Patient Name
- Department
- Doctor
- Age
- Treatment Cost (₹)
- Insurance Cover
- Insurance Paid (₹)
- Out of Pocket (₹)
- Stay Days
- Status

### Dataset Screenshot

![Dataset Screenshot](Images/Screenshot%202026-10-09%20142608.png)

---

## 2. Excel Tables

Excel Tables organize data into a structured format, making it easier to manage, sort, filter, and analyze records.

### Concepts Covered

- Creating Excel Tables using `Ctrl + T`
- Using table headers
- Organizing hospital records
- Applying filters to table columns
- Referencing table columns
- Working with structured datasets

### Excel Tables Screenshot

![Excel Tables Screenshot](Images/Screenshot%202026-10-09%20142621.png)

---

## 3. Structured References

**Structured references** allow Excel formulas to refer to table names and column names instead of ordinary cell addresses.

### Exercises

- Calculate the total treatment cost.
- Calculate the total insurance amount paid.
- Calculate the average patient age.
- Calculate total treatment costs for the Cardiology department.
- Count patients in the Orthopedics department.

### Formulas Covered

**1. Total Treatment Cost**

```excel
=SUM(Table5[Treatment Cost (₹)])
```

**2. Total Insurance Paid**

```excel
=SUM(Table5[Insurance Paid (₹)])
```

**3. Average Patient Age**

```excel
=AVERAGE(Table5[Age])
```

**4. Cardiology Total Treatment Cost**

```excel
=SUMIF(Table5[Department],"Cardiology",Table5[Treatment Cost (₹)])
```

**5. Orthopedics Patient Count**

```excel
=COUNTIF(Table5[Department],"Orthopedics")
```

### Structured References Screenshot

![Structured References Screenshot](Images/Screenshot%202026-10-09%20142631.png)

---

## 4. Calculated Columns

**Calculated columns** use formulas to calculate values for each row in an Excel Table. Excel can automatically fill the formula down the entire table column.

### Exercises

- Calculate insurance payments using treatment cost and insurance cover.
- Calculate out-of-pocket expenses.
- Apply formulas to every patient record.
- Summarize treatment costs and insurance payments.

### Concepts Covered

- Using formulas with table columns
- Calculating insurance payments
- Calculating out-of-pocket expenses
- Applying formulas to table rows
- Summarizing calculated values

### Calculated Columns Screenshot

![Calculated Columns Screenshot](Images/Screenshot%202026-10-09%20142638.png)

---

## 5. Dynamic Ranges

This exercise demonstrates how Excel Tables and structured references can be used to build flexible hospital summary reports that automatically accommodate new records added to the table.

### Summary Report Columns

- Department
- Doctor
- Patient Count
- Total Treatment Cost (₹)
- Average Stay (Days)

### Exercises

- Count patients handled by a specific doctor.
- Calculate total treatment costs by department.
- Calculate the average length of patient stays.
- Compare departments and doctors.
- Create a hospital summary report.
- Test how table-based formulas respond when new records are added.

### Formulas Covered

**1. Patient Count by Doctor**

```excel
=COUNTIF(Table5[Doctor],"Dr. Rao")
```

**2. Total Treatment Cost by Department**

```excel
=SUMIF(Table5[Department],"Orthopedics",Table5[Treatment Cost (₹)])
```

**3. Average Stay by Department**

```excel
=AVERAGEIF(Table5[Department],B9,Table5[Stay Days])
```

**4. Total Hospital Summary**

```excel
=SUM(D9:D16)
```

*Note: Adjust the cell references and table name if your worksheet uses different locations or names.*

### Dynamic Range Screenshot

![Dynamic Range Screenshot](Images/Screenshot%202026-10-09%20142648.png)

---

## 04. Excel Tables and Structured References Summary

| Function / Feature | Purpose |
|---|---|
| Excel Tables | Organize data in a structured format |
| Structured References | Refer to table columns by name |
| SUM | Calculate total values |
| AVERAGE | Calculate average values |
| SUMIF | Sum values that meet a condition |
| COUNTIF | Count records that meet a condition |
| AVERAGEIF | Calculate averages that meet a condition |
| Calculated Columns | Perform calculations using table data |
| Dynamic Ranges | Build flexible summaries using expanding datasets |

---

## Data Analysis Applications

These exercises demonstrate how Excel Tables and Structured References can be applied to practical hospital data analysis.

The analysis covers:

- Summarizing total treatment costs
- Calculating insurance payments
- Analyzing out-of-pocket patient expenses
- Calculating average patient age
- Counting patients by doctor
- Analyzing treatment costs by department
- Calculating average patient stay
- Creating hospital summary reports
- Using structured references in formulas
- Reducing dependence on fixed cell ranges

## Key Takeawayss

Through this practice, I learned how to:

- Convert datasets into Excel Tables.
- Use structured references instead of traditional cell references.
- Apply aggregation and conditional aggregation functions.
- Create calculated columns for row-level calculations.
- Build flexible summary reports.
- Apply Excel features to practical data analysis scenarios.
