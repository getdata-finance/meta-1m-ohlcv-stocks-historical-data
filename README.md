# META 1m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-637_227_rows-blue)](https://getdata.finance/datasets/meta) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/meta)

### -> [**Download the full META dataset on getdata.finance**](https://getdata.finance/datasets/meta)

**META 1m OHLCV stocks historical data** — ultra high-quality 1m OHLCV for **Meta Platforms**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **Meta Platforms** (US stocks)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/meta) · **637,227** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `META_1m.csv` (55,440 rows, `2026-02-06` -> `2026-09-01`). **Full archive on [getdata.finance](https://getdata.finance/datasets/meta)** — **637,227** `1m` rows, **11 timeframes**, `2020-02-25` -> `2026-09-01`.

## Download sample

**[META_1m.csv](https://github.com/getdata-finance/meta-1m-ohlcv-stocks-historical-data/blob/main/META_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/meta-1m-ohlcv-stocks-historical-data/main/META_1m.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/meta))** |
|---|--:|---|
| Instrument | Meta Platforms · US stocks | Meta Platforms · US stocks |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **637,227** |
| Period | `2026-02-06` -> `2026-09-01` | `2020-02-25` -> `2026-09-01` |
| File | `META_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/meta) |
| Coverage report | — | [META coverage](https://getdata.finance/coverage/meta) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/meta)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`META_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-06T20:00:00+00:00 | 650.98 | 650.99 | 650.41 | 650.63 | 122 |
| 2026-02-06T20:01:00+00:00 | 650.63 | 651.22 | 650.61 | 650.75 | 74 |
| 2026-02-06T20:02:00+00:00 | 650.75 | 651.15 | 650.61 | 651.15 | 75 |
| 2026-02-06T20:03:00+00:00 | 651.15 | 651.78 | 650.98 | 651.42 | 87 |
| 2026-02-06T20:04:00+00:00 | 651.42 | 651.48 | 651.25 | 651.27 | 71 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-01T19:55:00+00:00 | 585.51 | 585.51 | 583.33 | 583.55 | 176 |
| 2026-09-01T19:56:00+00:00 | 583.55 | 583.78 | 583.06 | 583.18 | 152 |
| 2026-09-01T19:57:00+00:00 | 583.18 | 584.12 | 583.17 | 583.97 | 141 |
| 2026-09-01T19:58:00+00:00 | 583.97 | 584.36 | 583.4 | 584.36 | 179 |
| 2026-09-01T19:59:00+00:00 | 584.36 | 585.16 | 583.25 | 584.43 | 265 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Download full data

Full META archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full META dataset on getdata.finance](https://getdata.finance/datasets/meta)**
