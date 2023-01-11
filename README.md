# Mod5-Financial-Planning

This is a python script that includes two financial analysis tools.
1. A tool to visualize current savings and then determine if you have enough reserves for an emergency fund. 
2. A tool to forecast the performance of a retirement portfolio in 30 years and 10 years with different weights.
The script uses the Alpaca SDK to import pricing data.
---

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://github.com/pandas-dev/pandas) - For access to Pandas series and dataframes.

* [pathlib](https://github.com/budlight/pathlib) - To load csv files

* [json](https://www.json.org/json-en.html) - To retreive data from a website.

* [%matplotlib inline](https://github.com/matplotlib/matplotlib) - For plotting charts.

* [MCForecastTools](Documentation included in local file) - For running Monte Carlo Simulations.

* [alpaca_trade_api](https://github.com/alpacahq/alpaca-trade-api-python) - For running Alpaka SDK API

* [os](https://docs.python.org/3/library/os.htmln) - For using os.getenv to hide API keys.
---

## Installation Guide

Before running the application first install the following dependencies.

```python
import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation

%matplotlib inline
```

---

## Usage

To use the finacial_planning_tools script simply clone the repository and financial_planning_tools.ipynb

```python
financial_planning_tools.ipynb
```



---

## Contributors

Mike Blanchette

---

## License

When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. Use this section to include the license you want to use.
