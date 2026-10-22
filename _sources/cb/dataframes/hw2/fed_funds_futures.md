# Dataframe: `hw2:fed_funds_futures` - 30-Day Fed Funds Futures

Daily 30-Day Fed Funds futures (ZQ) OHLCV bars retrieved from Databento's CME Globex feed. Each contract settles at 100 minus the calendar-day average effective federal funds rate for its delivery month. The dataset includes outright monthly contracts and calendar spreads; filter to outright contracts for FedWatch calculations.


## DataFrame Glimpse

```
Rows: 11737
Columns: 7
$ date   <datetime[ns]> 2026-10-21 00:00:00
$ symbol          <str> 'ZQF7'
$ open            <f64> 95.85
$ high            <f64> 95.855
$ low             <f64> 95.845
$ close           <f64> 95.85
$ volume          <u64> 24348


```

## Dataframe Manifest

| Dataframe Name                 | 30-Day Fed Funds Futures                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [fed_funds_futures](../dataframes/hw2/fed_funds_futures.md)                                       |
| Sources                        | CME Globex                                          |
| Providers                      | Databento                                        |
| Provider Links                 | https://databento.com/                                   |
| Tags                           | Futures, Monetary Policy, Fedwatch                                             |
| Access Types                   |                                       |
| How is data pulled?            | Databento Historical API via Python                                                   |
| Data available up to (min)     | 2026-10-21 00:00:00                                                             |
| Data available up to (max)     | 2026-10-21 00:00:00                                                             |
| Dataframe Path                 | /Users/ivychan/finm-328/hw2-ivyxchan27/_data/fed_funds_futures.parquet                                             |


**Linked Charts:**


- [hw2:fedwatch_latest_forecast](../../charts/hw2.fedwatch_latest_forecast.md)



## Pipeline Manifest

| Pipeline Name                   | HW 2: The Yield Curve and the Policy Path                       |
|---------------------------------|--------------------------------------------------------|
| Pipeline ID                     | [hw2](../../../index.md)              |
| Maintainer                      | Jeremiah Bejarano               |
| Contributors                    | Jeremiah Bejarano |
| Repository                     | https://github.com/hw-finm-32800/hw2                  |
| Pipeline Web Page               | <a href="file:///Users/ivychan/finm-328/hw2-ivyxchan27/docs/index.html">Pipeline Web Page      |
| Date of Last Code Update        | 2026-10-22 16:18:27           |
| OS Compatibility                | Windows, Linux, macOS |
| Linked Dataframes               |  [hw2:crsp_treasury_consolidated](../../dataframes/hw2/crsp_treasury_consolidated.md)<br>  [hw2:fed_yield_curve](../../dataframes/hw2/fed_yield_curve.md)<br>  [hw2:fed_funds_futures](../../dataframes/hw2/fed_funds_futures.md)<br>  |


**Build Commands:**
```
doit

```

