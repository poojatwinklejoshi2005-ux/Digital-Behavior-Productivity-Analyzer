Digital Behavior and Productivity Analyzer

1. Project Overview

This project is a Python-based data analysis tool that tracks and analyzes digital app usage behavior. It categorizes user screen time into productive and entertainment activities and provides insights into productivity patterns using data visualization.

2. Objective

The main objective of this project is to:

Analyze daily app usage behavior
Classify usage into productive and entertainment categories
Calculate productivity score based on usage time
Visualize usage patterns for better understanding of digital habits
3. Dataset Description

The dataset is manually created and includes the following fields:
Date: Represents the usage date
App: Name of the application used
Usage_Time(min): Total time spent on each app in minutes
Category: Type of app usage (Productive or Entertainment)

4. Technologies Used
Python
Pandas
NumPy
Matplotlib
OS module

5. Features
Data loading and preprocessing
Missing value handling
Category-wise usage analysis
Daily usage trend analysis
Productivity score calculation
Top used applications analysis
Data visualization using bar, line, and pie charts
CSV report generation

6. Project Workflow
Import required libraries
Create and load dataset
Clean and preprocess data
Perform grouping and analysis
Generate visualizations
Calculate productivity score
Generate insights based on score
Export final report as CSV

7. Key Analysis Performed
Total usage time by category
Daily usage trend
Most used applications
Productivity percentage calculation
Entertainment vs productive time comparison

8. Output Generated

The project generates:

Bar chart for category-wise usage
Line chart for daily usage trend
Pie chart for usage distribution
Printed insights on productivity level
CSV file containing processed data

9. How to Run the Project
Install required libraries:
pip install pandas numpy matplotlib
Run the Python script:
python main.py
Output graphs and report will be generated automatically

10. Future Improvements
Integration with real mobile or system usage data
User-specific login system
Weekly and monthly reports
Web dashboard using Streamlit or Flask
Export reports in PDF format

 Author: Pooja Joshi