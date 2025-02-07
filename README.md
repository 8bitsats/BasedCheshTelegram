# Based Cheshire Trading Terminal Bot 🐱

A sophisticated Telegram bot that combines AI-powered trading insights, NFT creation, and DeFi functionality on the Base network. This innovative bot serves as your all-in-one companion for navigating the Base DeFi ecosystem with style and intelligence.

## 🌟 Key Features

### 1. AI-Powered Chat (Groq Integration)
- Engage in intelligent conversations about DeFi, crypto markets, and trading strategies
- Get real-time insights and analysis powered by Groq's advanced language model
- Ask questions about market trends, token analysis, and technical concepts

### 2. NFT Creation & Minting
- Generate unique AI art using DALL-E 3
- Automatic minting to Base mainnet
- IPFS integration for decentralized storage
- Full metadata support with attributes
- Direct minting to your wallet

### 3. Portfolio Management
- Real-time wallet balance tracking
- Token portfolio analysis
- Transaction history viewing
- Gas price monitoring
- Secure key management

### 4. DeFi Operations
- ETH deposits and withdrawals
- Token swapping capabilities (coming soon)
- Real-time gas fee estimation
- Secure transaction handling

### 5. Market Analysis
- Trending tokens tracking
- Real-time price updates
- Portfolio value tracking
- Market sentiment analysis

## 🤖 Bot Commands

### Basic Commands
- `/start` - Initialize the bot and display the main menu
- `/help` - Display help information and command list

### Chat & Analysis Commands
- `Chat with Groq` - Start an AI conversation about crypto and DeFi
- `Trending Tokens` - View current trending tokens on Base
- `Check Portfolio` - Analyze any wallet's holdings
- `Gas Price` - Check current Base network gas prices

### Wallet Operations
- `Check Balance` - View your wallet balance
- `Deposit ETH` - Get your deposit address
- `Withdraw ETH` - Withdraw ETH to another address
- `Export Key` - Securely export your private key
- `Transaction History` - View your recent transactions

### NFT Commands
- `Generate NFT` - Create and mint an AI-generated NFT
  - Format: `prompt | name | description`
  - Example: `a mystical cat in cyberpunk style | Cyber Cheshire | A digital feline guardian`

### Trading Commands (Coming Soon)
- `Buy Tokens` - Purchase tokens using ETH
- `Sell Tokens` - Sell tokens back to ETH

## 🏗 Technical Architecture

### Core Components
1. **Telegram Bot Interface**
   - Built using the Grammy framework
   - Real-time updates and interactive buttons
   - Markdown formatting for beautiful messages

2. **AI Integration**
   - Groq API for intelligent conversations
   - DALL-E 3 for NFT art generation
   - Custom prompt engineering for optimal results

3. **Blockchain Integration**
   - Web3.js for Base network interaction
   - Custom wallet management system
   - Secure transaction handling

4. **Storage & Security**
   - IPFS via Pinata for decentralized storage
   - Encrypted private key management
   - Environment variable configuration

### External Services
- **Birdeye API**: Market data and token tracking
- **Basescan API**: Transaction and gas price monitoring
- **Pinata**: IPFS gateway and pinning
- **OpenAI**: DALL-E 3 image generation

## 🚀 Innovation Highlights

1. **AI-First Approach**
   - Combines multiple AI models (Groq + DALL-E)
   - Natural language interaction for complex operations
   - AI-powered market analysis and insights

2. **Base Network Integration**
   - Native support for Base mainnet
   - Optimized gas handling
   - Real-time network monitoring

3. **NFT Innovation**
   - One-click AI art generation and minting
   - Automated IPFS storage
   - Rich metadata and attributes

4. **Security Features**
   - Encrypted key management
   - Secure transaction signing
   - Rate limiting and error handling

## 🛠 Setup Instructions

1. **Prerequisites**
   - Node.js v16 or higher
   - Telegram account
   - Base network wallet with ETH

2. **Environment Setup**
   ```bash
   # Clone the repository
   git clone [repository-url]
   cd Based-Chesh-Trading-Terminal-Bot

   # Install dependencies
   npm install

   # Configure environment variables
   cp .env.example .env
   # Edit .env with your credentials
   ```

3. **Required API Keys**
   - Telegram Bot Token (from @BotFather)
   - Groq API Key
   - OpenAI API Key
   - Pinata API Keys
   - Birdeye API Key
   - Basescan API Key

4. **Running the Bot**
   ```bash
   # Start the bot
   node index.js
   ```

## 📈 Future Roadmap

1. **Enhanced Trading Features**
   - DEX integration for token swapping
   - Limit orders and automated trading
   - Portfolio rebalancing

2. **Advanced AI Features**
   - Market prediction models
   - Sentiment analysis
   - Custom trading strategies

3. **Community Features**
   - Social trading
   - Community-driven NFT collections
   - Trading competitions

## 🤝 Contributing

We welcome contributions! Please see our contributing guidelines for more details.

## 📝 License

This project is licensed under the ISC License.
