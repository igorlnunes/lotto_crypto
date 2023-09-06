# Proveably Rando Raffle Contracts

## About

This code is to create a proveably random start contract lottery.

## What we want it to do?

  1. Users can enter by paying for a ticket;
    1. The ticket fees are going to go to the winner during the draw;
  2. After X period of time, the lottery will automatically draw a winner;
    1. And this will be done programmatically;
  3. Using Chainlink VRF & Chainlink Automation
    1. Chainlink VRF -> Randomness;
    2. Chainlink Automation -> Time based trigger



```c
// Layout of Contract:
// version
// imports
// errors
// interfaces, libraries, contracts
// Type declarations
// State variables
// Events
// Modifiers
// Functions

// Layout of Functions:
// constructor
// receive function (if exists)
// fallback function (if exists)
// external
// public
// internal
// private
// view & pure functions
```



## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
## Tests
1. Write some deploy scripts
2. Write our tests
  1. Work on a local chain
  2. Forked Testnet
  3. Forked Mainnet