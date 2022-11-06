# OpenCastle

First implementation of the Session Key Plugin
Goerli: https://goerli.etherscan.io/address/0xd4e49154f02eC88E4D4fC79c61b87D285e85E400
Optimism goerli: https://blockscout.com/optimism/goerli/address/0xe3D5c725528A37cB924f094C09969baF87c5b391
Polygon mumbai: https://mumbai.polygonscan.com/address/0x278866e79C606e71C0B2Bc377D75B65475b03e33

## Usage

### Pre Requisites

Before running any command, make sure to install dependencies:

```sh
$ yarn install
```

### Compile

Compile the smart contracts with Hardhat:

```sh
$ yarn compile
```

### Test

Run the tests:

```sh
$ yarn test
```

### Deploy contract to network (requires Mnemonic and Infura API key)

```
npx hardhat run --network rinkeby ./scripts/deploy.ts
```

### Validate a contract with etherscan (requires API key)

```
npx hardhat verify --network <network> <DEPLOYED_CONTRACT_ADDRESS> "Constructor argument 1"
```
