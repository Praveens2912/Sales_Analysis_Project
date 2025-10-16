# 🛒 Sales Analysis Project

<br>

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![pandas](https://img.shields.io/badge/pandas-Data%20Analysis-yellow?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Seaborn](https://img.shields.io/badge/Seaborn-Insights-blueviolet)
![PyArrow](https://img.shields.io/badge/PyArrow-Feather%20Files-lightgrey)
<br>
![Sales](https://github.com/user-attachments/assets/c6c799a7-abb3-47d9-b07f-3a6cadc8dd75)

##  Project Overview
This project analyzes sales data to uncover meaningful insights that can help improve business performance.  
The dataset was stored in **Feather format** for efficient reading and writing.  
Using Python and visualization libraries, the project answers six key business questions related to monthly sales trends, city performance, and product popularity.

---

##  Business Questions Solved

### 1. How to read Feather data?
Demonstrated how to import `.feather` files using **pandas** and **pyarrow** for faster I/O operations.  
```python
import pandas as pd
all_data = pd.read_feather(r"C:\Users\sprav\Downloads\4..+Sales+Analysis/Sales_data.ftr")
```
<br>

### 2. Which is the best month for sales?

Calculated monthly revenue and identified the month with the highest total sales, helping to understand seasonal sales patterns.
<br>
<br>

 **Visualization: Monthly Sales Trend**
 <br>

![Monthly Sales Chart](https://github.com/user-attachments/assets/e70df5e7-b388-4d43-884e-0b0739354d69)

<br>

### 3. Which city has the maximum number of orders?

Analyzed city-wise order counts to find which city generated the most sales.
<br>
<br>

**Visualization: Orders by City**
<br>

<img width="627" height="491" alt="Screenshot 2025-10-16 131725" src="https://github.com/user-attachments/assets/389e185e-b02b-4884-84ee-194733e65851" />\
<br>

### 4. What product sold the most and why?

Examined the top-selling products and explored possible reasons such as price range, promotions, and customer demand.
<br>
<br>

**Visualization: Product Sales vs. Average Price**
<br>

<img width="825" height="715" alt="image" src="https://github.com/user-attachments/assets/2faca844-b5d2-48a0-844a-1641378775f1" />

<br>

### 5. Understanding trend of the most sold products

Visualized sales trends of popular products using Matplotlib and Seaborn to identify growth and demand patterns.
<br>
<br>

**Visualization: Monthly Sales Trend of Top Products**

<br>

<img width="870" height="663" alt="image" src="https://github.com/user-attachments/assets/4e5ee3d9-e668-4f32-b6b3-c8d612c5e956" />

<br>


### 6. What products are most often sold together?

Performed a combination analysis to find items frequently purchased together, useful for cross-selling strategies.
<br>
<br>

**Visualization: Frequently Bought Together Products**
<br>

<img width="1050" height="505" alt="image" src="https://github.com/user-attachments/assets/84044211-05cd-43a3-ad84-76916fdbd968" />


<br>

##  Tools & Libraries Used

- Python

- pandas – data cleaning and analysis

- NumPy – numerical operations

- Matplotlib / Seaborn – data visualization

- PyArrow – Feather file reading and writing


<br>

##  Key Insights

- December had the highest total sales, likely due to holiday shopping.

- San Francisco recorded the maximum number of orders.

- MacBook Pro Laptop was the most sold product, indicating high-end customer demand.

- iPhone and Lightning Cable were frequently bought together, suggesting strong product bundling potential.




<br>

## Conclusion

This project demonstrates how to extract insights from raw sales data using Python.<br>
By identifying best-performing months, cities, and products, businesses can better plan inventory, promotions, and pricing strategies.



<br>
Developed By

 Praveen S<br>
 Chennai, India<br>
 GitHub Profile - https://github.com/Praveens2912<br>
 Portfolio - https://praveens2912.github.io/My_Portfolio/
