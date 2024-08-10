
<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/6295/6295417.png" width="100" />
</p>

<h1 align="center"> Decentralized Crowdfunding Platform</h1>


## Quick Links

> - [Overview](#overview)
> - [Features](#features)
> - [Usage](#usage)
> - [Repository Structure](#repository-structure)
> - [Modules](#modules)
> - [Getting Started](#getting-started)
>   - [Installation](#installation)
>   - [Running crowdFunding](#running-crowdFunding)
>   - [Tests](#tests)
> - [Project Roadmap](#project-roadmap)
> - [Contributing](#contributing)
> - [License](#license)
> - [Acknowledgments](#acknowledgments)

---

## Overview
This project is a decentralized crowdfunding platform built on blockchain technology. It allows users to create and contribute to crowdfunding campaigns without relying on intermediaries, ensuring transparency, security, and trust. The platform operates on smart contracts, enabling direct interaction between campaign creators and backers.





## Features

- **Decentralized**: No central authority controls the platform. It operates fully on smart contracts.
- **Transparency**: All transactions and campaign details are recorded on the blockchain, ensuring complete transparency.
- **Security**: Funds are securely held in smart contracts until the campaign goals are met.
- **Ease of Use**: Simple interface for creating campaigns and contributing to them.
- **Global Accessibility**: Anyone with a blockchain wallet can participate from anywhere in the world.

## Technology Stack

- **Frontend**: React.js, TypeScript
- **Smart Contracts**: Solidity
- **Blockchain**: Ethereum (Testnet/Mainnet)
- **Development Tools**: Truffle/Hardhat, MetaMask
- **Storage**: IPFS (InterPlanetary File System) for decentralized file storage
- **UI/UX**: Tailwind CSS

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/crowdfunding-platform.git
   cd crowdfunding-platform
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Configure Environment Variables**
   Create a `.env` file in the root directory and add your environment variables:
   ```bash
   REACT_APP_INFURA_PROJECT_ID=your_infura_project_id
   REACT_APP_CONTRACT_ADDRESS=your_deployed_contract_address
   REACT_APP_NETWORK=your_network (e.g., ropsten, rinkeby)
   ```

4. **Compile and Deploy Smart Contracts**
   ```bash
   npx hardhat compile
   npx hardhat run scripts/deploy.js --network your_network
   ```

5. **Start the Frontend**
   ```bash
   npm start
   ```

6. **Access the Platform**
   Open your web browser and navigate to `http://localhost:3000`.

## Usage

### Creating a Campaign
1. Connect your wallet using MetaMask.
2. Click on "Create Campaign."
3. Enter campaign details: title, description, funding goal, and deadline.
4. Confirm the transaction to deploy the campaign smart contract.

### Contributing to a Campaign
1. Browse available campaigns.
2. Select a campaign and click "Contribute."
3. Enter the amount you wish to contribute.
4. Confirm the transaction via MetaMask.

### Withdrawing Funds
- Campaign creators can withdraw funds only if the funding goal is met within the deadline. 
- Backers can claim refunds if the campaign does not reach its goal.

## Project Structure

- `contracts/`: Contains Solidity smart contracts.
- `scripts/`: Deployment scripts for smart contracts.
- `src/`: React.js frontend source code.
- `test/`: Test files for smart contracts.
- `artifacts/`: Compiled contract artifacts.
- `public/`: Static assets for the frontend.




## Repository Structure

```sh
└── crowdFunding/
    ├── README.md
    ├── client
    │   ├── .gitignore
    │   ├── LICENSE.md
    │   ├── README.md
    │   ├── index.html
    │   ├── package-lock.json
    │   ├── package.json
    │   ├── postcss.config.js
    │   ├── src
    │   │   ├── App.jsx
    │   │   ├── assets
    │   │   │   ├── create-campaign.svg
    │   │   │   ├── dashboard.svg
    │   │   │   ├── index.js
    │   │   │   ├── loader.svg
    │   │   │   ├── logo.svg
    │   │   │   ├── logout.svg
    │   │   │   ├── menu.svg
    │   │   │   ├── money.svg
    │   │   │   ├── payment.svg
    │   │   │   ├── profile.svg
    │   │   │   ├── search.svg
    │   │   │   ├── sun.svg
    │   │   │   ├── thirdweb.png
    │   │   │   ├── type.svg
    │   │   │   └── withdraw.svg
    │   │   ├── components
    │   │   │   ├── CountBox.jsx
    │   │   │   ├── CustomButton.jsx
    │   │   │   ├── DisplayCampaigns.jsx
    │   │   │   ├── FormField.jsx
    │   │   │   ├── FundCard.jsx
    │   │   │   ├── Loader.jsx
    │   │   │   ├── Navbar.jsx
    │   │   │   ├── Sidebar.jsx
    │   │   │   └── index.js
    │   │   ├── constants
    │   │   │   └── index.js
    │   │   ├── context
    │   │   │   └── index.jsx
    │   │   ├── index.css
    │   │   ├── main.jsx
    │   │   ├── pages
    │   │   │   ├── CampaignDetails.jsx
    │   │   │   ├── CreateCampaign.jsx
    │   │   │   ├── Home.jsx
    │   │   │   ├── Profile.jsx
    │   │   │   └── index.js
    │   │   └── utils
    │   │       └── index.js
    │   ├── tailwind.config.js
    │   ├── vite.config.js
    │   └── yarn.lock
    └── web3
        ├── .gitignore
        ├── README.md
        ├── contracts
        │   └── CrowdFunding.sol
        ├── hardhat.config.js
        ├── package-lock.json
        ├── package.json
        └── yarn.lock
```



