# first-dapp
My first decentralized app, built as part of the LearnWeb3.io beginner track. A simple Solidity smart contract deployed to a testnet with a basic frontend using Ethers.js, allowing wallet connections and on‑chain interactions — my first step into Web3 development.

---

## Contract Information
- **Contract Address:** `0xD2f0C7BF71b3F8219827680D1b0cB6826AA408a0`
- **Network:** zkSync Sepolia Testnet
- **RPC URL:** https://sepolia.era.zksync.dev
- **Chain ID:** 300
- **Currency Symbol:** ETH
- **Block Explorer:** [zkSync Sepolia Explorer](https://sepolia.explorer.zksync.io)

---

## How to Run and Test This Project

### Prerequisites
- MetaMask browser extension installed
- Some test ETH on zkSync Sepolia Testnet (get from a faucet)
- Modern browser (Chrome, Firefox, Edge)

### Steps to Run Locally
1. **Clone the repository**
   ```powershell
   git clone https://github.com/yourusername/first-dapp.git
   cd first-dapp
   ```
2. **Open `index.html` in your browser**
   - You can simply double-click the file or use a local server (like Live Server in VS Code).
3. **Connect MetaMask to zkSync Sepolia Testnet**
   - The dApp will prompt you to switch networks automatically.
   - If not, add zkSync Sepolia manually:
     - Network Name: zkSync Sepolia Testnet
     - RPC URL: https://sepolia.era.zksync.dev
     - Chain ID: 300
     - Currency Symbol: ETH
     - Block Explorer: https://sepolia.explorer.zksync.io
4. **Interact with the dApp**
   - Enter your mood in the input box.
   - Click "Set Mood" to save it on-chain.
   - Click "Get Mood" to read your mood from the blockchain.

### Notes
- All interactions are on-chain and require MetaMask approval.
- Make sure you have test ETH for transactions.
- If you see errors about the network, check that MetaMask is on zkSync Sepolia.

### Troubleshooting
- If you get a chain mismatch error, switch MetaMask to zkSync Sepolia Testnet.
- If transactions fail, ensure you have enough test ETH.
- For any other issues, check the browser console for error messages.

---
 welcome to Web3!
