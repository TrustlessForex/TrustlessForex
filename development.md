# Development 

## Tools

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
