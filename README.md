# Nifty Returns
This script generates a bubble chart visualizing the relationship between average return and risk (standard deviation) of Nifty returns for different periods. The size of each bubble represents the period.

Requirements
Python 3.x
Pandas
Seaborn
Matplotlib
Usage
Ensure you have the required dependencies installed.
Place your data file named data.csv in the same directory as the script.
Run the script using python script.py.
The bubble chart will be displayed and saved as bubble_chart.png.
Data Format
The CSV file should contain the following columns:

Date: Date of the data point
Period: Numerical value indicating the period
NiftyReturn: Percentage return of Nifty for each period
Script Functionality
Reads data from the CSV file.
Converts the NiftyReturn column to numeric format after removing the '%' sign.
Calculates the average return and standard deviation for each period.
Creates a bubble chart using Seaborn, where:
X-axis represents average return.
Y-axis represents risk (standard deviation).
Size of each bubble represents the period.
Adds title, axis labels, legends, and data labels to enhance interpretation.
Saves the chart as a PNG file named bubble_chart.png.
