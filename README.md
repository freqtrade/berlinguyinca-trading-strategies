# freqtrade-trading-strategies
contains strategies for using freqtrade. Please be aware they are supposed to show off some of the indicators and concepts you can use with freqtrade and might not be great for investing purposes. So please use them on your own risk.

If you really like them, or think I lost enough money testing them, please feel free to shoot me a donation in btc at:

1AoyvVpGSg9TatyCNZbTgkQveFHZXssutW


## Backtesting Results

### Simple:

2018-05-01 21:37:18,094 - freqtrade.optimize.backtesting - INFO - Measuring data from 2018-04-12T04:40:00+00:00 up to 2018-05-02T04:30:00+00:00 (19 days)..

```
==================================== BACKTESTING REPORT ====================================
pair        buy count    avg profit %    total profit BTC    avg duration    profit    loss
--------  -----------  --------------  ------------------  --------------  --------  ------
BTC_ETH            13            1.16          0.00150821           600.0        13       0
BTC_LTC             2            1.24          0.00024830           685.0         2       0
BTC_ETC             2            1.26          0.00025439           515.0         2       0
BTC_POWR            3            2.94          0.00091145           433.3         3       0
BTC_XMR             2            1.37          0.00027446           357.5         2       0
TOTAL              22            1.44          0.00319681           555.2        22       0

```

``` javascript
  "max_open_trades": 1,
  "stake_currency": "BTC",
  "stake_amount": 0.01,

  "experimental": {
    "use_sell_signal": true,
    "sell_profit_only": true
  }
```

#### Total Profit: ~31% in 19 days

### Quickie:

```
2018-05-01 21:41:24,313 - freqtrade.optimize.backtesting - INFO - Measuring data from 2018-04-12T04:40:00+00:00 up to 2018-05-02T04:35:00+00:00 (19 days)..
2018-05-01 21:41:24,927 - freqtrade.optimize.backtesting - INFO -
==================================== BACKTESTING REPORT ====================================
pair        buy count    avg profit %    total profit BTC    avg duration    profit    loss
--------  -----------  --------------  ------------------  --------------  --------  ------
BTC_ETH            17            0.64          0.00109456           510.3        17       0
BTC_LTC             7            0.68          0.00048056           489.3         7       0
BTC_ETC             4            0.99          0.00039919           187.5         4       0
BTC_DASH            4            0.92          0.00037095           178.8         4       0
BTC_ZEC             3            0.72          0.00021597           278.3         3       0
BTC_XLM             2            0.89          0.00017956           350.0         2       0
BTC_NXT             4            0.83          0.00033445           160.0         4       0
BTC_POWR            4            1.54          0.00062234           250.0         4       0
BTC_ADA             5            0.75          0.00037910           641.0         5       0
BTC_XMR             3            0.71          0.00021304           483.3         3       0
TOTAL              53            0.81          0.00428972           403.7        53       0

```

``` javascript
  "max_open_trades": 1,
  "stake_currency": "BTC",
  "stake_amount": 0.01,

  "experimental": {
    "use_sell_signal": true,
    "sell_profit_only": true
  }
```

#### Total Profit: ~42% in 19 days
