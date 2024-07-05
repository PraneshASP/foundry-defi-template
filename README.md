## 🛡️ Foundry DeFi Template 🛡️

This is a starter template for [Foundry](https://book.getfoundry.sh/) for DeFi protocols. The template comes with proper directory structure to get started with your DeFi project. Feel free to tweak it as per the requirements. 

#### Read the [blog post](https://flawsomedev.com/blog/ideal-defi-protocol-architecture-solidity-template) for more details. 

---

#### Src directory structure:

```bash
.
├── interfaces
│   └── external
├── mocks
└── protocol
    ├── core
    ├── integrations
    │   ├── aave
    │   └── uniswap
    ├── libraries
    ├── misc
    ├── oracles
    └── tokenization
```

#### Tests directory structure:

```log
.
├── common
│   ├── BaseTestSetup.sol
│   ├── BaseTestSetupLive.sol
│   └── harness
│       └── VaultHarness.sol
├── fork
│   └── vault
│       ├── Deposit.t.sol
│       └── trees
│           └── Deposit.tree
└── unit
    └── vault
        ├── Deposit.t.sol
        └── trees
            └── Deposit.tree
```

#### Foundry docs:

https://book.getfoundry.sh/

## Usage

#### Build

```shell
$ forge build
```

#### Test

```shell
$ forge test
```

#### Format

```shell
$ forge fmt
```

#### Gas Snapshots

```shell
$ forge snapshot
```

#### Deploy

```shell
$ forge script script/DeployCore.s.sol:DeployCore --rpc-url <your_rpc_url> --broadcast
```

#### Help

```shell
$ forge --help
```
