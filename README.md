# Stuff I Learn About Advanced Excel for Reference

This repository contains my **personal notes and practice files on Excel**.
Each section includes the **Excel file name and a screenshot of the output for quick reference**.

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

The exercise calculates the total product sales by multiplying the corresponding **Price** and **Quantity** values.

### Screenshot

![Array Multiplication](https://github.com/Ankitmahato-0509/Advanced-Excel/blob/main/Images/Screenshot%202026-09-05%20183409.png?raw=true)


## Revenue Calculations

This exercise demonstrates how **SUMPRODUCT** can be used to calculate revenue from sales data.

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

The analysis includes:

- Calculating total product sales
- Calculating total revenue
- Calculating product-specific revenue
- Analyzing sales by salesperson
- Analyzing sales by country
- Applying multiple conditions
- Performing conditional calculations

# Stuff I Learn About Advanced Excel for Reference

This repository contains my **personal notes and practice files on Advanced Excel**.  
Each section includes the **Excel file name and a screenshot of the output for quick reference**.

# 02. Advanced XLOOKUP & XMATCH

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

The **XMATCH function** is used to find the relative position of a value within a range or array.

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

**XLOOKUP** can be combined with multiple conditions to retrieve a value when more than one criterion must be satisfied.

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

**Reverse XLOOKUP** is used to search from the **last occurrence to the first occurrence**.

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

# XLOOKUP & XMATCH Summary

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

## Key Learning

**XLOOKUP** and **XMATCH** are powerful modern Excel functions for performing flexible and dynamic lookups.

By combining these functions with **multiple criteria, wildcard matching, and reverse searching**, complex lookup requirements can be handled efficiently in Excel.

# 03. Dynamic Array Functions

**File:** `03.Dynamic Array Functions.xlsx`

### Concepts Covered

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

## Dataset

The exercises use a **One Piece Characters dataset** containing information about characters.

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

The dataset is used throughout the exercises to demonstrate how Dynamic Array Functions can automatically return multiple results.

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

![FILTER Function](https://github.com/Ankitmahato-0509/Advanced-Excel/blob/main/Images/Screenshot%202026-09-05%20183409.png?raw=true)

---

# SORT Function

The **SORT function** is used to dynamically sort a dataset based on a selected column.

### Exercise

Sort the dataset based on **Bounty**, from:

**Highest → Lowest**

### Concepts Covered

* Sorting data dynamically
* Sorting based on a specific column
* Descending order
* Returning the complete sorted dataset
* Dynamic array sorting

### Example

The dataset is sorted using the **Bounty_M** column in descending order.

### Screenshot

![SORT Function](https://github.com/Ankitmahato-0509/Advanced-Excel/blob/main/Images/Screenshot%202026-09-05%20183431.png?raw=true)

---

# SORTBY Function

The **SORTBY function** is used to sort one array based on the values in another array.

### Exercise

Sort the dataset based on **Age**, from:

**Highest → Lowest**

### Concepts Covered

* Sorting using another range
* Sorting by Age
* Descending order
* Dynamic sorting
* Sorting an entire dataset based on a selected column

### Example

The dataset is dynamically sorted using the **Age** column.

### Screenshot

![SORTBY Function](https://github.com/Ankitmahato-0509/Advanced-Excel/blob/main/Images/Screenshot%202026-09-05%20183420.png?raw=true)

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

![UNIQUE Function](https://github.com/Ankitmahato-0509/Advanced-Excel/blob/main/Images/Screenshot%202026-09-05%20183420.png?raw=true)

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

![SEQUENCE Function](https://github.com/Ankitmahato-0509/Advanced-Excel/blob/main/Images/Screenshot%202026-09-05%20183420.png?raw=true)

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

The exercise first filters the dataset to find members of the:

`Straw Hat Pirates`

The filtered results are then sorted based on **Bounty**.

### Screenshot

![Combining Dynamic Array Functions](https://github.com/Ankitmahato-0509/Advanced-Excel/blob/main/Images/Screenshot%202026-09-05%20183431.png?raw=true)

---

# Dynamic Array Functions Summary

| Function               | Purpose                                      |
| ---------------------- | -------------------------------------------- |
| **FILTER**             | Returns data that meets specified conditions |
| **SORT**               | Sorts an array based on a selected column    |
| **SORTBY**             | Sorts an array based on another range        |
| **UNIQUE**             | Returns unique values from a range           |
| **SEQUENCE**           | Generates a sequence of numbers              |
| **Combined Functions** | Performs advanced dynamic data analysis      |

---

# Data Analysis

This exercise demonstrates how Dynamic Array Functions can make Excel analysis more efficient and flexible.

The analysis includes:

* Filtering characters based on affiliation
* Sorting characters by bounty
* Sorting characters by age
* Extracting unique affiliations
* Generating automatic sequence numbers
* Creating dynamic filtered reports
* Combining FILTER and SORT
* Working with automatically expanding results
* Reducing the need for helper columns

## Key Learning

Dynamic Array Functions allow Excel formulas to **return multiple results automatically** and make those results **spill into adjacent cells**.

These functions are especially useful for:

* Data cleaning
* Data analysis
* Dynamic reports
* Dashboard preparation
* Creating automated lists
* Sorting and filtering large datasets
* Reducing manual work in Excel

