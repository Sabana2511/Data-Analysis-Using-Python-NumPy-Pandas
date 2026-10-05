# Data Analysis Using Python, NumPy & Pandas

## 📌 Project Overview

This project is focusing on fundamental data analysis techniques using **Python, NumPy, and Pandas**.

The project covers numerical computations with NumPy and structured data manipulation, exploration, filtering, and aggregation using Pandas.

---

## 🎯 Objectives

* Work with NumPy arrays for numerical computations.
* Perform array indexing and slicing.
* Convert temperature values from Celsius to Fahrenheit.
* Calculate maximum, minimum, and mean temperatures.
* Create and manipulate Pandas Series.
* Understand `loc` and `iloc` indexing.
* Apply Boolean filtering.
* Create and explore Pandas DataFrames.
* Perform grouping and aggregation.
* Modify, add, and remove DataFrame records and columns.

---

## 🛠️ Technologies Used

* **Python**
* **NumPy**
* **Pandas**
* **Google Colab**

---

## 📂 Project Structure

```text
Python-DA Project/
│
├── Python_DA_Project.ipynb
├── README.md
└── Documentation/
    └── Project_Documentation.pdf
```

---

## 📊 Dataset 1 – Temperature Analysis

The first part of the project analyzes daily average temperatures for two weeks.

### Week 1

```text
[22.5, 25.3, 20.8, 23.4, 26.1, 24.8, 21.9]
```

### Week 2

```text
[19.2, 22.5, 21.3, 24.0, 23.5, 22.8, 20.1]
```

### Operations Performed

* Created 1D and 2D NumPy arrays.
* Inspected array shape, data type, and number of elements.
* Converted Celsius temperatures to Fahrenheit.
* Calculated:

  * Maximum temperature
  * Minimum temperature
  * Mean temperature
* Performed array indexing and slicing.
* Extracted:

  * First three days
  * Weekend temperatures
  * Middle three days
  * Individual weekly temperatures

---

## 📈 Dataset 2 – Student Marks

A Pandas Series was created using student marks and custom rank labels.

| Rank  | Mark |
| ----- | ---: |
| Rank1 |   95 |
| Rank2 |   92 |
| Rank3 |   89 |
| Rank4 |   85 |
| Rank5 |   80 |

### Operations Performed

* Created a Pandas Series.
* Accessed values using integer positions.
* Used `loc` for label-based selection.
* Used `iloc` for position-based selection.
* Filtered students with marks greater than 90.
* Updated Rank1's mark from 95 to 100.
* Removed Rank5.
* Calculated CGPA by dividing marks by 10.

---

## 💰 Dataset 3 – Transaction Analysis

The transaction dataset contains:

* Transaction ID
* Product Category
* Region
* Amount

### Product Categories

* Electronics
* Clothing
* Furniture

### Regions

* North
* South
* East
* West

### Data Analysis Performed

* Displayed the complete DataFrame.
* Examined the first and last records.
* Checked DataFrame shape and data types.
* Selected specific columns.
* Retrieved the last three columns using `iloc`.
* Filtered transactions based on region and amount.
* Calculated product category frequency.
* Identified unique regions.
* Calculated average transaction amount by region.

---

## 🔧 Data Manipulation

The following DataFrame operations were performed:

1. Updated Transaction ID `102` amount from `150` to `165`.
2. Added a `Discount` column representing 10% of the transaction amount.
3. Removed Transaction ID `109`.
4. Deleted the `Discount` column.

---

## 📌 Key Findings

* **Electronics** had the highest number of transactions.
* The **East region** had the highest average transaction amount.
* The **West region** had the lowest average transaction amount.
* NumPy provided efficient numerical operations on temperature data.
* Pandas simplified data filtering, indexing, grouping, and manipulation.

### Temperature Analysis

* Week 1 average temperature: **23.54°C**
* Maximum temperature: **26.1°C**
* Minimum temperature: **20.8°C**
* Temperature range: **5.3°C**
* Week 1 average in Fahrenheit: **74.37°F**

### Transaction Analysis

* Total transactions: **10**
* Total transaction amount: **₹2,780**
* Average transaction amount: **₹278**
* Highest transaction amount: **₹450**
* Lowest transaction amount: **₹150**
* Electronics transactions: **4 (40%)**
* Clothing transactions: **3 (30%)**
* Furniture transactions: **3 (30%)**
* Highest regional average: **East – ₹375**
* Lowest regional average: **West – ₹190**

---

## 🧠 Key Concepts Learned

### NumPy

```text
Array Creation
Array Properties
Indexing
Slicing
Mathematical Operations
Statistical Functions
1D and 2D Arrays
```

### Pandas

```text
Series
DataFrame
loc
iloc
Boolean Filtering
GroupBy
Aggregation
Value Counts
Unique Values
Data Manipulation
```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone <your-repository-url>
```

### 2. Navigate to the project directory

```bash
cd Python_DA_Project
```

### 3. Install required libraries

```bash
pip install numpy pandas
```

### 4. Run the Notebook

Open:

```text
Python_DA_Project.ipynb
```

using **Jupyter Notebook**, **JupyterLab**, or **Google Colab**.

---

## 👩‍💻 Author

**Sabana Asmi R**

**Data Analyst | SQL | Power BI | Python | Excel**

---

## 📚 Learning Outcome

This project strengthened my foundational knowledge of **Python-based data analytics** and provided hands-on experience with **NumPy and Pandas**, which are essential tools for data cleaning, analysis, and preparation for visualization and business intelligence.
