# CreditBridge DeFi Application

A professional-grade DeFi application that interfaces with the CreditBridge smart contract to process real-world transactions. Built with Next.js, Tailwind CSS, and ethers.js.

## Features

- 🌐 Modern, responsive UI with sleek design
- 💳 Seamless wallet connection via MetaMask
- 💱 Real-time price feeds via Chainlink
- 🏦 ACH processing integration
- ✅ Built-in KYC verification
- 📊 Transaction history tracking
- 🔒 Secure burn and settle operations

## Tech Stack

- **Frontend Framework:** Next.js 14
- **Styling:** Tailwind CSS
- **UI Components:** shadcn/ui
- **Blockchain Integration:** ethers.js v5
- **Smart Contract:** Solidity (CreditBridge)

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open [http://localhost:8000](http://localhost:8000) in your browser

## Smart Contract Integration

The application interfaces with the CreditBridge smart contract which provides:

- Trust-backed ERC20 token functionality
- Compliance and KYC verification
- ACH processing capabilities
- Chainlink price feed integration
- Burn-settle mechanics

## Project Structure

```
src/
├── app/                    # Next.js app directory
│   ├── page.tsx           # Landing page
│   ├── dashboard/         # Dashboard pages
│   └── layout.tsx         # Root layout
├── components/            # React components
│   ├── WalletConnect.tsx  # Wallet connection
│   ├── TransactionForm   # Transaction form
│   └── TransactionHistory # Transaction history
├── lib/                   # Utilities
│   └── creditBridgeService.ts # Contract interactions
```

## Security Considerations

- All contract interactions are protected with proper error handling
- KYC verification required for burn and settle operations
- Real-time price feeds ensure accurate valuations
- Wallet connection state management for secure transactions

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

MIT License - see LICENSE file for details
