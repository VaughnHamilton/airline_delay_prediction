# Airline Delay Prediction

## Get the Data

Download your dataset from AWS:

https://da2-airline-forecast.s3.eu-central-1.amazonaws.com/airline_2m.tar.gz

Uncompress it with:

``` bash
  tar -zxvf airline_2m.tar.gz
```

## Load the Data into Pandas

``` bash
df = pd.read_csv('airline_2m.csv', low_memory=False, encoding='iso-8859-1', nrows=1000000)
```

