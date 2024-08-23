# Pandas-Data-Science-Tasks
Set the real world data science tasks using the Python Pandas library.
<br><br>
For ans the question...<br>
What was the best month for sales? How much was earned that month?
<br>
 What city sold the most product?
 <br>
 What time should we display advertisements to maximize likelihood of customer's buying product?
<br>
What products are most often sold together?
<br>
What product sold the most? Why do you think it sold the most?


## Tools and techniques for this project

### **Tools**

1. **Python Libraries**:
   - **Pandas**: For data manipulation and analysis (e.g., reading CSV files, cleaning data, and aggregating results).
   - **NumPy**: For numerical operations and handling arrays.
   - **Matplotlib**: For data visualization (e.g., creating bar charts).

2. **Jupyter Notebook**: For interactive data analysis and visualization in a notebook environment.

3. **CSV Files**: For storing and handling sales data.

### **Techniques**

1. **Data Import**:
   - Merging multiple CSV files into a single DataFrame using `pd.concat()`.
   - Reading and writing CSV files using `pd.read_csv()` and `pd.to_csv()`.

2. **Data Cleaning**:
   - Removing rows with `NaN` values using `dropna()`.
   - Handling text in date columns to clean and convert dates.
   - Converting data types using `pd.to_numeric()`.

3. **Data Transformation**:
   - Creating new columns based on existing data (e.g., extracting month from date, adding city information).
   - Handling string manipulations to extract specific parts of the address.

4. **Data Aggregation and Analysis**:
   - Calculating sales by grouping data and summing up sales values.
   - Identifying the best month for sales and the city with the highest sales.

5. **Data Visualization**:
   - Creating bar charts to visualize sales by month and city using `plt.bar()`.
   - Customizing charts with labels, ticks, and formatting.

6. **Datetime Operations**:
   - Extracting hour and minute from datetime objects for analyzing time-related patterns.
