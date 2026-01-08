# DStock Core EVM

## Prerequisites
- [Foundry](https://book.getfoundry.sh/getting-started/installation)

## Installation

```bash
git clone https://github.com/dstock-core-evm/dstock-core-evm.git
cd dstock-core-evm
forge install
```

## Usage

### Compile
```bash
forge build
```

### Test
```bash
forge test
```

### Deploy
```bash
forge script script/Deploy.s.sol:DeployScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```
