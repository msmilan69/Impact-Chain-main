# Impact Chain

Impact Chain is a blockchain-based platform designed to facilitate transparent, decentralized, and impactful charitable giving. The project leverages smart contracts to ensure trust, accountability, and efficiency in donations and fund management.

## Project Structure

- **contracts/**: Solidity smart contracts for token, funding, governance, rewards, and staking.
- **backend/**: Node.js/Express backend for API and business logic.
- **client/**: React/TypeScript frontend for user interaction.
- **scripts/**: Deployment and utility scripts.

## Features
- Decentralized donation and funding platform
- DAO governance for project decisions
- Token rewards and staking
- Transparent tracking of causes and donations

## Getting Started

### Prerequisites
- Node.js & npm
- Hardhat (for smart contract development)
- MetaMask (for interacting with the blockchain)

### Installation

1. **Clone the repository:**
   ```sh
   git clone <repo-url>
   cd Impact-Chain-main
   ```
2. **Install dependencies:**
   ```sh
   cd backend && npm install
   cd ../client && npm install
   ```
3. **Compile contracts:**
   ```sh
   npx hardhat compile
   ```
4. **Run backend:**
   ```sh
   cd backend && npm start
   ```
5. **Run frontend:**
   ```sh
   cd client && npm run dev
   ```

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](LICENSE)
