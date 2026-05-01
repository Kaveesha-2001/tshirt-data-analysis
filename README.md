# T-Shirt Inventory & Data Analysis Project

This project focuses on generating synthetic data for a T-shirt inventory system and performing various data visualizations to understand stock distribution, pricing, and color intensity.

## 📌 Project Overview
The project is divided into three main phases:
1.  **Data Generation:** Using Python's `random` and `string` libraries to create a dataset of 1,000 T-shirts.
2.  **Data Wrangling:** Organizing data using `Pandas` DataFrames and grouping stock by size.
3.  **Visualization:** Using `Matplotlib` and `Seaborn` to create:
    *   **Pie Charts:** Total stock distribution.
    *   **Grouped/Stacked Bar Charts:** Comparing stock by color intensity (Dark vs Light).
    *   **Box Plots:** Price distribution and outliers.
    *   **Pair Plots:** Visualizing relationships in the Iris dataset (as a bonus analysis).

## 📊 Visualizations Included

### 1. Stock Distribution by Size
A Pie Chart representing how the total inventory is distributed across different sizes (S, M, L, XL, XXL).

### 2. Stacked Bar Chart
A visualization showing the total stock for each size, stacked by color intensity (Dark vs Light). This helps in understanding the total inventory volume at a glance.

### 3. Price Distribution Box Plot
A statistical representation of T-shirt prices categorized by color density, showing the median price and any potential outliers.

## 🛠️ Technologies Used
*   **Python 3**
*   **Pandas:** For data manipulation and tabular structures.
*   **NumPy:** For numerical operations and random data generation.
*   **Matplotlib:** For core plotting and charts.
*   **Seaborn:** For advanced statistical visualizations.

## 🚀 How to Run the Code
1.  Ensure you have Python installed.
2.  Install the required libraries:
    
```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  Run the script:
    ```bash
    python your_script_name.py
    
```

## 📝 Key Functions
*   `generate_random_id()`: Creates a unique ID (e.g., 452B).
*   `generate_random_size()`: Assigns sizes based on specific probability weights.
*   `generate_random_price()`: Generates a random price up to 10,000.
*   `generate_random_stock()`: Assigns a random stock count between 12 and 2345.

---
Developed as a Data Analysis exercise.
```

---

### **මෙය භාවිතා කරන ආකාරය:**
1.  ඔයාගේ පරිගණකයේ අලුත් **Text Document** එකක් හදන්න.
2.  ඉහත ඇති code එක ඒකට paste කරන්න.
3.  File එක save කරන විට නම විදියට **`README.md`** යොදන්න.
4.  ඊටපස්සේ කලින් මම කියලා දුන්න විදියට `git add README.md`, `git commit`, සහ `git push` කරන්න.

GitHub එකේ ඔයාගේ repository එකට කවුරුහරි ආවම මුලින්ම පේන්නේ මේ ලස්සන විස්තරයයි!
```
