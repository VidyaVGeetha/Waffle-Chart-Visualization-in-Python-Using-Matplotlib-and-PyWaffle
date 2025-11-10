# 🧇 Waffle Chart Visualization of Canadian Immigration Data (Matplotlib + PyWaffle)

## 📊 Overview
This project shows how to turn tabular data into a **waffle chart** in Python.

The notebook:
1. Loads the **Canadian Immigration** dataset.
2. Filters a few countries (🇩🇰 Denmark, 🇳🇴 Norway, 🇸🇪 Sweden).
3. Calculates proportions for each country.
4. Builds a waffle chart **manually** with NumPy + Matplotlib.
5. Wraps that logic into a **reusable function** `create_waffle_chart(...)`.
6. Recreates the same visualization using **PyWaffle** (a dedicated waffle-chart library).

This is useful for a **Data Analyst portfolio** because it shows:
- data loading and cleaning,
- proportion calculations,
- a custom plot,
- and the ability to package logic in a function.

---

## 🧰 Tech Stack / Libraries
- `pandas` – load and clean the Canadian immigration data
- `numpy` – do the proportion and tile calculations
- `matplotlib` – draw the manual waffle chart
- `pywaffle` – draw the same chart with less code

---

## 🚀 How to Run

1. **Clone this repo**
   ```bash
   git clone https://github.com/yourusername/python-waffle-chart-canadian-immigration.git
   cd python-waffle-chart-canadian-immigration
   
2.Install the requirements.
 pip install pandas numpy matplotlib pywaffle
 
3.Open the notebook.
jupyter notebook Seaborn.ipynb

4.Run all cells

the first part will load the Canadian immigration data

the middle part will build the waffle chart step by step

the final part will show the function version and the PyWaffle version
_____________________________________________________________

📁 Notebook Structure

Step 1–8: import libraries, read Canada.csv, set Country as index

Step 9–15: filter Denmark, Norway, Sweden and compute proportions

Step 16–21: build the waffle chart manually (matrix, grid, legend)

Step 21: create_waffle_chart(...) – your custom function

Step 23: recreate the same chart with PyWaffle.
__________________________________________________________
💼 Why this project is relevant for Data Analyst jobs

1.Can read real datasets (CSV)

2.Can explain proportions visually

3.Can write reusable functions

4.Can show both low-level Matplotlib and higher-level libraries



