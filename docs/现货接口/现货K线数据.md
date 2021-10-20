#### 现货K线数据

+ url： `/public` (GET)

+ 入参

| 参数key      | 参数value       | 备注        |
| :----------- | :-------------- | :---------- |
| command      | returnChartData | 返回K线数据 |
| currencyPair | BTC_USDT        | 合约名称    |
| start        | 1631386560      | 开始时间戳  |
| end          | 1632386549      | 结束时间戳  |
| peroiod      | 14400           | /           |

+ 出参

  ```json
  [
      {
          "date":1631376000, // 时间戳
          "high":"45978.5", // 最高价
          "low":"45297.4", // 最低价
          "open":"45573.0", // 开盘价
          "close":"45370.8", // 收盘价
          "volume":"31438242.004", // 交易量
          "quoteVolume":"1.000", // 交易额
          "weightedAverage":"1.000000" // 均价
      }
  ]
  ```
