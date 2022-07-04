# Machine Learning | Mercado Libre
Analysis of the company's financial and user data in clever ways to make the company grow

---

## Summary

This project is a financial analysis made for the e-commerce site Mercado Libre, made with Jupyter Notebook and that contains:
* Visual depictions of seasonality (as measured by Google Search traffic) that are of interest to the company.
* An evaluation of how the company’s stock price correlates to its Google Search traffic.
* A Prophet forecast model that can predict hourly user search traffic.
* Answers to questions about the financial analysis.
* A plot of a forecast for the company’s future revenue. 

---
## Installation and Usage

```sh
git clone https://github.com/diegoalcocer/ml-mercado-libre.git
cd ml-mercado-libre/
```
To start the Jupyther Notebook you could launch the jupyter lab:

```sh
jupyter lab
```
For the forecast we use Prophet. To install it you can follow the instructions in this [link to prophet](https://facebook.github.io/prophet/docs/installation.html). If you use **Anaconda** you can type the following command:
```sh
conda install -c conda-forge prophet
```

### 📚 resources/

This project uses the following resources required for analysis 

* google_hourly_search_trends.csv:  [jun-1-2016 to Sept-8-2020] Mercado Libre's hourly search trends from Google
* mercado_daily_revenue.csv: [jan-01-2019 to may-14-2020] Mercado Libre's Daily Revenue
* mercado_stock_price.csv: [jan-02-2015 to jul-31-2020] Mercado Libre's stock price (close)

---

## License

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
