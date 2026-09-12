# EUSTX50 3m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-973_922_rows-blue)](https://getdata.finance/datasets/eustx50) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eustx50)

### -> [**Download the full EUSTX50 dataset on getdata.finance**](https://getdata.finance/datasets/eustx50)

**EUSTX50 3m OHLCV index historical data** — ultra high-quality 3m OHLCV for **EURO STOXX 50**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3m OHLCV** for **EURO STOXX 50** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/eustx50) · **973,922** `3m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `EUSTX50_3m.csv` (36,119 rows, `2026-03-12` -> `2026-09-11`, 3.17 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/eustx50)** — **973,922** `3m` rows (full `1m`: 2,770,438), **11 timeframes**, `2012-08-27` -> `2026-09-11`.

## Download sample

**[EUSTX50_3m.csv](https://github.com/getdata-finance/eustx50-3m-ohlcv-index-historical-data/blob/main/EUSTX50_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/eustx50-3m-ohlcv-index-historical-data/main/EUSTX50_3m.csv)) · [GitHub Releases](https://github.com/getdata-finance/eustx50-3m-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/eustx50-3m-ohlcv-index-historical-data/](https://getdata-finance.github.io/eustx50-3m-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/eustx50](https://getdata.finance/datasets/eustx50)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/eustx50))** |
|---|--:|---|
| Instrument | EURO STOXX 50 · Index | EURO STOXX 50 · Index |
| Timeframes | `3m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3m rows | 36,119 | **973,922** |
| Size | 3.17 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/eustx50) |
| Period | `2026-03-12` -> `2026-09-11` | `2012-08-27` -> `2026-09-11` |
| File | `EUSTX50_3m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/eustx50) |
| Coverage report | — | [EUSTX50 coverage](https://getdata.finance/coverage/eustx50) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/eustx50)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3m` sample · [getdata.finance](https://getdata.finance/datasets/eustx50) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`EUSTX50_3m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-12T07:00:00+00:00 | 5811.88 | 5816.38 | 5762.7 | 5765.22 | 121.952 |
| 2026-03-12T07:03:00+00:00 | 5765.22 | 5766.7 | 5762.7 | 5765.21 | 71 |
| 2026-03-12T07:06:00+00:00 | 5765.21 | 5766.71 | 5761.2 | 5761.72 | 53 |
| 2026-03-12T07:09:00+00:00 | 5761.72 | 5766.72 | 5760.21 | 5765.72 | 68 |
| 2026-03-12T07:12:00+00:00 | 5765.72 | 5766.72 | 5763.2 | 5766.71 | 41 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-11T19:45:00+00:00 | 6318.24 | 6319.26 | 6318.24 | 6319.25 | 61 |
| 2026-09-11T19:48:00+00:00 | 6319.25 | 6320.25 | 6317.25 | 6320.25 | 19 |
| 2026-09-11T19:51:00+00:00 | 6320.25 | 6320.26 | 6319.24 | 6319.26 | 16 |
| 2026-09-11T19:54:00+00:00 | 6319.26 | 6320.26 | 6319.24 | 6319.24 | 6 |
| 2026-09-11T19:57:00+00:00 | 6319.24 | 6322.26 | 6319.24 | 6320.3 | 76 |

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

df = pd.read_csv('EUSTX50_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('EUSTX50_3m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('EUSTX50_3m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3min')
print(pf.stats())
```

## Download full data

The complete **EUSTX50** archive on **[getdata.finance](https://getdata.finance/datasets/eustx50)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **973,922** rows at `3m`, plus all other timeframes in the same ZIP.

**[-> Get the full EUSTX50 dataset on getdata.finance](https://getdata.finance/datasets/eustx50)**

---
*GetData · EUSTX50 3m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/eustx50)*
