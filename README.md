STOCK-DATA
=================

### 数据收集

[https://github.com/juxuny/statistics]

每天一个压缩包，16:00更新

周六日一般是不会有数据的，如果有请忽略吧

### 数据说明

```
.
  \
   |-- index
   |     \
   |      |-- s_sh000001.csv
   |      |-- s_sz399001.csv
   |-- sh600000.csv
   |-- sh600001.csv
   |-- ...
   |-- ...
```

解压之后得到一堆csv文件，每个文件以股票代码命名，`sh600000.csv`, 其中sh是新浪数据库里的前缀

| 字段 | 描述 |
|--|--|
|date|日期|
|time|日间|
|current_price|当前价|
|open_price|今天开盘价|
|yesterday_price|昨天收盘价|
|max|今天最大|
|min|今天最小|
|buy_price_1|买一价|
|buy_price_2||
|buy_price_3||
|buy_price_4||
|buy_price_5||
|buy_1|买一量|
|buy_2||
|buy_3||
|buy_4||
|buy_5||
|sell_price_1|卖一价|
|sell_price_2||
|sell_price_3||
|sell_price_4||
|sell_price_5||
|sell_1|卖一量|
|sell_2||
|sell_3||
|sell_4||
|sell_5||
|deal|成交总量|
|deal_price|成交总额|
