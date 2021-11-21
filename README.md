# Truffle Pet Shop Tutorial

This repo contains a working example (11/20/2021) of the "Pet Shop" tutorial for [Truffle Suite](https://www.trufflesuite.com/tutorial).

Follow along with the linked instructions or use the **TL;DR** below.

1. `npm i -g truffle`
2. clone this repo or start from scratch:
  - `mkdir pet-shop-tutorial && cd pet-shop-tutorial`
  - `truffle unbox pet-shop`
3. Install [ganache-cli](https://www.npmjs.com/package/ganache-cli)
  - `npm i -g ganache-cli`
4. Start Ganache (local blockchain instance)
  - `ganache-cli -p 7545 --clientId 1337`
  - Copy the "seed phrase" generated by Ganache to a scratchpad
    - (it should output in the terminal)
5. Install [MetaMask](https://metamask.io/)
  - Import the seed phrase
  - Select "Localhost: 7545" as your network from the dropdown
6. `truffle migrate`
7. `npm run dev`
