# Fiat to BTC

## About

Calls the blockchain.com API once a week to create a historical record of fiat currencies to BTC exchange rates.  
To be used on [Satoshi Power](https://satoshi-power.com/)

## What this does currently

1. Pulls BTC/various fiat currency exchange rates from [external API](https://blockchain.info/ticker)
2. Github action to pull data each week on sunday 10:00 UTC
3. On each run, saves fresh data into `snapshots.json` and triggers redeploy