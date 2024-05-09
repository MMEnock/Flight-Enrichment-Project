# Light Enrichment and Data Cleaning-Wrangling

This project focuses on the enrichment of flight data. It includes two main Jupyter Notebooks:
1. **Flight Schedule Cleaning.ipynb** - Cleans the flight schedule data and prepares it for enrichment.
2. **Flight_Enrichment_Assignment.ipynb** - Enriches the cleaned flight data by calculating the minimum time difference between existing and potential flight schedules, and by combining routes through various criteria like airline code and leg type.

## Key Features
- **Data Cleaning**: Standardizes and cleans flight schedule data for further processing.
- **Data Enrichment**: Analyzes cleaned data to find optimal scheduling based on minimal time differences and route combinations.
- **Decision Making**: Utilizes complex criteria involving via points, airline codes, and leg types to enhance flight scheduling decisions.

## Libraries Used
This project uses the following Python libraries:
- `datetime` for handling date and time operations.
- `numpy` and `pandas` for data manipulation.
- `dateutil` for robust date operations.
- `autopep8` for code formatting.
- `os` and `re` for operating system interactions and regular expressions.
- `cProfile` for performance profiling.
- `typing` for type hints.

## Installation
Ensure you have Python installed on your system. You can install all required libraries using pip:

```bash
pip install numpy pandas python-dateutil autopep8

