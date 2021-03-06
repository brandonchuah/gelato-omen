## Automating Liquidity Withdrawals for Omen.eth Users

This repo contains tests showcasing how liquidity providers on Omen.eth or any other UI that supports the Conditional Token Smart Contracts can automate withdrawing liquidity from `FixedProductMarketMakers` using Gelato & a Gnosis Safe by defining a future time when the withdrawal transactions should be executed. Neither Truffle nor Buidler is used, simply Ethers.js, a Ganache Mainnet fork & Jest.

## Run locally

1. Add `ALCHEMY_ID` to `.env` file

2. Run:

```
nvm install 14.15.1 // or nvm use 14.15.1
yarn
yarn test
```
