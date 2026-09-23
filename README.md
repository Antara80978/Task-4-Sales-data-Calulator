# 📊 Sales Data Calculator

## Task 4 — AI & ML Internship

A simple Python-based **Sales Data Calculator** that analyzes a collection of sales values and calculates important statistical measures such as **total sales, average sales, highest sale, and lowest sale**.

---

## 📌 Project Overview

The **Sales Data Calculator** is a beginner-friendly Python project designed to demonstrate basic numerical data analysis.

The project uses a manually created list of sales values and Python's built-in functions to calculate important sales statistics.

This project helps understand how Python can be used to process numerical data and generate meaningful insights.

---

## 🎯 Objective

The main objectives of this project are:

- Create and store sales data using a Python list.
- Calculate the total sales.
- Calculate the average sales.
- Identify the highest sale.
- Identify the lowest sale.
- Understand basic numerical data analysis using Python.

---

## 🛠️ Technologies Used

- **Python**
- **Jupyter Notebook**

### Python Functions Used

- `sum()`
- `max()`
- `min()`
- `len()`

---

## 📊 Dataset

The project uses manually created sales data:

```python
sales = [1200, 2500, 1800, 3200, 2100, 1500, 2800, 3500, 1700, 2300]
```

The dataset contains **10 sales transactions**.

---

## 🧮 Calculations

### 1. Total Sales

The `sum()` function is used to calculate the total value of all sales.

```python
total_sales = sum(sales)
```

**Result:**

```text
22600
```

---

### 2. Average Sales

The average is calculated using the total sales divided by the number of sales.

```python
average_sales = total_sales / len(sales)
```

**Result:**

```text
2260.0
```

---

### 3. Highest Sale

The `max()` function identifies the highest sales value.

```python
highest_sale = max(sales)
```

**Result:**

```text
3500
```

---

### 4. Lowest Sale

The `min()` function identifies the lowest sales value.

```python
lowest_sale = min(sales)
```

**Result:**

```text
1200
```

---

## 📈 Results

| Metric | Result |
|---|---:|
| Number of Sales | 10 |
| Total Sales | 22,600 |
| Average Sales | 2,260 |
| Highest Sale | 3,500 |
| Lowest Sale | 1,200 |

---

## 🔍 Result Interpretation

The dataset contains **10 sales transactions** with a total sales value of **22,600**.

The average sale is **2,260**. The highest recorded sale is **3,500**, while the lowest recorded sale is **1,200**.

These calculations provide a basic overview of the sales data and demonstrate how Python can be used to quickly analyze numerical information.

---

## 💡 Key Learnings

Through this project, I learned:

- How to store numerical data using Python lists.
- How to use built-in Python functions for data analysis.
- How to calculate total and average values.
- How to identify minimum and maximum values.
- How basic programming can be applied to real-world data analysis.
- How to present analytical results in a structured format.

---

## 🚀 Future Improvements

The project can be extended by:

- Adding sales data from CSV or Excel files.
- Using **Pandas** for larger datasets.
- Adding data visualization using **Matplotlib**.
- Calculating median and standard deviation.
- Creating monthly or yearly sales reports.
- Building an interactive sales dashboard.
- Adding graphical representations of sales trends.

---

## 📁 Project Structure

```text
Sales-Data-Calculator/
│
├── Sales_Data_Calculator.ipynb
├── README.md
└── Project_Report.docx
```

---

## 👩‍💻 Author

**Antara Sarvade**

AI & ML Internship — Task 4

---

## 📜 License

This project was created for **educational and internship purposes**.
