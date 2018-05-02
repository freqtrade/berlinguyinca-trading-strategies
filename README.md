# freqtrade-trading-strategies
contains strategies for using freqtrade. Please be aware they are supposed to show off some of the indicators and concepts you can use with freqtrade and might not be great for investing purposes. So please use them on your own risk.

If you really like them, or think I lost enough money testing them, please feel free to shoot me a donation in btc at:

1AoyvVpGSg9TatyCNZbTgkQveFHZXssutW


## Backtesting Results

Simple:

2018-05-01 21:37:18,094 - freqtrade.optimize.backtesting - INFO - Measuring data from 2018-04-12T04:40:00+00:00 up to 2018-05-02T04:30:00+00:00 (19 days)..

==================================== BACKTESTING REPORT ====================================
pair        buy count    avg profit %    total profit BTC    avg duration    profit    loss
--------  -----------  --------------  ------------------  --------------  --------  ------
BTC_ETH            13            1.16          0.00150821           600.0        13       0
BTC_LTC             2            1.24          0.00024830           685.0         2       0
BTC_ETC             2            1.26          0.00025439           515.0         2       0
BTC_POWR            3            2.94          0.00091145           433.3         3       0
BTC_XMR             2            1.37          0.00027446           357.5         2       0
TOTAL              22            1.44          0.00319681           555.2        22       0

  "max_open_trades": 1,
  "stake_currency": "BTC",
  "stake_amount": 0.01,

  "experimental": {
    "use_sell_signal": true,
    "sell_profit_only": true
  },
