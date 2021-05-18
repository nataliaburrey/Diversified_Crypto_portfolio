[
<img width="845" alt="Screen Shot 2021-05-18 at 9 50 41 AM" src="https://user-images.githubusercontent.com/80833988/118692111-96680200-b7be-11eb-8a31-a39556f521b6.png">
](url)

> "Diversification is a protection against ignorance. It can be achieved by combining assets that move in the opposite direction, which means those assets react to the same economic event differently.
"


# Diversified portfolio analyzer


:star: Cryptocurrency and index funds.


In this Project, we assumed the role of a quantitative analyst for a FinTech investing platform. This platform aims to offer clients a one-stop online investment solution for their portfolio.

[
<img width="595" alt="Screen Shot 2021-05-18 at 10 22 37 AM" src="https://user-images.githubusercontent.com/80833988/118696288-ff517900-b7c2-11eb-944d-50b5ca93cc94.png">
](url)



## Table of content




## An executive summary

*  A portfolio analyzer: Create a framework can be used in the future to create a  Diversified Portfolio can be tune in for any goal and risk-tolerance
* Put into practice our new skills we learned: collect, clean and analyze complex financial data and how to use APIs to access a wide range of high-quality, up-to-date data in real time. 
* Using Python and Pandas libraries compares the performance of different assets. Include calculations, tables, financial models and interactive visualizations. Also include information about past  performance of the portfolios, as well as suggestions for portfolio composition to insure moderate risk/return profile.

[
<img width="601" alt="Screen Shot 2021-05-18 at 10 28 47 AM" src="https://user-images.githubusercontent.com/80833988/118697206-e72e2980-b7c3-11eb-86c7-bb9ba63a7125.png">
](url)



###  Overview of the project and project goals.

* We’re been tasked with evaluating various  investment options  for inclusion in the client portfolios. Need to determine the options with most investment potential based on key risk-management metrics: the daily returns, standard deviations, Sharpe ratios.
* To keep the costs low, the firm uses algorithms to build each client's portfolio. The algorithms choose from various investment styles and options.
* Our solution is for unexperienced investor-somebody with low risk tolerance, Interested in cryptocurrency but would like to chose the ones with higher returns to create a riskier part of portfolio with higher returns to take advantage of emerging market
* On one hand, our customer does not have a time to individually pick the stock-so we chose 3 most popular indexes, which will introduce diversify to a  customers portfolio in allow user to have moderate returns with lower risk as user plans for retirement 

[
<img width="446" alt="Screen Shot 2021-05-18 at 10 38 59 AM" src="https://user-images.githubusercontent.com/80833988/118698527-5f491f00-b7c5-11eb-8970-157d7b6fe5eb.png">
](url)

* On the other hand, following the hype of emerging crypto market, our investor would like to take  an advantage of fabulous returns. For this reason we decided to introduce moderate risk into the portfolio, by picking one of the most known and established cryptocurrencies on the market: Bitcoin (BTC), Ethereum (ETH), Litecoin (LTC) and Ripple (XRP) to balance out low-risk low-return index portion


### What special about out project?


[
<img width="1188" alt="Screen Shot 2021-05-18 at 10 43 02 AM" src="https://user-images.githubusercontent.com/80833988/118699057-f1e9be00-b7c5-11eb-8767-eccf1652c50b.png">
](url)


* Very well  commented code with deeply analyses and explained results for technical user lacking an understanding
* Reading financial data and making the connection between code results and meaning of it for the user unexperienced in financial tools and lanscrape



## Software version control

### Libraries / interfaces
*  Pandas - is a software library designed for data analytics that makes it easier to work with data from practically any type of file. Pandas supplies powerful tools for working with time data in particular, and time is a key aspect of financial analysis. Analysts typically compare and measure financial assets—from single stocks to large portfolios—across time.
* With the combination of Pandas and Jupyter Notebook, you can efficiently import, prepare, and analyze data of any type or quantity.
* Following libraries were used to analyze the data

```
# Import the required libraries and dependencies
import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from pathlib import Path
import numpy as np
import matplotlib.pyplot as plt
import hvplot.pandas
import seaborn as sns
%matplotlib inline

```
    
### Work with GitHub
* Repository created on GitHub
* Our group made sure that files  were frequently committed to repository
* Our repository is organized, and includes Resources folder with CSV  project files, 
* Jupyter Notebook with code well commented with concise, relevant notes.
* Detailed explanation of each step with explanation of financial data and conclusions of analyses (example)

### How to install

* Save remote repo from GitHub to your computer (Desktop): in Terninal type:

```
cd desktop

git clone https://github.com/nataliaburrey/SQL_Financial_Application.git
```

now you can find repo on your desktop


* Open a Jupyter Lab: In Terminal type command

```
jupyter lab
```

* In Jupyter Lab access saved repo folder 
* Choose [ etf_analyzer.ipynb ] file to see the analysis report.



## How to use Voila

Following screenshots and videos of the web application, created by deploying your Jupyter notebook via the Voilà library

To deploy Voilà library via terminal type in code:


```
conda activate dev
cd <relative-path-to-notebook>
voila <notebook_name>

```
The file will be opened into default WEB browser

## Work with data

### Data Collection

* We used various skills learned in a bootcamp and various sources of date to collect information: data collected from CSV files, APIs, or databases by using Python or a Python library
* WEB sites 
* CSV files and functions -Import data from a CSV file into a Pandas DataFrame.
* API calls (web site, code example)
* Alpaca Api calls (create a .env file -explanation how to create)
* Describe the source of your data and why you chose it for your project. === 	•	Import data from a CSV file into a Pandas DataFrame.

### Cleanup & Analyse

* We identified and cleaned up missing, incomplete, erroneous, and duplicated text values in the dataset
* Generate summary statistics and visualizations to help you better understand the DataFrame
* Reorganized  subsets of information within the DataFrame to do a targeted analysis
* Write Python code to capture the price differences across the cryptocurrency market.


### Data visualization 
* The next step was to dive a bit more deeply into that data through visualizations.
* Some sets of data to analyses use a simple plot function, but for others included longer time period and overlaying data we included interactive visualizations to explore and uncover relationships and patterns in your data
* We will be able to present information to our client using Voila 



## License

MIT

## Links

* [Resourses](https://github.com/nataliaburrey/project_1/tree/main/Resources)
* [Jupyter Lab](https://github.com/nataliaburrey/project_1/blob/main/project_1.ipynb)
* [Repository copy link](https://github.com/nataliaburrey/project_1.git)

