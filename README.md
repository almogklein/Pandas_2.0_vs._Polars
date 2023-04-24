# Pandas_2.0_vs._Polars
Pandas and Polars Data Manipulation Benchmarking
This repository contains code for benchmarking the performance of Pandas and Polars libraries for data manipulation. The code is written in Python and executed in a Jupyter Notebook.

Requirements
To run the code, you need to have the following libraries installed:

Pandas
Polars
Matplotlib
Usage
To use the code, simply open the Jupyter Notebook pandas-polars-benchmarking.ipynb and run the cells.

The Notebook contains two main sections: Syntax Comparison and Performance Comparison.

Syntax Comparison
The Syntax Comparison section compares the syntax of Pandas and Polars for various data manipulation operations. The following operations are covered:

Creating a DataFrame
Saving and Reading a DataFrame
Sorting a DataFrame
Filtering a DataFrame
Grouping a DataFrame
Each operation is performed using both Pandas and Polars, and the syntax for both libraries is compared. The code for each operation is in separate cells, and the output is displayed below the code.

Performance Comparison
The Performance Comparison section compares the performance of Pandas and Polars for the same data manipulation operations as in the Syntax Comparison section. The code for each operation is executed using both libraries, and the time taken to execute each operation is recorded.

After all the operations are executed, a graph is displayed showing the time taken for each operation using both libraries. The x-axis shows the different operations we performed, and the y-axis shows the time taken in seconds. The blue bars represent the runtimes for Pandas, while the orange bars represent the runtimes for Polars.
