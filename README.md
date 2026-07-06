# XAUUSD 16h OHLCV Metals Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-7_444_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full XAUUSD dataset on ork.ad**](https://ork.ad/)

**XAUUSD 16h OHLCV Precious metals historical data** — ultra high-quality 16h OHLCV for **Gold / US Dollar**. Near-continuous precious-metals liquidity across global sessions. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 16h OHLCV** for **Gold / US Dollar** (Precious metals)
- **Near-continuous precious-metals liquidity across global sessions**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`16h`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **7,444** `16h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `16h` sample updated in sync

> **Sample on GitHub** · `XAUUSD_16h.csv` (328 rows, `2025-10-03` → `2026-07-03`). **Full archive on [ork.ad](https://ork.ad/)** — **7,444** `16h` rows (~0.43 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2009-02-24` → `2026-07-03`.

## Download sample

**[XAUUSD_16h.csv](https://github.com/ork-ad/xauusd-16h-ohlcv-metals-historical-data/blob/main/XAUUSD_16h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/xauusd-16h-ohlcv-metals-historical-data/main/XAUUSD_16h.csv)) · [GitHub Releases](https://github.com/ork-ad/xauusd-16h-ohlcv-metals-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/xauusd-16h-ohlcv-metals-historical-data/](https://ork-ad.github.io/xauusd-16h-ohlcv-metals-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Gold / US Dollar · Precious metals | Gold / US Dollar · Precious metals |
| Timeframes | `16h` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 16h rows | 328 | **7,444** |
| Size | 0.02 MB | ~0.43 MB |
| Period | `2025-10-03` → `2026-07-03` | `2009-02-24` → `2026-07-03` |
| File | `XAUUSD_16h.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`16h` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `16h` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `16h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`XAUUSD_16h.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2025-10-03T16:00:00Z | 3882.14 | 3889.64 | 3880.0 | 3885.17 | 80265.0 |
| 2025-10-05T16:00:00Z | 3885.17 | 3949.9 | 3884.08 | 3942.7 | 339163.0 |
| 2025-10-06T08:00:00Z | 3942.7 | 3977.79 | 3926.78 | 3958.47 | 641018.0 |
| 2025-10-07T00:00:00Z | 3958.47 | 3991.38 | 3941.22 | 3981.16 | 731781.0 |
| 2025-10-07T16:00:00Z | 3981.16 | 4049.92 | 3974.42 | 4049.51 | 411683.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-06-30T16:00:00Z | 4031.05 | 4034.16 | 3960.3 | 3984.77 | 434737.0 |
| 2026-07-01T08:00:00Z | 3984.77 | 4116.35 | 3981.5 | 4050.47 | 689133.0 |
| 2026-07-02T00:00:00Z | 4050.47 | 4144.0 | 4041.52 | 4107.13 | 861422.0 |
| 2026-07-02T16:00:00Z | 4107.13 | 4195.76 | 4106.28 | 4172.28 | 459166.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('XAUUSD_16h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('XAUUSD_16h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('XAUUSD_16h.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='16h')
print(pf.stats())
```

## Download full data

The complete **XAUUSD** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **7,444** rows at `16h`, plus all other timeframes in the same ZIP.

**[→ Get the full XAUUSD dataset on ork.ad](https://ork.ad/)**

---
*GetData · XAUUSD 16h OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-06 UTC*