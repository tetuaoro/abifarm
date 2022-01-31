# Abifarm
_Find the best path to make an arbitrage strategy_

## Environment

`node v14.17`

## Install dependencies

```
yarn install
```

## Run script

```
yarn start
```

## How works

The bot uses minimum of 100 BUSD on binance to make an arbitrage. It uses every 100 BUSD free. If you have 1000 BUSD, it will be able to use 10 times of 100 BUSD.

## Requirements

You need an **api key** a **secret key** from your binance account : [create](https://www.binance.com/fr/my/settings/api-management). Enable only trading Spot. Once you get your keys, copy paste keys into the file `sample-env` and rename the file into `.env`. Let's gets some money.
