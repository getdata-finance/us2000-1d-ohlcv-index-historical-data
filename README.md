# US2000 1d OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_445_rows-blue)](https://getdata.finance/datasets/us2000) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/us2000)

### -> [**Download the full US2000 dataset on getdata.finance**](https://getdata.finance/datasets/us2000)

**US2000 1d OHLCV index historical data** — ultra high-quality 1d OHLCV for **Russell 2000**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1d OHLCV** for **Russell 2000** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1d`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/us2000) · **2,445** `1d` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1d` sample updated in sync

> **Sample on GitHub** · `US2000_1d.csv` (732 rows, `2024-05-06` -> `2026-09-11`, 56.70 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/us2000)** — **2,445** `1d` rows (full `1m`: 2,717,412), **11 timeframes**, `2018-10-26` -> `2026-09-11`.

## Download sample

**[US2000_1d.csv](https://github.com/getdata-finance/us2000-1d-ohlcv-index-historical-data/blob/main/US2000_1d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/us2000-1d-ohlcv-index-historical-data/main/US2000_1d.csv)) · [GitHub Releases](https://github.com/getdata-finance/us2000-1d-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/us2000-1d-ohlcv-index-historical-data/](https://getdata-finance.github.io/us2000-1d-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/us2000](https://getdata.finance/datasets/us2000)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/us2000))** |
|---|--:|---|
| Instrument | Russell 2000 · Index | Russell 2000 · Index |
| Timeframes | `1d` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1d rows | 732 | **2,445** |
| Size | 56.70 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/us2000) |
| Period | `2024-05-06` -> `2026-09-11` | `2018-10-26` -> `2026-09-11` |
| File | `US2000_1d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/us2000) |
| Coverage report | — | [US2000 coverage](https://getdata.finance/coverage/us2000) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/us2000)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1d` sample · [getdata.finance](https://getdata.finance/datasets/us2000) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`US2000_1d.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-05-06T00:00:00+00:00 | 2039.32 | 2065.61 | 2037.56 | 2062.18 | 73045 |
| 2024-05-07T00:00:00+00:00 | 2062.18 | 2078.84 | 2059.38 | 2063.31 | 70930 |
| 2024-05-08T00:00:00+00:00 | 2063.31 | 2064.81 | 2042.19 | 2053.19 | 74618 |
| 2024-05-09T00:00:00+00:00 | 2053.19 | 2077.55 | 2044.84 | 2076.55 | 79873 |
| 2024-05-10T00:00:00+00:00 | 2076.55 | 2086.96 | 2052.45 | 2056.76 | 81560.04948 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-07T00:00:00+00:00 | 2973.06 | 2975.53 | 2963.32 | 2967.55 | 57545 |
| 2026-09-08T00:00:00+00:00 | 2967.55 | 2976 | 2952.79 | 2960.31 | 201886 |
| 2026-09-09T00:00:00+00:00 | 2960.31 | 2964.45 | 2917.69 | 2921.91 | 178501 |
| 2026-09-10T00:00:00+00:00 | 2921.91 | 2932.01 | 2885.88 | 2886.36 | 225068 |
| 2026-09-11T00:00:00+00:00 | 2886.36 | 2928.03 | 2886.17 | 2903.87 | 271220 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('US2000_1d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('US2000_1d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('US2000_1d.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1d')
print(pf.stats())
```

## Download full data

The complete **US2000** archive on **[getdata.finance](https://getdata.finance/datasets/us2000)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **2,445** rows at `1d`, plus all other timeframes in the same ZIP.

**[-> Get the full US2000 dataset on getdata.finance](https://getdata.finance/datasets/us2000)**

---
*GetData · US2000 1d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/us2000)*
