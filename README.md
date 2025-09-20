# Fiat to BTC

## About

Calls the blockchain.com API once a week to create a history of Fiat currency to BTC exchange rates.
Use this to feed [Satoshi Power](https://satoshi-power.com/) with data once a week by appending to a json file.

## What this does currently

1. Pulls BTC/various fiat currency exchange rates from [external API](https://blockchain.info/ticker)
2. Github action to pull data each week at Sunday 00:05 UTC
3. On each run, saves fresh data into `snapshots.json` and triggers redeploy
