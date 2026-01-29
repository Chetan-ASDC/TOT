# Excel Lookup Functions Practice

## Dataset

| EmpID | Name   | Department | Salary | Joining Date | Location   |
|-------|--------|------------|--------|--------------|------------|
| E101  | Rahul  | IT         | 50000  | 01-01-2024   | Delhi      |
| E102  | Priya  | HR         | 45000  | 15-02-2024   | Mumbai     |
| E103  | Ankit  | Finance    | 55000  | 20-03-2024   | Bangalore  |
| E104  | Neha   | IT         | 60000  | 10-04-2024   | Pune       |
| E105  | Ramesh | Marketing  | 48000  | 25-05-2024   | Chennai    |
| E106  | Sanya  | HR         | 47000  | 05-06-2024   | Delhi      |

---

## **VLOOKUP Tasks**

1. **Find Salary by EmpID**  
   Find the **Salary** of employee with EmpID `E104` using `VLOOKUP`.

2. **Find Department by Name**  
   Find the **Department** of employee `Sanya` using `VLOOKUP`.

3. **Find Location by EmpID**  
   Retrieve the **Location** of employee with EmpID `E103` using `VLOOKUP`.

4. **Handle Missing EmpID**  
   If an EmpID is not in the dataset (e.g., `E110`), return `"Not Found"` using `VLOOKUP` with `IFERROR`.

---

## **HLOOKUP Tasks**

> *Tip: To use HLOOKUP, you may need to copy the dataset horizontally with headers in the first row.*

5. **Department in 3rd row**  
   Using `HLOOKUP`, find the **Department** of the employee in the **3rd row**.

6. **Salary in 5th row**  
   Retrieve the **Salary** of the employee in the **5th row** using `HLOOKUP`.

7. **Joining Date by Name**  
   Using `HLOOKUP`, find the **Joining Date** of the employee named `Priya`.  
   *(Hint: Consider using `MATCH` to find the correct column first.)*

---

## **XLOOKUP Tasks**

8. **Salary by Name**  
   Find the **Salary** of employee `Ankit` using `XLOOKUP`.

9. **Location by EmpID**  
   Retrieve the **Location** of EmpID `E105` using `XLOOKUP`.

10. **Handle Missing EmpID**  
    If the **EmpID** entered in a cell (e.g., `G1`) is not in the dataset, return `"Employee Not Found"` using `XLOOKUP`.

---

