# Data Challenge
This repo is intended for the 2019-2020 course Data Challenge 2.

# Data

One can read the data in two manners. The preferred one is by using the (gzipped) Parquet file at `data/transactions.gzip` via (Python):
``` 
import pandas as pd

path = "data/transactions.gzip"
df = pd.read_parquet(path)
```

Alternatively, one can download the csv-data via https://we.tl/t-FksRNp4Cxn. This link will expire on February 5th, 2020. 

The .gzip and .csv contents are equivalent.
