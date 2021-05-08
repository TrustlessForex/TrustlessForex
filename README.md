# tfx.cash - Work in progress 👷

Premier source of Forex stablecoins for DeFi.

Our mission is to do to Forex what bitcoin did to gold.

We provide ways to create Forex stablecoins for Defi. The system use what we call a currency factory for each currency. Each factory is independent from each other and forked from a security-audited smart contract (Liquity).

# Stablecoins
Fx stablecoins include: tEUR, tCNY, tCHF, tAUD, tCAD, tJPY, tKRW and tGBP. Each price is secured with [price oracles](https://data.chain.link/) from ChainLink. 
## Peg and Collaterization: 
Each stablecoin is secured by at least 110% or more of the same amount in ETH. The only collateral for each stablecoin is ETH, which is most trustless collateral possible in DeFi. The peg is assured by the Liquity set of smart contract.

# Revenue sharing tokens
Each currency factory is emitting its own token, which is named 'currency code' + 'fx', i.e., EURfx, CNYfx, CHFfx, AUDfx, CADfx, JPYfx, KRWFfx and GBPfx. The max amount of revenue share token for a currency is 21 million. 21M EURfx, 21M CNYfx, etc. The token emission is similar to bitcoin: issuance is halved every 4 years. Each revenue sharing tokens is only used for the single purpose of capturing a share of the management fees.

## Revenue share mechanism
Holders who stake CURfx tokens in the dividend pool receive a share of the management fees of the corresponding currency factory.

# No governance token
We first demonstrate the usefulness of our products. Then on top of a successful line of product and with a clear roadmap, only then we will build a governance token. This is a very similar philosophy to the Uniswap story: first prioritize usefulness, decentralization and trustlessness and then later on introduce a governance token by airdropping it to all past and present users + revenue share token holders. 

# Deployments

## Testnet

### Ropsten

* TroveManager: 0x85402e4954AD0F0Be5D28E2df76c3d14A0E0Bf31
* StabilityPool: 0x5FD8a915Ec55c7Bac16054261eaE580e15161339
* BorrowerOperations: 0x985c156AD6027eBf63DD6a500b07c90999479D56
