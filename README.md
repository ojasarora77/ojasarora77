# Ojas Arora
**Smart Contract Developer | Python & AI Engineer | DeFi Infrastructure**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ojas-arora-b62430231/)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=flat&logo=twitter&logoColor=white)](https://x.com/OjasArora77)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:ojas4jan@gmail.com)
[![Lyneth Labs](https://img.shields.io/badge/Lyneth_Labs-000000?style=flat&logo=ethereum&logoColor=white)](https://lyneth.ai)

---

## About

Software engineer with three years of production experience across smart contract development, Python data pipelines, and AI-powered automation. Previously build institutional vault infrastructure at [Orion Finance](https://orionfinance.ai/) and trust infrastructure for autonomous agents at [Lyneth Labs](https://lyneth.ai).

**Current Focus:** ERC4626/ERC7540 vault architecture, on-chain quantitative analysis, agentic AI systems, and decentralised trust infrastructure for autonomous agent economies.

---

## Projects & Startups

### Co-Founder | [Lyneth Labs](https://lyneth.ai)
*May 2025 - Present | Backed by $20K from Venice AI*

Building the trust infrastructure layer for autonomous AI agent economies on ERC-8004 registries.

- Designed a **Beta-Dirichlet reputation system** that models every agent as a probability distribution rather than a static score, with a Global Mixture Model that dynamically clusters agents into behavioural archetypes
- Built a **discrete-time dynamical trust engine** treating agent interactions as asymmetric virtual games with logarithmic economic weighting and a Zero-Trust Sybil-Filter
- Implemented **wallet clustering and anomaly detection** using on-chain metrics (balance history, wallet age, gas spend) to classify behavioural archetypes and detect coordinated attack signatures
- Deployed an **EigenTrust-inspired graph layer** for detecting Sybil cliques and collusion rings with formal security analysis proving manipulation resistance

[docs.lyneth.ai](https://docs.lyneth.ai) | [lyneth.ai](https://lyneth.ai)

---

## Experience

### Smart Contract Developer | [Orion Finance](https://orionfinance.ai/)
*November 2025 - June 2025*

Building ERC4626/ERC7540 vault infrastructure for institutional DeFi portfolio management.

- Developed modular vault factory with strategy adapters connecting to Uniswap, Morpho, Aave, Lido, and Yearn with UUPS proxy and upgradeable patterns
- Built **Python pipelines** using web3.py, pandas, and numpy to trace on-chain capital flows across Morpho Blue markets, identifying loan/collateral pairs, supply caps, and per-market liquidity depth
- Computed **Spearman correlation, Sharpe ratios, VaR, and maximum drawdown** across multi-protocol vault positions to surface hidden concentration risk
- Wrote **Dune Analytics SQL** to track vault activity, token flows, and stablecoin settlement patterns ([dune.com/orionfinance/sepolia](https://dune.com/orionfinance/sepolia))
- Optimised gas costs across deployment scenarios with comprehensive **Foundry** and **Hardhat** fuzz and invariant test suites

### Full Stack Developer | [Bond.credit](https://bond.credit/)
*August 2025 - November 2025*

Built crypto-native credit infrastructure for autonomous agents.

- Developed **Python** credit scoring algorithms processing agent transaction histories and wallet behaviour datasets via iExec TEE for privacy-preserving computation
- Built Solidity contracts for credit vaults and **agUSD stablecoin** minting against agent reputation scores anchored to ERC-8004 registries

### Full Stack Developer | [0em Labs](https://0emlabs.com/)
*June 2025 - September 2025*

Built stablecoin payment gateways and MCP marketplaces using Node.js, Cloudflare Workers, and WalletConnect, handling cross-chain token flows and automated payment pipelines.

### Full Stack Developer | [Tokunize](https://www.tokunize.com/)
*March 2025 - June 2025*

Built React.js/TypeScript frontend and Django/PostgreSQL backend for fractional real estate tokenisation with ERC3643 security token standards for regulatory compliance.

---

## Research

### Smart Contract Vulnerability Detection | University of Southampton
*Final Year Project, 2025-2026*

End-to-end Python ML pipeline for automated smart contract security analysis.

- Fine-tuned **BERT** classifier on 6,700+ Solidity contracts achieving **F1=0.996**; benchmarked **CodeBERT** QA span extractor against Qwen2.5-Coder 480B (zero-shot) and 7B LoRA fine-tuning
- Built full **Python training pipeline** using HuggingFace, PyTorch, and scikit-learn on Iridis HPC cluster (A100/L4 via SLURM) with LOTO cross-validation across 27 vulnerability categories
- Designed **three-stage automated audit pipeline**: BERT triage → CodeBERT span extraction → LLM root cause explanation via REST API, reducing manual review scope by ~80%
- Discovered **two genuine vulnerabilities** in Orion Finance production contracts: unguarded `setVault` (DoS vector) and missing Chainlink `answeredInRound` check — both disclosed and fixed

---

## Hackathons & Awards

**CodeGene** | Encode AI Hackathon 2025
🥇 1st Place Nethermind Bounty | AI-powered smart contract security platform that automatically generates and executes exploits to prove vulnerabilities. Evolved into Lyneth Labs.
[Live Demo](https://codegene-theta.vercel.app/) | [GitHub](https://github.com/ojasarora77/smart-contract-auditor)

**GuardFi** | Encode London AIxWeb3 2024
🏆 $3,500 in Bounties | Decentralised insurance using AI risk assessment and Flare cross-chain verification
[Live Demo](https://guardfi-clone-nextjs.vercel.app/) | [GitHub](https://github.com/manukj/GuardFi)

**AssetXchange** | ETH Oxford 2024
🏅 Main Track Winner | No-code platform for real-world asset tokenisation
[Live Demo](https://asset-x-change-frontend.vercel.app/) | [GitHub](https://github.com/ojasarora77/AssetXchange)

---

## Technical Skills

**Languages:** Python, Solidity, TypeScript, SQL, Java, Haskell

**AI & ML:** HuggingFace, PyTorch, scikit-learn, BERT, LLM API integration, Claude Code, Cursor

**Python & Data:** pandas, numpy, web3.py, scipy, data pipelines, REST APIs, Dune Analytics SQL

**Blockchain & DeFi:** Hardhat, Foundry, Ethers.js, OpenZeppelin, ERC20/ERC3643/ERC4626/ERC7540/ERC8004

**Backend & Web:** Django, Node.js, Next.js, React.js, Cloudflare Workers, PostgreSQL, Docker

**Infrastructure:** Git, Linux, Azure, SLURM/HPC, TEEs

---

## Education

**BSc Computer Science** | University of Southampton
*2023 - 2026*

Key modules: Algorithms, Machine Learning, Distributed Systems, Cyber Security, Databases

**Final Year Project:** End-to-end Python ML pipeline for smart contract vulnerability detection — fine-tuned BERT achieving F1=0.996 on 6,700+ contracts, with automated LLM API integration for root cause analysis on Iridis HPC infrastructure. Discovered two genuine production vulnerabilities.

---

## GitHub Stats

<div align="left">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ojasarora77&theme=dark&hide_border=true" height="165" alt="streak stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ojasarora77&theme=dark&hide_border=true&layout=compact" height="165" alt="language stats" />
</div>

---

## Connect

- 🌐 [lyneth.ai](https://lyneth.ai)
- 💼 [LinkedIn](https://www.linkedin.com/in/ojas-arora-b62430231/)
- 🐦 [Twitter/X](https://x.com/OjasArora77)
- 📧 [Email](mailto:ojas4jan@gmail.com)
