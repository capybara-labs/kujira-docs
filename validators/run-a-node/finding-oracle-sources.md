# 🔍 Finding Oracle Sources

This guide assumes you're running on Ubuntu 22.04 LTS - the commands will probably work just fine on 20.04 LTS or Debian.

## Sharing of config is not advisable

## Configuring stablecoin price

## Searching for suitable oracle  sources (manual)

## Searching for suitable oracle  sources (automated)

https://github.com/kohola-io/validator-tools/blob/main/bash/get-pairs.sh

```
$ ./get-pairs.sh BNB USD
Osmosis:

OKX:

MEXC:
  BNB_BUSD
  BNB3L_USDT
  BNB_USDT
  BNB_USDC
  BNB3S_USDT

Kraken:

Huobi:
  BNBUSDT

Gate:
  BNB-USD
  BNB3L-USDT
  BNB-USDT
  BNB3S-USDT

Fin:

Coinbase:

Binance.com:
jq: error (at <stdin>:3): Cannot index number with string "symbol"

Binance.us:
  BNBUSD
  BNBUSDT
  BNBBUSD
```
