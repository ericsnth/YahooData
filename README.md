# YahooData
Extract historical data from a Yahoo Finance into a pandas DataFrame.

# How to Use ?
import the class, then run :

Python 3:
```
df = YahooData.fetch("TSLA", start="2000-01-01", end="2021-12-31")
print(df)
```

Python 2:
```
df = YahooData()
dfs = df.fetch("TSLA", start="2000-01-01", end="2021-12-31")
print(dfs)
```

Hopefully it can be useful, thanks :)
