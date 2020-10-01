# DefiGold Exchange

[![Tests](https://github.com/Uniswap/uniswap-interface/workflows/Tests/badge.svg)](https://github.com/Uniswap/uniswap-interface/actions?query=workflow%3ATests)
[![Styled With Prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://prettier.io/)

This is a fork of the open source interface for Uniswap -- a protocol for decentralized exchange of Ethereum tokens.
This code will change as we migrate from the Ethereum network to FantasyGold Core. 



## DefiGold Interface

To access the DefiGold Interface visit [app.fantasygold.io](https://app.fantasygold.io). 

## Listing a token

Please see the
[@fantasygold/default-token-list](https://github.com/fantasygold/default-token-list)
repository.

## Development

### Install Dependencies

```bash
yarn
```

### Run

```bash
yarn start
```

### Configuring the environment (optional)

To have the interface default to a different network when a wallet is not connected:

1. Make a copy of `.env` named `.env.local`
2. Change `REACT_APP_NETWORK_ID` to `"{YOUR_NETWORK_ID}"`
3. Change `REACT_APP_NETWORK_URL` to e.g. `"https://{YOUR_NETWORK_ID}.infura.io/v3/{YOUR_INFURA_KEY}"`

Note that the interface only works on testnets where both
[DefiGold LP Token](https://uniswap.org/docs/v2/smart-contracts/factory/) and
[multicall](https://github.com/makerdao/multicall) are deployed.
The interface will not work on other networks.

## Contributions

**Please open all pull requests against the `master` branch.**
CI checks will run against all PRs.


