# polymarket data download

One-click access to high-frequency historical Polymarket data.

## usage

l2 data:
```python
df = pd.read_parquet(
    "https://s.wangshuox.com/poly_l2/btc-updown-5m-1775174400.parquet",
    storage_options={
        "User-Agent": "Mozilla/5.0"
    }
)
```
polygon trades download:
```
https://s.wangshuox.com/polygon_trades/btc-updown-5m-1775174400.parquet 
```

## Available since

| market | available since |
| --- | --- |
|  5m market | `2026-02-13 17:00:00` -> `btc-5m`；`2026-02-22 03:55:00` -> `eth-5m`、`sol-5m`、`xrp-5m` |
| 15m, 1h, 4h, 1d | `2026-01-26 08:00:00` |
| musk | `elon-musk-of-tweets-february-12-february-14` |
