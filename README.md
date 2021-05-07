# TrustlessForex

International currencies for DeFi

We introduce a new protocol for creating synthetic international currencies in decentralised finance. The system use what we call a currency factory for each currency. Each factory is independent from each other and cloned from a security-audited smart contract (Liquity).

Currency factory at start: TEUR 🇪🇺, TCNY 🇨🇳, TCHF 🇨🇭, TAUD 🇦🇺, TCAD 🇨🇦, TJPY 🇯🇵, TKRW 🇰🇷 and TGBP 🇬🇧 
with [price oracles](https://data.chain.link/) from ChainLink.

# Revenue sharing tokens
Each currency factory is emitting its own token, which allow holders to get a share of the factory revenues by staking them in the Dividend Pool. 

8 revevenue sharing tokens EURFX, CNYFX, CHFFX, AUDFX, CADFX, JPYFX, KRWFX and GBPFX.

# Governance token
A governance token TFOREX is introduced to govern the addition and promotion of new currencies in the protocol and general integration in the DeFi eco-system.

# Tools

Desktop
* Remix IDE: write and deploy contracts
* Ganache: local step-by-step chain loaded with addresses

Web
* https://abi.hashex.org/# to obtain Constructor arguments ABI-encoded

# Liquity

## Compiling smart contracts
Use `Enable optimization: 200`

## Deploying Liquity smart contracts:
Let's start with `LUSDToken.sol`. You first need to deploy these 3 contracts as describe in its `constructor`:

```
    constructor
    (
        address _troveManagerAddress,
        address _stabilityPoolAddress,
        address _borrowerOperationsAddress
    )
```

* `TroveManager.sol`
* `StabilityPool.sol`
* `BorrowOperations.sol`

# Testnets

## Ropsten

* TroveManager: 0x85402e4954AD0F0Be5D28E2df76c3d14A0E0Bf31
* StabilityPool: 0x5FD8a915Ec55c7Bac16054261eaE580e15161339
* BorrowerOperations: 0x985c156AD6027eBf63DD6a500b07c90999479D56
