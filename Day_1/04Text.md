# Microsoft Excel – Text Functions & Data Cleaning

---

## 1. Introduction

- Text functions in Excel are used to **clean, manipulate, and format text data**.  
- Essential for preparing **messy datasets** for analysis.  
- Helps in standardizing data like names, IDs, addresses, and customer records.  

> Example: Removing extra spaces, combining first and last names, or extracting codes from strings.

---

## 2. Cleaning Functions

### 2.1 TRIM
- **Purpose:** Removes extra spaces from text (except single spaces between words).  
- **Syntax:** `=TRIM(A2)`  
- **Example:** `"  Rahul Sharma  "` → `"Rahul Sharma"`  

### 2.2 CLEAN
- **Purpose:** Removes non-printable characters (useful when copying from other applications).  
- **Syntax:** `=CLEAN(A2)`  

---

## 3. Text Case Functions

- **UPPER:** Converts text to uppercase → `=UPPER(A2)` → `"rahul"` → `"RAHUL"`  
- **LOWER:** Converts text to lowercase → `=LOWER(A2)` → `"RAHUL"` → `"rahul"`  
- **PROPER:** Capitalizes first letter of each word → `=PROPER(A2)` → `"rahul sharma"` → `"Rahul Sharma"`  

> Tip: Useful for **standardizing names or addresses** in datasets.

---

## 4. Extracting Text

- **LEFT:** Extracts characters from the start → `=LEFT(A2,5)`  
- **RIGHT:** Extracts characters from the end → `=RIGHT(A2,4)`  
- **MID:** Extracts characters from the middle → `=MID(A2,3,4)`  

> Example: Extracting area code from phone numbers or product codes from IDs.

---

## 5. Text Analysis Functions

- **LEN:** Returns the length of a string → `=LEN(A2)`  
- **FIND / SEARCH:** Locate position of a character or substring → `=FIND("a",A2)`  

> Tip: FIND is **case-sensitive**, SEARCH is **not case-sensitive**.

---

## 6. Text Combining & Replacing

- **CONCAT / TEXTJOIN:** Combine text from multiple cells → `=CONCAT(A2,B2)` or `=TEXTJOIN(" ",TRUE,A2:B2)`  
- **SUBSTITUTE:** Replace specific text → `=SUBSTITUTE(A2,"old","new")`  
- **REPLACE:** Replace part of a text string by position → `=REPLACE(A2,3,5,"XYZ")`  

> Example: Merging first & last names, or cleaning product codes.

---

## 7. Dataset for Practice

| Customer Name       | Customer ID | City        |
|--------------------|------------|------------|
| "  rahul sharma "   | c12345     | delhi      |
| "PRIYA KUMAR"       | C23456     | mumbai     |
| " ankit verma"      | c34567     | kolkata    |
| "SANYA singh "      | C45678     | chennai    |

> Note: Names have **extra spaces** and inconsistent capitalization to practice cleaning.

---

## 8. Exercises

1. Remove extra spaces from **Customer Name** using `TRIM`.  
2. Standardize all names to **Proper Case** using `PROPER`.  
3. Extract the **first 3 letters** of Customer ID using `LEFT`.  
4. Extract the **last 2 letters** of Customer ID using `RIGHT`.  
5. Combine **Customer Name** and **City** into a single column using `CONCAT` or `TEXTJOIN`.  
6. Replace `"delhi"` with `"Delhi"` using `SUBSTITUTE` for consistent city names.  
7. Count the **number of characters** in each Customer Name using `LEN`.  

---

## 9. Hands-on Outcomes

By the end of this session, students will be able to:  
- Clean messy text data using `TRIM` and `CLEAN`  
- Standardize names using `UPPER`, `LOWER`, `PROPER`  
- Extract parts of text using `LEFT`, `RIGHT`, `MID`  
- Combine and replace text efficiently with `CONCAT`, `TEXTJOIN`, `SUBSTITUTE`, `REPLACE`  
- Prepare customer or product data for analysis in Excel  

---
