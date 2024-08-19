# Financial Ratios Analysis Application

## Overview

This application calculates and visualizes various financial ratios from given data. It is designed to assist in the analysis of financial health over time, focusing on key metrics like interest coverage, fixed-charge coverage, cash flow coverage, and operating cash flow ratios.

## Features

- **Calculation of Financial Ratios**: Automatically computes multiple financial ratios using historical data.
- **Interactive Web Visualization**: Offers a dynamic web interface to plot the calculated ratios over time, allowing for easy trend analysis and insights.
- **Customizable Data Input**: Users can input their financial data, and the application will process and display corresponding ratios.

## Requirements

- python 3.x
- pandas
- numpy
- dash == 2.17.1
- datetime
- openpyxl>=3.1.3

## Installation

1. Ensure Python 3.x is installed on your system.
2. Install required Python libraries:
   ```bash
   pip install pandas numpy dash datetime openpyxl

## Implementation

To utilize the `ratios_calculator` package effectively, follow these steps to prepare your data and run the analysis:

### Step 1: Data Preparation
Download the required financial documents from FACTSET:
- **Balance Sheet**
- **Income Statement**
- **Stock Price History**

Ensure these files are saved in **Excel [.xlsx]** format.

### Step 2: Install the Package
If you haven't already installed the `ratios_calculator` package, you can do so using pip. Open your command-line interface and run:

```bash
pip install ratios_calculator
```

### Step 3: Usage

After installing and importing the `ratios_calculator` package, you can easily run the analysis using the following command in your Python script or interactive session:

```python
import ratios_calculator
ratios_calculator
```

After the program is run, follow the prompts in the terminal to provide the path to the specified files downloaded in Step 1. 

### Step 4: Output

After processing, the ratios_calculator will automatically save a CSV file **[ratios.csv]** containing the calculated financial ratios to your current working directory. This file can be used for further analysis or reporting.

## License
This project is licensed under the MIT License.
