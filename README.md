# Blockchain

* [₿itcoin](#bitcoin)
  * [Digital Currency & the Double-spending Problem](#digital-currency-&-the-double-spending-problem)
  * [The First Blockchain](#the-first-blockchain)
  * [Bitcoin Nodes](#bitcoin-nodes)
  * [Transactions](#transactions)
* [Smart Contracts](#smart-contracts)
* [DApps](#dapps)
* [DAOs](#daos)
* [Ethereum](#ethereum)
* [Neo](#neo)
* [Lumen](#lumen)
* [Privacy Currencies](#privacy-currencies)
* [PoW vs PoS](#pow-vs-pos)
* [Double Spending Attacks](#double-spending-attacks)
  * [Race Attack](#race-attack)
  * [Finney Attack](#finney-attack)
  * [51% Attack](#51%-attack)
* [Forks](#forks)
* [Decentralized vs Centralized](#decentralized-vs-centralized)
* [Further Reading](#further-reading)
* [Footnotes](#footnotes)

## Bitcoin
#### The First Decentralized Cryptocurrency & the First Blockchain

### Digital Currency & the Double-spending Problem

One of the early obstacles to reliable digital currency is what is called the **double-spending problem**. In many early prototypes of digital currency, it was possible for currency holders to spend the same token/unit of currency twice, as if they spent their money, stole it back, and spent it again elsewhere.

[Satoshi Nakamoto](#satoshi-nakamoto), the person or people behind Bitcoin, solved the double-spending problem with the first-ever implementation of **Blockchain**.

**Note:** It is still possible to carry out double-spending attacks on flawed, vulnerable, or compromised blockchains. [Click here for more on double-spending attacks.](#double-spending-attacks-against-blockchains)

### The First Blockchain
#### What is a Blockchain?

A blockchain is a chain of blocks of records linked with cryptographic hashes in [Merkle trees](#merkle-trees), also known as hash trees.

While early theory behind blockchain dates back to the early 1990s[<sup>1</sup>](#footnotes), the first blockchain was conceived in 2008 and implemented in 2009 as Bitcoin's public ledger.

In the Bitcoin core, the Bitcoin blockchain serves as a decentralized public ledger, containing all of the transactions that have ever occurred on the Bitcoin network.

By having its nodes spread across the globe, and controlled by multiple different actors, no single organization or person can alter or otherwise control Bitcoin, and the Bitcoin network's governance is automated via a proof-of-work (PoW) system.

### Bitcoin Nodes
#### What is a Bitcoin Node?

A full node on the Bitcoin network contains a record of every transaction that has ever occurred on the Bitcoin blockchain, or a full copy of the blockchain. Nodes...
<!-- TODO add more here -->

### Transactions
#### What is a Bitcoin Transaction?

In order for any amount of Bitcoin to be transferred from one address to another on the blockchain, that transaction is sent as
<!-- TODO add more stuff here -->

- Wallets, mining, etc

### Bitcoin Mining
#### What is Bitcoin Mining?

## PoW vs PoS

## Smart Contracts

## DApps

## DAOs

## Forks


## Ethereum
Truly decentralized.

- Solidity, Vyper langs
- Gas
- Ganache
- Metamask
- Ether wallet & Mist browser
- Ether-based tokens & ERC standards
- Governance structure
- Carbon voting

Example Ethereum Projects

- CryptoKitties
- Decentraland
- etc

## Neo

NOT decentralized -- a majority of nodes are controlled and run by one party.

- Multi-language support (Python, JS, etc)
- Centralized node governance...

## Lumen

NOT decentralized.

## Double-spending Attacks
## Against Blockchains

#### Race Attack

#### Finney Attack

#### 51% Attack

## Decentralized vs Centralized

## Further reading

- [Original Bitcoin Paper, Satoshi Nakamoto, 2008](https://bitcoin.org/bitcoin.pdf)
- [Mastering Bitcoin: Programming the Open Blockchain](https://github.com/bitcoinbook/bitcoinbook)
- [About "Satoshi Nakamoto"](https://en.wikipedia.org/wiki/Satoshi_Nakamoto)

## Footnotes
##### 1
- [How to timestamp a digital document, Haber, Stornetta, 1990](https://link.springer.com/article/10.1007/BF00196791) -- First work on design of cryptographically-secured blockchain.
- [Improving the Efficiency and Reliability of Digital Time-stamping, Bayer, Haber, Stornetta, 1992](https://link.springer.com/chapter/10.1007/978-1-4613-9323-8_24) -- Addition of Merkle trees to blockchain design.
