# ETF - Passive Income Analysis - Module 7
This repo seeks the objective of building a financial database and web application by using SQL, Python, and the Voilà library to analyze the performance of a hypothetical fintech ETF.

---

## Technologies

Required programs, libraries, systems, and overall dependencies:

Python (version 3.0 or later)
<br>
`Pathlib`
<br>
`pandas`
<br>
`%matplotlib`
<br>
`hvplot.pandas`
<br>
`sqlalchemy`
<br>
`numpy`
---

## Installation Guide

`pip install Voila`

conda install -c pyviz hvplot geoviews

---

## Usage

SQL Queries

```python
query2 = """
SELECT time, daily_returns
FROM PYPL
ORDER BY daily_returns DESC
LIMIT 10;
"""

# Using the query, read the data from the database into a Pandas DataFrame
pypl_top_10_returns = pd.read_sql_query(query2, con=engine)

# Review the resulting DataFrame

pypl_top_10_returns
```

---

## Contributors

Reginald Hyppolite
https://www.linkedin.com/in/reginald-hyppolite-nyc/

BIG THANKS to all the great TAs and Professor Vinicio DeSola

---

## License

N/A -- Free open.ware for a better world.