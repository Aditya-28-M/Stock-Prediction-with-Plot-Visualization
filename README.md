`# Stock-Prediction-with-Plot-Visualization

This Python program provides tools for **stock data exploration, visualization, outlier removal, and simple prediction**.  
It uses **Pandas, NumPy, Matplotlib, and Seaborn** to clean and visualize stock market datasets.

---

##  Features

1. **Data Exploration**
   - Print first N rows
   - Print last N rows
   - Dataset info (`shape`, `dtypes`, `info`)
   - Dataset description (summary statistics)

2. **Outlier Removal**
   - Removes outliers using the **IQR (Interquartile Range)** method
   - Iteratively removes outliers until each column (`Open, High, Low, Close, Adj Close, Volume`) has **0 outliers**
   - Shows how many outliers are removed per column

3. **Data Visualization (after outlier removal)**
   - Histogram
   - Boxplot
   - Line plot (`Date` vs any stock column)
   - Pair plot (scatter matrix)
   - Heatmap (correlation between stock columns)

4. **Simple Stock Prediction**
   - Checks if dataset has a `Close` column
   - Predicts **future trend** based on last 5 closing prices
   - Prints **last price, predicted price, and direction ( UP or  DOWN)**

---

## Requirements

The csv file should be in the same folder where the program is saved
 - Install dependencies before running:

```bash
pip install numpy pandas matplotlib seaborn
