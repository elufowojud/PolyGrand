<div align="center">

# 🎯 PolyGrand

### Next-Generation Prediction Markets Built on Algorand

*Capturing the $8B prediction market opportunity with 100x lower costs and 3x faster performance*
--
[![Algorand](https://img.shields.io/badge/Built%20on-Algorand-00dc94?style=for-the-badge&logo=algorand)](https://algorand.co/)
[![PyTeal](https://img.shields.io/badge/Smart%20Contracts-PyTeal-blue?style=for-the-badge)](https://pyteal.readthedocs.io/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

[Quick Start](#-quick-start) • [Roadmap](#-roadmap) • [Architecture](#-technical-architecture)

</div>

---

## 🚨 The Problem

**Polymarket's $8B valuation proves prediction markets work.** But Ethereum-based platforms face critical limitations:

| Challenge | Ethereum (Polymarket) | PolyGrand (Algorand) |
|-----------|----------------------|---------------------|
| **Transaction Fees** | $2-50 | $0.0002 (100x cheaper) |
| **Trade Finality** | 15+ seconds | 4.5 seconds (3x faster) |
| **Energy Efficiency** | High | 2500x more efficient |
| **US Market Access** | Blocked | Regulatory-ready |

**Result:** Millions of potential users priced out. Billions in untapped markets.

---

## 🌟 Our Solution

PolyGrand is a next-generation prediction market platform built on Algorand that delivers:

### Technical Superiority
- ✅ **100x Cheaper** - $0.0002 transactions enable micro-predictions
- ✅ **3x Faster** - 4.5 second finality for instant trading
- ✅ **Energy Efficient** - Carbon-neutral blockchain infrastructure
- ✅ **Quantum-Secure** - 6 years of perfect uptime

### Unique Features
- 🎯 **Multi-Dimensional Markets** - Beyond binary yes/no outcomes
- 👥 **Social Trading** - Stake on expert predictors
- 🏆 **Battle Royale Tournaments** - Gamified prediction competitions
- 🤖 **AI vs Human Benchmarking** - Canonical accuracy platform
- 💎 **AOT Token Economy** - Staking rewards and governance

---

## 🛠 Technical Architecture

### Smart Contract Layer (PyTeal)
```
PolyGraph/
├── contracts/                 # PyTeal Smart Contracts
├── backend/                   # python
├── frontend/                  # React/TypeScript Frontend
├── scripts/                   # Deployment & Utility Scripts
└── docs/                      # Documentation

```

### Key Components
- **Algorand Standard Assets (ASAs)** - Outcome tokens for each market
- **Atomic Transfers** - Complex multi-asset trades in single transactions
- **State Proofs** - Cryptographic verification of market outcomes
- **React/TypeScript Frontend** - Modern responsive UI
- **Node.js Backend** - Real-time market data and APIs

---

## Demo Video
<!-- Loom embed (iframe). Note: GitHub strips iframes, keep the linked thumbnail below as a fallback. -->
<iframe src="https://www.loom.com/embed/56216210c8154e21961c7687c931f3c7" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen style="width:100%;max-width:900px;height:520px;"></iframe>

<!-- Fallback clickable thumbnail (works on GitHub and other places that disallow iframes) -->
[![Watch demo on Loom](https://cdn.loom.com/sessions/thumbnails/56216210c8154e21961c7687c931f3c7-with-play.gif)](https://www.loom.com/share/56216210c8154e21961c7687c931f3c7)

<!-- Direct link -->
[Open the demo video on Loom](https://www.loom.com/share/56216210c8154e21961c7687c931f3c7)
---


## UI Screenshots
<img width="1326" height="655" alt="image" src="https://github.com/user-attachments/assets/f6dd9a16-47a5-47e9-bfb5-cccf1b0ac8a7" />
<img width="1260" height="604" alt="image" src="https://github.com/user-attachments/assets/690ddad3-c559-4ef3-bf88-edbd8e0befd3" />
<img width="1229" height="627" alt="image" src="https://github.com/user-attachments/assets/27430b06-22d8-48aa-91fc-ffdac85e0b9c" />
<img width="796" height="618" alt="image" src="https://github.com/user-attachments/assets/eff38dbb-49ed-428f-b95b-e5ce8ddb1ed6" />




---

## 🗺 Roadmap

### Phase 1: Foundation (Months 1-6)
- [x] Smart contract development
- [x] TestNet deployment
- [x] Frontend MVP launch
- [ ] Mobile app development
- [ ] Advanced trading features (limit orders, leverage)

### Phase 2: Growth (Months 6-12)
- [ ] Cross-chain prediction aggregation
- [ ] Enterprise white-label solutions
- [ ] US regulatory compliance features
- [ ] Institutional API launch

### Phase 3: Scale (Months 12-24)
- [ ] Prediction market infrastructure provider
- [ ] AI prediction data marketplace
- [ ] Corporate decision market platform

---

## 🏆 Competitive Advantages

| Feature | PolyGrand | Polymarket | Augur | Gnosis |
|---------|-----------|------------|-------|--------|
| **Transaction Cost** | $0.0002 | $2-50 | $5-30 | $3-20 |
| **Finality Speed** | 4.5s | 15s+ | 60s+ | 12s+ |
| **Energy Efficient** | ✅ | ❌ | ❌ | ❌ |
| **Social Trading** | ✅ | ❌ | ❌ | ❌ |
| **Tournaments** | ✅ | ❌ | ❌ | ❌ |
| **AI Integration** | ✅ | ❌ | ❌ | ❌ |

---

## 🚀 Quick Start

### Prerequisites
- **Python** 3.12+
- **Node.js** 18+
- **npm** 9+
- **Algorand account** with TestNet funds (for contract deployment)

### Installation & Setup

#### One-Command Setup

The easiest way to run the entire PolyGrand stack (frontend + backend):

**Linux/Mac:**
```bash
git clone https://github.com/Ei-Sandi/PolyGrand.git
cd PolyGrand
./start.sh
```

**Windows:**
```cmd
git clone https://github.com/Ei-Sandi/PolyGrand.git
cd PolyGrand
start.bat
```

The script will:
- ✅ Create Python virtual environment
- ✅ Install all dependencies (Python & Node.js)
- ✅ Start backend (FastAPI) on http://localhost:8000
- ✅ Start frontend (Vite) on http://localhost:3000

#### Manual Setup

If you prefer to set up manually:

```bash
# 1. Clone the repository
git clone https://github.com/Ei-Sandi/PolyGrand.git
cd PolyGrand

# 2. Install Python dependencies
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
pip install -r backend/requirements.txt

# 3. Install Node.js dependencies
npm install

# 4. Start both services
npm run dev
```

#### Available Commands

```bash
npm run dev              # Start frontend + backend together
npm run dev:frontend     # Start only frontend (port 3000)
npm run dev:backend      # Start only backend (port 8000)
npm run build            # Build frontend for production
npm run install:all      # Install all dependencies
npm run clean            # Clean all node_modules
```

### Access the Application

- **Frontend:** http://localhost:3000
- **Backend API:** http://localhost:8000

### Smart Contracts Deployment (Optional)

```bash
# Configure environment
cp .env.example .env
# Edit .env with your Algorand credentials

# Compile and deploy contracts
cd contracts
python compile.py
python deploy.py
```

---

## 📊 Success Metrics

### Year 1 Targets
- 👥 **10,000+** monthly active users
- 💰 **$50M+** quarterly trading volume
- 📈 **10%** market share of Polymarket volume
- 🏢 **15+** institutional clients

### Year 2 Targets
- 👥 **100,000+** monthly active users
- 💰 **$100M+** quarterly trading volume
- 🌍 **50+** countries with active users
- 🏆 **1000+** tournaments hosted

---

## 💡 Vision

**PolyGrand aims to become the prediction layer for Web3** - moving beyond being just another prediction market to becoming the essential infrastructure for:

- 📊 Decentralized forecasting
- 🏢 Corporate decision-making
- 🤖 AI benchmarking
- 📈 Financial derivatives
- 🎮 Gamified predictions

*All built on Algorand's scalable, efficient, and regulatory-friendly blockchain.*

> "We're not just building a better prediction market - we're creating the prediction economy of the future."

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Built with ❤️ on Algorand**

[⭐ Star us on GitHub](https://github.com/Ei-Sandi/PolyGrand)

</div>
