Unicorn Companies Data Analysis
==================================

This project provides a comprehensive analysis of a dataset containing information about unicorn companies (privately held startup companies valued at over $1 billion). It leverages Python with `pandas`, `numpy`, and `matplotlib` to perform data cleaning, answer key business questions, and visualize insights.

Project Overview
-------------------

The main goal of this project is to extract meaningful information from the unicorn companies dataset, identify trends, and present the findings in a clear and visually appealing manner.

Features
----------

*   **Data Loading & Preprocessing**: Reads the dataset from a specified URL, handles missing values, and converts data types for accurate analysis.
    
*   **Key Questions Answered**: Provides answers to 10 specific questions about unicorn companies, such as highest valuation, geographical distribution, and financial trends.
    
*   **Visualizations**: Generates various `matplotlib` plots (bar charts, pie charts, scatter plots) to visually represent the analysis results.
    
*   **Organized Output**: Presents findings in a structured format with clear headings, text explanations, and tabular data where appropriate.
    
*   **Pink Themed Visuals**: All generated graphs and visuals are designed with an appealing pink color theme.
    

How to Run the Project
-------------------------

To run this analysis script, follow these steps:

### Prerequisites

Make sure you have Python installed on your system. This project requires the following Python libraries:

*   `pandas`
    
*   `numpy`
    
*   `matplotlib`
    

You can install them using `pip` (or `python -m pip` if `pip` is not directly in your PATH):

    pip install pandas numpy matplotlib
    

or

    python -m pip install pandas numpy matplotlib
    

### Running the Script

1.  **Save the Script**: Copy the Python code from the analysis script (which you have in your local environment) and save it as a `.py` file (e.g., `unicorn_analysis.py`) in a directory of your choice.
    
2.  **Execute from Terminal**: Open your terminal or command prompt, navigate to the directory where you saved `unicorn_analysis.py`, and run the script using your Python interpreter:
    
        python unicorn_analysis.py
        
    
    (If `python` is not in your PATH, use the full path to your Python executable, e.g., `C:/Users/User/AppData/Local/Programs/Python/Python310/python.exe unicorn_analysis.py`)
    
3.  **View Results**: The script will print the analysis results and answers to the questions directly in your terminal. It will also open separate windows for each generated plot. You will need to close each plot window to proceed through the script's execution.
    

Questions Answered
--------------------

The script provides insights into the following aspects of unicorn companies:

1.  **Highest Valuation**: Identifies the company with the highest valuation in the dataset.
    
2.  **Missing 'Founded Year'**: Counts companies without a recorded 'Founded Year'.
    
3.  **No Listed Investors**: Determines the number of companies without any listed investors.
    
4.  **Most Unicorns by Country**: Finds the country with the highest number of unicorn companies.
    
5.  **Founded After 2010**: Counts companies founded after the year 2010.
    
6.  **Average Valuation by Industry**: Calculates the average valuation of unicorn companies per industry.
    
7.  **Top 5 Cities**: Identifies the top 5 cities with the most unicorn companies.
    
8.  **Financial Stage Distribution**: Shows the distribution of companies across different financial stages (or industries, if financial stage data is unavailable).
    
9.  **Most Portfolio Exits**: Lists companies with the highest number of portfolio exits.
    
10.  **Valuation and Total Raised Correlation**: Computes the correlation between a company's 'Valuation ($B)' and 'Total Raised'.
    

Feel free to contribute to this project by suggesting improvements or adding more analyses!
