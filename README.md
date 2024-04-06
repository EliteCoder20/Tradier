## Getting Started

This is the Tradier, a Decentralized algorithmic trading bot marketplace and platform.

For local use, clone and run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

## Inspiration

Over the years, the investment landscape has been riddled with promises of revolutionary "next-gen trading bots" promising life-changing returns. Unfortunately, many of these turn out to be elaborate Ponzi schemes, with the infamous BitConnect scandal being a prime example. Investors lost over $2.4 billion to a purported "trading bot" that, in reality, never existed. In response to such deceptive practices, Tradier emerged. Our platform is dedicated to fostering a new era of trading by offering a decentralized, transparent environment for creating, investing in, and withdrawing from algorithmic trading bots.

## What it does

Tradier revolutionizes the world of trading through its unique NFT collection, leveraging the robust Avalanche C-chain. Each NFT in this collection is not just a digital asset but also functions as an individual wallet (under the ERC6551 standard), capable of holding and managing on-chain assets. What sets these NFTs apart is their embedded JavaScript code, which dictates their trading behaviors. This on-chain script is executed using Chainlink Functions, a groundbreaking feature that enables our trading bots to access both web2 APIs and external AI models, aiding in their decentralized decision-making process. The deployment of an NFT on Tradier allows the manager to set up automated trading strategies via Chainlink Automation's executeTrade function. This opens the door for external investors to engage with the NFT bot, allowing for both investment and withdrawal. To ensure equitable distribution of shares, the NFT bot utilizes Chainlink Data Feeds. This feature accurately assesses the current value of the wallet's tradable assets, thereby allocating shares in a fair and transparent manner. Moreover, the platform offers a smooth front-end interface for users to create, invest, withdraw, and even interact with "Droidvisor" which is powered by GPT-4 and Coinmarketcap to help you make informed decisions on the crypto market.

## How Engineerians/Tradier is built

The frontend utilizes NextJs and ReactJs, the backend is powered by ethers, Thirdweb, OpenAI, and Coinmarketcap. The contracts are written in solidity and powered by chainlink functions, automation, and data feeds. The contracts are hosted on the avalanche C-chain.

## What's next for Engineerians/Tradier

Tradier, currently in its functional prototype phase, is poised for transformation into a Minimum Viable Product (MVP). To achieve this milestone, several key steps are outlined. Expansion of On-Chain Capabilities: We aim to broaden the range of on-chain actions. This includes integrating a variety of routers and functions, surpassing the current offerings, to enhance the versatility and efficiency of our trading bots. Infrastructure Enhancement: Another critical step involves refining the infrastructure to support events and logs more effectively. This enhancement is vital for accurately tracking profit/loss values and integrating performance fees along with other final features. Finalizing and Securing the Platform: The last phase involves a thorough cleanup of our test contracts. This includes removing hardcoded test addresses to ensure greater flexibility and security. Subsequently, a comprehensive audit of the contract will be conducted to ensure its integrity and reliability.

## BRIEF DESCRIPTION ON HOW YOUR PROJECT FITS INTO CHAINLINK: CHAINLINK TRACK TRACK
In the Chainlink track, Tradier utilizes Chainlink Functions and Chainlink Data Feeds to enhance the capabilities of its trading bots. Chainlink Functions enable the execution of on-chain scripts, accessing both web2 APIs and external AI models for decentralized decision-making. Moreover, Chainlink Data Feeds accurately assess the value of tradable assets in wallets, ensuring fair and transparent allocation of shares within the platform.

## BRIEF DESCRIPTION ON HOW YOUR PROJECT FITS INTO ETHEREUM FOUNDATION: ETHEREUM TRACK TRACK
Tradier fits into the Ethereum Foundation's Ethereum track by utilizing the Ethereum blockchain for its NFT collection and ERC-6551 standard wallets. It leverages Ethereum's decentralized nature to provide a transparent environment for algorithmic trading bots. Additionally, it integrates with Chainlink Functions for executing on-chain scripts and accessing external APIs, which enhances the functionality of its trading bots.

## LICENSE
MIT

### Build with love by Team Engineerians

| Name            | Github                                         | Discord         |
| --------------- | ---------------------------------------------- | --------------- |
| TechZombie333 | [@Kundan](https://github.com/TechZombie333)   | codefunky   |
| Aditya101 | [@harshshen](https://github.com/EliteCoder20)   | elitecoder1001  |
