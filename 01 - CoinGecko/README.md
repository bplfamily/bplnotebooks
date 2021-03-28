The folder contains CoinGecko historical data for all coins from 2013-04-28
(earliest date possible) to 2021-03-28 (without close). To extract the
database, run:

```bash
xz -dk CoinGecko_2013-04-28_2021-03-28.parquet.xz
```

The .parquet file is required for notebooks which read the file at the start.
It is a huge file (0.5GB) so be careful!
