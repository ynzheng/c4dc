[![CircleCI](https://circleci.com/gh/kemargrant/c4dc/tree/master.svg?style=svg)](https://circleci.com/gh/kemargrant/c4dc/tree/master)
# Description

C4DC is a web client to interact with [C4D](https://github.com/kemargrant/c4d)

A live version can be found at [http://arbitrage.0trust.us](http://arbitrage.0trust.us)
 
## Installation
```
git clone https://github.com/kemargrant/c4dc
cd c4dc
npm install
npm run start
```


## Configuration
The 'Settings' tab controls  connection to the bot

| Name | Value | Type
| ------ | ------ | ------ |
| Private Key | Private key of C4D (Config.key in C4D's config.json) | String
| Host | IP Address of C4D | String
| Port | Port number of C4D (Config.port in C4D's config.json) | Number
| Connect | Connect to running C4D instanc | Switch
| AutoConnect | Automatically connect to running C4D instance | Switch
| AutoSave | Save settings and data in local storage | Switch
| Reset Settings | Clear settings and data saved in local storage | Switch
| Polling Rate | Update polling rate (seconds) of C4D bot | Number
| Swing Polling Rate | Update swing polling rate (seconds) of C4D bot | Number
| Sane Trades | Perform arbitrage when the percentage deviation is between the upper and lower limits | Switch
| Liquid Trades | Perform arbitrage when order book has liquidity | Switch
| Swing Trade | Vibrate with the frequency of the market | Switch
| Lower Limit | Lowest acceptable percentage (if sane Trades is active) | Number
| Upper Limit | Highest acceptable percentage (if sane Trades is active) | Number
| Swing Percentage | Percentage Deviation between buy/sell orders | Number


## Disclaimer

- C4DC is not guaranteed to make you money
- Do not invest more than you can afford to lose
- Do not use this C4DC if you do not understand cryptocurrency or triangular arbitrage

License
----
GPLv3


Donate
------
BTC:1656ASaUDzMbiQHf32YUNU2E3QWKGPdFEL

ETH:0x30CE6E295D5c204b9C77C6DE995260735B8Ba8bC
