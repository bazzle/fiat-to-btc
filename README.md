# Fiat to BTC

## About

Calls the blockchain.com API once a week to create a history of Fiat currency to BTC exchange rates.

## What this does currently

1. Pulls BTC/various fiat currency exchange rates from [external API](https://www.blockchain.com/explorer/api/exchange_rates_api)
2. Github action to pull data each week at Sunday 00:05 UTC.
3. On each run, saves into `snapshots.json`
