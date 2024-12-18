# BRO💪FIGHTS
Buy weapons and battle with other Bro NFTs.

⚙️ Built using NextJS, RainbowKit, Hardhat, Wagmi, and Typescript. Deployed on Mantle Sepolia

Deployed smart contract on Mantle Sepolia : https://explorer.sepolia.mantle.xyz/address/0xb7a39632a3C45FF7027AfdF0B41dad8408C12190

## Welcome to BRO💪FIGHTS Homepage


## Marketplace page


## Game Play page


## Requirements

Before you begin, you need to install the following tools:

- [Node (v18 LTS)](https://nodejs.org/en/download/)
- Yarn ([v1](https://classic.yarnpkg.com/en/docs/install/) or [v2+](https://yarnpkg.com/getting-started/install))
- [Git](https://git-scm.com/downloads)

## Quickstart

To get started with BRO💪FIGHTS, follow the steps below:

1. Clone this repo & install dependencies

```
git clone https://github.com/govardhan666/Bro_Fights_on_Mantle
cd Bro_Fights_on_Mantle
yarn install
```

2. Run a local network in the first terminal:

```
yarn chain
```

This command starts a local Ethereum network using Hardhat. The network runs on your local machine and can be used for testing and development. You can customize the network configuration in `hardhat.config.ts`.

3. On a second terminal, deploy the test contract:

```
yarn deploy
```

This command deploys a test smart contract to the local network. The contract is located in `packages/hardhat/contracts` and can be modified to suit your needs. The `yarn deploy` command uses the deploy script located in `packages/hardhat/deploy` to deploy the contract to the network. You can also customize the deploy script.

4. On a third terminal, start your NextJS app:

```
yarn start
```

Visit your app on: `http://localhost:3000`. You can interact with your smart contract using the contract component or the example ui in the frontend. You can tweak the app config in `packages/nextjs/scaffold.config.ts`.