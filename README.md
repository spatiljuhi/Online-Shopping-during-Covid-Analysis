# Online Shopping Data Generator and Analysis

This project involves generating simulated online shopping data using Python and xlsxwriter library. The generated data is then analyzed using Pandas, Matplotlib, and Seaborn for insights into online shopping patterns, expenditures, and trends.

## Code Overview

The provided code generates synthetic online shopping data in an Excel file (`OnlineShopping.xlsx`) and subsequently reads and analyzes the data using Pandas and visualization libraries.

### Code Structure

- Data Generation: The code uses xlsxwriter to create an Excel workbook with 100 rows of simulated online shopping data.
- Data Analysis: After generating the data, the code reads the Excel file using Pandas and performs various analyses and visualizations to extract insights.

### Libraries Used
- `xlsxwriter` - for creating Excel files.
- `Pandas` - for data manipulation and analysis.
- `Matplotlib` and `Seaborn` - for data visualization.

## Usage

### Data Generation
- The code generates synthetic online shopping data in an Excel file named `OnlineShopping.xlsx`.

### Data Analysis
- Reads the generated data from `OnlineShopping.xlsx` using Pandas.
- Cleans null values within the dataset.
- Analyzes total expenditure, tax charged, and patterns in online shopping behavior.
- Visualizes the data using various plots (bar charts, pie charts, line plots) to represent yearly spending, website-wise expenditure, category-wise purchases, etc.

### Code Files
- `OnlineShoppingDataAnalysis.py`: Reads the generated data and performs analysis and visualizations.

## Getting Started

### Prerequisites
- Python (version 3.7.9)
- Libraries: xlsxwriter, Pandas, Matplotlib, Seaborn

### Installation
1. Clone this repository.
2. Install the required dependencies using `pip install -r requirements.txt`.

### Running the Code
1. Run `OnlineShoppingDataAnalysis.py` to perform data analysis and visualize insights.

## Results

The analysis provides insights into yearly spending trends, website-wise expenditures, category-wise purchases, and tax implications. Visualizations offer a clear representation of online shopping behavior and patterns.

## Contributing

Contributions and suggestions for enhancements are welcome! Feel free to submit pull requests or issues for improvements or additional analyses.
