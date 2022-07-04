# Cryptocurrency Arbitrage Notebook
## Description
The Cryptocurrency Arbitrage notebook provides an example of how one can use Jupyter and Python to perform an arbitrage analysis based on historical Bitcoin trade data from two cryptocurrency exchanges, Bitstamp and Coinbase.  

The notebook is divided into the following phases: 

- **Collection** - In this phase, the historical Bitcoin trade data is imported via csv files that are exported from Bitstamp and Coinbase.
- **Preparation** - In this phase, the Bitcoin trade data is cleansed and prepared for analysis.   All missing data is removed, all '$' characters under the 'Close' column are removed, the 'Close' column is converted to float datatype and any duplicate data is removed.  
- **Analysis** - In the last phase, we analyze and calculate arbitrage profits for different periods to see if there are any opportunities for arbitrage.   

## Technologies
This example uses the following technologies: 

- **pathlib** - This library is used to determine the path to the daily_rate_sheet.csv and the path to save the qualifying_loans.csv to. Please see [pathlib documentation](https://docs.python.org/3/library/pathlib.html) for more information.
- **csv** - This library is used to read and write csv files. Please see [csv documentation](https://docs.python.org/3/library/csv.html) for more information.
- **Jupyter** - Jupyter is a web-based interactive development environment for data science and analysis.   Please see Please see [Jupyter documentation](https://jupyter.org/) for more information.
- **pandas** - pandas is a software library written for the Python programming language for data manipulation and analysis.  Please see [pandas documentation](https://pandas.pydata.org/) for more information.

## Installation
The `pathlib` and `csv` libraries are already installed with Python 3.7.

In order to use the Cryptocurrency Arbitrage notebook, you will need to install `Jupyter` and `pandas`. Below are the instructions for installing each required library.

### Installing Jupyter
@TODO 

### Installing pandas
@TODO 

## Usage
### Launching the Cryptocurrency Arbitrage Notebook
@TODO 

### Running the Calculations
@TODO 

## Contributors
This sample application was authored by:

Quinn Wong (quinn.wong@gmail.com)
LinkedIn: https://www.linkedin.com/in/quinnwong/

## License
The MIT License (MIT)

Copyright (c) 2022 Quinn Wong

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
