# META 1m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_109_222_rows-blue)](https://getdata.finance/datasets/meta) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/meta)

### -> [**Download the full META dataset on getdata.finance**](https://getdata.finance/datasets/meta)

**META 1m OHLCV stocks historical data** — ultra high-quality 1m OHLCV for **Meta Platforms**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1m OHLCV** for **Meta Platforms** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/meta) · **1,109,222** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `META_1m.csv` (55,440 rows, `2026-02-06` -> `2026-09-01`, 5.48 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/meta)** — **1,109,222** `1m` rows (full `1m`: 636,459), **11 timeframes**, `2012-05-18` -> `2026-09-01`.

## Download sample

**[META_1m.csv](https://github.com/getdata-finance/meta-1m-ohlcv-stocks-historical-data/blob/main/META_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/meta-1m-ohlcv-stocks-historical-data/main/META_1m.csv)) · [GitHub Releases](https://github.com/getdata-finance/meta-1m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/meta-1m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/meta-1m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/meta](https://getdata.finance/datasets/meta)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/meta))** |
|---|--:|---|
| Instrument | Meta Platforms · US stocks | Meta Platforms · US stocks |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **1,109,222** |
| Size | 5.48 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/meta) |
| Period | `2026-02-06` -> `2026-09-01` | `2012-05-18` -> `2026-09-01` |
| File | `META_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/meta) |
| Coverage report | — | [META coverage](https://getdata.finance/coverage/meta) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/meta)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1m` sample · [getdata.finance](https://getdata.finance/datasets/meta) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`META_1m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-06T20:00:00+00:00 | 650.98 | 650.99 | 650.41 | 650.63 | 122 |
| 2026-02-06T20:01:00+00:00 | 650.63 | 651.22 | 650.61 | 650.75 | 74 |
| 2026-02-06T20:02:00+00:00 | 650.75 | 651.15 | 650.61 | 651.15 | 75 |
| 2026-02-06T20:03:00+00:00 | 651.15 | 651.78 | 650.98 | 651.42 | 87 |
| 2026-02-06T20:04:00+00:00 | 651.42 | 651.48 | 651.25 | 651.27 | 71 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-01T19:55:00+00:00 | 585.51 | 585.51 | 583.33 | 583.55 | 176 |
| 2026-09-01T19:56:00+00:00 | 583.55 | 583.78 | 583.06 | 583.18 | 152 |
| 2026-09-01T19:57:00+00:00 | 583.18 | 584.12 | 583.17 | 583.97 | 141 |
| 2026-09-01T19:58:00+00:00 | 583.97 | 584.36 | 583.4 | 584.36 | 179 |
| 2026-09-01T19:59:00+00:00 | 584.36 | 585.16 | 583.25 | 584.43 | 265 |

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

df = pd.read_csv('META_1m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('META_1m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('META_1m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **META** archive on **[getdata.finance](https://getdata.finance/datasets/meta)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **1,109,222** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full META dataset on getdata.finance](https://getdata.finance/datasets/meta)**

---
*GetData · META 1m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/meta)*
