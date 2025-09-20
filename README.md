# Fiat to BTC

## About

Calls the blockchain.com API once a week to create a history of Fiat currency to BTC exchange rates.  
To be used on [Satoshi Power](https://satoshi-power.com/)

## What this does currently

1. Pulls BTC/various fiat currency exchange rates from [external API](https://blockchain.info/ticker)
2. Github action to pull data each week at Sunday 10:00 UTC
3. On each run, saves fresh data into `snapshots.json` and triggers redeploy