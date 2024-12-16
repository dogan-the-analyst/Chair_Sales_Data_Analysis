# Chair Sales Data Analysis
This project is an Excel-based study for practice. The dataset used is `sales_data_analysis_source.xlsx`.

## Overview
The study involves transforming and analyzing sales data using Excel functions and features like **IF**, **VLOOKUP**, and **PivotTable**. Below are the steps and results:

---

## Initial Table State
Here is the raw dataset as it appears initially:  
![Initial Table](https://github.com/user-attachments/assets/81c0d9e2-f1e0-4f03-a1c1-031336669465)

---

## Final Table State
After processing the data, the table looks as follows:  
![Final Table](https://github.com/user-attachments/assets/e949e4df-bb68-4a27-ae76-4b5cfc4b1122)

---

## Applying Discounts
1. **Discount Criteria**:  
   If the quantity is **greater than or equal to 20**, we mark "Y" for a discount, otherwise "N":  
   ![Discount](https://github.com/user-attachments/assets/04c373ca-0f7c-4805-be66-c0b4043e40d6)

2. **Discount Calculation**:  
   If a discount is applied ("Y"), the total amount is multiplied by **0.95**:  
   ![Discount Calculation](https://github.com/user-attachments/assets/a562ce57-e00e-43f6-b242-4e24eaf3e839)

---

## Using Customer Information
The original dataset includes a sheet named `Customer Info`:  
![Customer Info](https://github.com/user-attachments/assets/c3f2ddcd-7bee-435e-b1cf-634f7a702cf2)

- **Company Names**:  
  Using **VLOOKUP**, we retrieve company names:  
  ![VLOOKUP Company](https://github.com/user-attachments/assets/0bfc3b71-acb6-4167-8978-f1ae3ef31f03)

- **Sales Representatives**:  
  Similarly, we retrieve representative names:  
  ![VLOOKUP Reps](https://github.com/user-attachments/assets/7aacdf6a-a907-4439-9cc2-ac3f3069504c)

---

## PivotTable Analysis
Finally, we use **PivotTable** to analyze the data:
1. **Total Sales by Chair Models by Month**:  
   ![Pivot Table - Models](https://github.com/user-attachments/assets/b05fa602-4e1f-4c8b-a0b8-da514441b4d9)

2. **Total Sales by Representatives by Month**:  
   ![Pivot Table - Reps](https://github.com/user-attachments/assets/716b3223-7e91-4da8-92d5-2c7b0dd37a38)

---

## Conclusion
This project demonstrates the use of Excel for data analysis, showcasing various features like formulas and PivotTables to derive meaningful insights from raw data.
