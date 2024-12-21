
# lottery-smart-contract

A robust and secure smart contract implementation for a decentralized lottery platform on Ethereum, built using Solidity. This contract ensures fairness and transparency by leveraging cryptographic randomness.

## Features

- **Fair Lottery Mechanics:** Utilizes secure randomness for selecting winners.
- **Decentralized:** Operates entirely on-chain with no reliance on centralized entities.
- **Efficient:** Optimized for minimal gas usage to reduce user costs.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/anshika1307-code/Lotterydapp-smartcontract.git
   git clone https://github.com/your-username/CryptoLotteryDapp-website.git
   ```


## Usage

1. Compile the contract:
   ```bash
   npx hardhat compile
   ```
2. Deploy to a local blockchain:
   ```bash
   npx hardhat run scripts/deploy.js --network localhost
   ```
3. Test the contract:
   ```bash
   npx hardhat test
   ```

## Smart Contract Details

- **Language:** Solidity
- **Randomness:** Implemented using Chainlink VRF (Verifiable Random Function)
- **Optimization:** Gas-efficient structure with minimal external calls

## License

This project is licensed under the MIT License. See the LICENSE file for details.

# Crypto Lottery DApp Website

A user-friendly front-end for interacting with the Lottery Smart Contract. Built with React and integrated with Web3.js for seamless blockchain connectivity.

## Features

- **Responsive Design:** Accessible across devices with a clean and intuitive UI.
- **Blockchain Integration:** Easily connect with MetaMask or other Web3 wallets.
- **Real-time Updates:** Displays the latest lottery information directly from the blockchain.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/anshika1307-code/CryptoLotteryDapp-website.git
   ```
2. Navigate to the project directory:
   ```bash
   cd CryptoLotteryDapp-website
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

## Usage

1. Start the development server:
   ```bash
   npm start
   ```
2. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Technologies Used

- **Front-end:** React, TailwindCSS
- **Blockchain Interaction:** Web3.js, Thirdweb SDK
- **Hosting:** Vercel

## Frontend Repository

  [Click here for the frontend repo](https://github.com/anshika1307-code/CryptoLotteryDapp-website)
