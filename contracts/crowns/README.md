[![N|Solid](https://play.blocklords.io/favicon.png)](https://play.blocklords.io)
# What is *Crowns*?
Crowns is the official currency of Blocklords, the first grand strategy game. See the [lightpaper](https://blocklords.io/lightpaper.pdf).
This repository holds the token source code and token related open sources under *MIT* licence.

Deployed contracts on Mainnet:
- [`0x8c9f6a021039ccbe98451918db6EE629368aD600`](https://rinkeby.etherscan.io/token/0x8c9f6a021039ccbe98451918db6EE629368aD600) &ndash; Crowns (CWS) token.
- [`0xb32efAc4993a3d0e88a271f1AD21736DAEf3bAD2`](https://rinkeby.etherscan.io/address/0x8c9f6a021039ccbe98451918db6EE629368aD600) - Vesting Contract, to lock CWS for a given period of time.

*Crowns (CWS)* could be obtained through purchase on
- [UniSwap](https://uniswap.org), 
- and other exchanges 

or, can be earned within the Blocklords game.

# Crowns (CWS) features

Crowns (CWS) is an erc-20 token on Ethereum mainnet. It's primarely used to purchase within Blocklords. The **unique feature** of ***Crowns*** is that, every recharge within the game is spread accross all token holders as dividends. We call it **rebase**.

### Supply
Crown has a fixed supply. Total of 10,000,000 CWS.
* 10% is going to investors
* 10% is going to team
* ...

# Vesting Contract
Is a simple contract used to lock Crowns for a certain period of time. It's based on OpenZeppelin's TimeLock token.


---

# Technical part
## Online usage
To play with contracts online, you can directly import the gist code on Remix, an online editor.
[Crowns on Remix!](https://remix.ethereum.org/#version=soljson-v0.6.7+commit.b8d736ae.js&optimize=false&gist=4f896fa3b55d8dcedb64ef67dc1349b5)

### Rinkeby testnet addresses:
*ERC-20 Crowns* - `0xe157A3036d1c5C0EC3fAFF3c3AbcFf1300191047`, owned by `0x084b488B3cC68E9aECaCE8ABbe91E72D2Ff57C9B`

*Vesting Contract* - `0xE6111b1fC47B41F9EF613700Bd2B506526fb67a5`, owned by `0x02832a2ca659E429b0abA8dDC5f202B73AD901BA`

### Abi files:
Abi files generated by Remix are available at [blocklords/crowns/abi/](https://github.com/blocklords/crowns/tree/master/abi) folder.
It may be used to use to interact with blockchain by 3rd party online tools.

## Offline usage:
This project is built by *Embark.js* framework. Clone this git onto your machine. Please refer to [Embark page](https://github.com/embarklabs/embark) for instructions.
Once you've installed Embark, type on command:
```sh
embark run rinkeby
```

## Contribution, Suggestion

Want to contribute? Pull a request, or open an issue.