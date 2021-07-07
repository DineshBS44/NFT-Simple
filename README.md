# Simple NFT

Simple NFT is delployed to Ethereum's Public test network called Rinkeby

The smart contract is verified in Etherscan

The smart contract is compiled, tested and deployed using Chainlink Truffle Box

<br/>
<p align="center">
<a href="https://chain.link" target="_blank">
<img src="https://raw.githubusercontent.com/smartcontractkit/box/master/box-img-lg.png" width="225" alt="Chainlink Truffle logo">
</a>
</p>
<br/>

## Requirements

- NPM

## Installation

1. Install truffle

```bash
npm install truffle -g
```

2. Setup repo

```bash
mkdir SimpleNFT
cd SimpleNFT/
```

3. Unbox

```bash
truffle unbox smartcontractkit/box
```

4. Install dependencies by running:

```bash
npm install

# OR...

yarn install
```

## Compile

```bash
truffle compile
```

## Test

```bash
truffle test
```

## Deploy

For deploying to the kovan network, Truffle will use `truffle-hdwallet-provider` for your mnemonic and an RPC URL. Set your environment variables `$RPC_URL` and `$MNEMONIC` before running:

```bash
truffle migrate --reset --network rinkeby
```

## Verify

For verifying the smart contract deployed to Rinkeby

```bash
truffle run verify NFTSimple --network rinkeby --license MIT
```

## Developer

- **Dinesh B S** [(@DineshBS44)](https://github.com/DineshBS44)

## License

Licensed under MIT License : https://opensource.org/licenses/MIT

<br>
<br>
