# Awesome Kaspa

A curated list of awesome Kaspa resources, tools, and projects.

## Index

- [Wallets](#wallets)
- [Development Tools](#development-tools)
- [Layer 2 Solutions](#layer-2-solutions)
- [Explorers](#explorers)
- [Mining](#mining)
- [Exchanges](#exchanges)
- [DeFi & DEX](#defi--dex)
- [KRC-20 & NFT Marketplaces](#krc-20--nft-marketplaces)
- [Analytics](#analytics)
- [Payment Solutions](#payment-solutions)
- [Bridges](#bridges)
- [ASIC Manufacturers](#asic-manufacturers)
- [News & Education](#news--education)
- [Tools & Utilities](#tools--utilities)
- [Communication & Social](#communication--social)
- [Gaming & Entertainment](#gaming--entertainment)
- [Jobs & Marketplace](#jobs--marketplace)
- [Merchandise](#merchandise)
- [Visualization & Educational](#visualization--educational)
- [Archive / Inactive Projects](#archive--inactive-projects)

---

### Wallets

#### Hardware Wallets

| Wallet | Description | Features | License |
|--------|-------------|----------|---------|
| [Ledger](https://www.ledger.com/) | Industry-leading cold wallet for multi-chain asset management | 15,000+ cryptocurrencies, Secure Element chip, Mobile/desktop apps, 50+ wallet integrations | Mixed (MIT/Proprietary) |
| [Tangem](https://tangem.com/) | Card wallet with EAL6+ security certification | Card form factor, EAL6+ certified, No battery, IP69K waterproof, 25-year warranty, Kaspa support | MIT |
| [OneKey](https://onekey.so/) | Open-source multi-chain hardware wallet | 5,000+ cryptocurrencies, EAL6+ secure elements, Multi-platform (desktop/mobile/web/extension), Open-source firmware | MIT |
| [SafePal](https://www.safepal.com/) | Multi-format non-custodial wallet suite | Hardware (S1/X1) + Mobile + Browser extension, Air-gapped QR transactions, Multi-chain, DeFi/NFT support | Open Source (GPL-v2) |
| [CoolWallet](https://www.coolwallet.io/) | Bluetooth-enabled card wallet | Card form factor, CC EAL6+ secure element, Kaspa support (Pro/Go), 30+ chains, Bluetooth connectivity | MIT |

#### Mobile Wallets

| Wallet | Description | Features | License |
|--------|-------------|----------|---------|
| [Kaspium](https://github.com/azbuky/kaspium_wallet) | Lightweight non-custodial Kaspa wallet for mobile | 12/24-word seed phrases, Android/iOS, Multi-language support, Open-source, Flutter-based | [MIT](https://github.com/azbuky/kaspium_wallet/blob/main/LICENSE) |
| [Kurncy](https://www.kurncy.com/) | Kaspa-native wallet with comprehensive token support | KRC-20/KRC-721/KNS support, HD wallets, Instant transactions, iOS/Android, Fiat on/off-ramp (upcoming) | Proprietary |
| [OKX Wallet](https://www.okx.com/web3) | Self-custodial multi-chain wallet with advanced trading | 130+ chains, DEX swaps (100+ pools), Staking, 1,000 sub-accounts, Biometric auth, Security audits | Proprietary |
| [CoinEx Wallet](https://www.coinex.com/wallet) | Decentralized multi-chain wallet with DeFi portal | 60+ blockchains, 1M+ tokens, DApp browser, NFT/DeFi/GameFi, Transaction accelerator, Self-custody | Proprietary |
| [NOW Wallet](https://walletnow.app/) | Non-custodial wallet with extensive crypto support | 70+ coins/1500+ tokens, Staking (BNB/TRX/SOL/ADA), NFT support (ETH/SOL), WalletConnect, GasFree USDT | Proprietary |
| [Math Wallet](https://mathwallet.org/) | Universal multi-platform Web3 wallet | 100-200+ blockchains, Kaspa support, Staking platform, Mobile/desktop/extension, dApp store | Proprietary |

#### Browser Extension Wallets

| Wallet | Description | Features | License |
|--------|-------------|----------|---------|
| [Kasware](https://github.com/kasware-wallet/extension) | First open-source browser extension wallet for Kaspa | Firefox/Chrome support, HD wallet, Kaspa-wasm powered, Open-source, Multi-browser | [MIT](https://github.com/kasware-wallet/extension/blob/main/LICENSE) |
| [Kastle](https://github.com/forbole/kastle) | Advanced browser wallet with comprehensive token support | KRC-20/KRC-721 management, Ledger integration, Biometric auth, KNS support, L1/L2 transactions, dApp connectivity | [BSL 1.1](https://github.com/forbole/kastle/blob/main/LICENSE) |
| [Ghost Wallet](https://www.ghostwallet.org/) | Open-source Chrome extension for Kaspa ecosystem | KRC20 mint/send/receive, Chainge integration, Non-custodial, Chrome only, Mobile apps (upcoming Feb 2025) | [GPL-3.0](https://github.com/argonmining/kat-gov-wallet/blob/main/LICENSE) |
| [Kaspian](https://github.com/KaffinPX/Kaspian) | Compact self-custodial wallet with merchant features | QR code payments, Merchant tools, Provider API, Multi-network support, Theme customization, Alpha stage | [GPL-3.0](https://github.com/KaffinPX/Kaspian/blob/main/LICENSE) |
| [Zelcore](https://zelcore.io/) | Multi-platform wallet with extensive blockchain support | 80+ blockchains/100,000+ tokens, Desktop/mobile/extension, Ledger/Trezor support, d2FA, WalletConnect, 1,200+ pairs swaps | Proprietary |

#### Web Wallets

| Wallet | Description | Features | License |
|--------|-------------|----------|---------|
| [Kaspacom Wallet](https://wallet.kaspa.com/) | Open-source web wallet integrated with Kaspa DeFi platform | L1/L2 support, DEX integration, NFT marketplace, KNS domains, Community-built, Open-source | [MIT](https://github.com/KASPACOM/kaspacom-web-wallet/blob/main/LICENSE) |
| [Kaspa NG](https://github.com/aspectron/kaspa-ng) | High-performance desktop wallet with full node capabilities | Built-in Rusty Kaspa node, BlockDAG visualizer, Multi-platform (Windows/Linux/MacOS), Rust-based security, Remote connectivity | [Open Source / Proprietary](https://github.com/aspectron/kaspa-ng/blob/master/LICENSE) |
| [Kaspanet](https://wallet.kaspanet.io/) | Simple browser-based web wallet for Kaspa | 12-word seed phrase, Browser local storage, Easy interface, Send/receive KAS, Web-based | [MIT](https://github.com/kaspanet/kaspa-web-wallet/blob/master/LICENSE) |
| [Kaspa Kold](https://kaskold.com/) | Air-gapped cold storage solution for maximum security | Air-gapped security, Offline transaction signing, Mnemonic phrase backup, Cold storage, Message signing | [GPL-2.0](https://github.com/peavey2787/KasKold/blob/main/LICENSE) |
| [KasKeeper](https://kaskeeper.vercel.app/) | KEF-backed Web3 wallet with advanced features | KRC20 support, Layer 2 testnet, Web/mobile/extension, KEF integration, Self-custodial | Proprietary |
| [DEX.cc Wallet](https://dex.cc/) | High-performance non-custodial wallet with DEX integration | 4,000+ TPS, $0.0000025 fees, Multi-account management, Sub-second finality, AMM swaps (upcoming) | Proprietary |
| [Guarda](https://guarda.com/) | Multi-platform wallet with extensive asset support | 70+ blockchains/400K tokens, Staking (up to 40% APY), Desktop/mobile/web/extension, Ledger support, Buy/swap | [GPL-3.0](https://github.com/guardaco/guarda-android-wallets/blob/develop/LICENSE) |
| [Coin Wallet](https://coin.space/) | Privacy-focused cross-platform wallet | 25+ cryptocurrencies, Built-in swaps, Hardware wallet support, No KYC, Tor access, Multi-platform sync | [MIT](https://github.com/CoinSpace/CoinSpace/blob/master/LICENSE) |
| [CoinRabbit](https://coinrabbit.io/) | All-in-one custodial wallet with lending services | 300+ cryptocurrencies, Custodial cold storage, Lending/borrowing, Swap features, Savings accounts, No verification | Proprietary |

#### Specialized Wallets

| Wallet | Description | Features | License |
|--------|-------------|----------|---------|
| [KSPR Bot](https://kspr-bot.xyz/) | Telegram-based all-in-one KRC20/KRC721 wallet | Telegram bot, KRC20/KRC721 operations, Batch minting, Built-in marketplace, Mobile access, 5% royalty system | Proprietary |
| [Atomik Wallet](https://github.com/Atomik-Global/atomik-wallet) | User-friendly cross-platform wallet (work in progress) | Ionic V8 framework, iOS/Android/Web, 10BPS ready, UI/UX focused, Experimental status, Biometric auth | [MIT](https://github.com/Atomik-Global/atomik-wallet/blob/main/LICENSE) |
| [KasPaper](https://github.com/svarogg/kaspaper) | Lightweight paper wallet generator for cold storage | Go-based generator, Customizable HTML templates, Print-ready output, Offline usage, Paper wallet creation | [GPL-3.0](https://github.com/svarogg/kaspaper/blob/master/LICENSE) |

[⬆ Back to Index](#index)

---

### Development Tools

#### Core Libraries & Node Implementation

| Repository | Description | Features | License | Socials |
|------------|-------------|----------|---------|---------|
| [Rusty Kaspa](https://github.com/kaspanet/rusty-kaspa) | Official Rust full-node implementation | Full-node, RPC (JSON/Borsh), UTXO indexing, WASM SDK, 10 BPS Crescendo support, Mining, Mainnet/testnet/devnet | [ISC](https://github.com/kaspanet/rusty-kaspa/blob/master/LICENSE) |  |
| [Kaspa-JS](https://github.com/K-Kluster/kaspa-js) | TypeScript SDK monorepo for Kaspa development | Address encoding/decoding, Schnorr signatures, Sign-In with Kaspa (SIWK), CLI starter kit, Node.js v20+ | [ISC](https://github.com/K-Kluster/kaspa-js/blob/main/LICENSE) | [Discord](https://discord.gg/vuKyjtRGKB) |
| [WASM32 SDK](https://kaspa.aspectron.org/docs/index.html) | WebAssembly bindings for JavaScript/TypeScript | Browser/Node.js/Bun compatible, Wallet SDK, RPC API, Transaction generation, MV3 extension support | [ISC](https://github.com/kaspanet/rusty-kaspa/blob/master/LICENSE) | [X](https://x.com/CryptoAspect) |
| [Kdapp](https://github.com/michaelsutton/kdapp) | High-frequency interactive dApp framework | Rust-based, BlockDAG optimization, Interactive dApps, High-frequency transactions | [ISC](https://github.com/michaelsutton/kdapp/blob/main/LICENSE) | [X](https://x.com/michaelsuttonil) |
| [Kaspeak SDK](https://github.com/kaspeak/kaspeak-sdk) | SDK for decentralized applications with crypto features | Text/binary data transfer, Custom message types, ECDH/XChaCha20/Schnorr crypto, CBOR/Zstandard compression | [MIT](https://github.com/kaspeak/kaspeak-sdk/blob/main/LICENSE) | [X](https://x.com/KaspeakOfficial)<br>[Telegram](https://t.me/kaspeak_en) |

#### APIs & Services

| Service | Description | Features | License | Socials |
|---------|-------------|----------|---------|---------|
| [REST-API](https://github.com/kaspa-ng/kaspa-rest-server) | HTTP REST API server for Kaspa network | Python-based, HTTP methods, Swagger docs at api.kaspa.org, Standard REST endpoints | MIT |  |
| [Kasplex API](https://docs-kasplex.gitbook.io/krc20) | Open-source indexer and API for KRC-20/KRC-721 data | Protocol + Indexer + API, Mainnet/testnet endpoints, Open-source, Self-hostable | Proprietary | [X](https://x.com/Kasplex)<br>[Telegram](https://t.me/kasplex_official) |
| [NOWNodes](https://nownodes.io/) | Professional blockchain API provider | 100+ blockchains, 99.95% uptime, 15K+ TPS, WebSocket support, 24/7 support, Free trial | Proprietary |  |

#### Development Utilities

| Tool | Description | Features | License | Socials |
|------|-------------|----------|---------|---------|
| [Simply Kaspa Indexer](https://hub.docker.com/r/supertypo/simply-kaspa-indexer) | PostgreSQL indexer optimized for concurrency | Docker container, PostgreSQL backend, Concurrent processing, kaspa-rest-server integration | [MIT](https://github.com/argonmining/simply-kaspa-indexer/blob/main/LICENSE) |  |
| [KasPush](https://github.com/kas-builder/KasPush_) | Wallet balance tracker with push notifications | HTML/JavaScript, iOS push notifications, Balance tracking, Mobile alerts | [MIT](https://github.com/kas-builder/KasPush_/blob/main/LICENSE) |  |
| [Kaspa Register](https://github.com/laudena/kaspa_register) | NFC point-of-sale payment request system | Flask app, NFC support, Payment URIs, POS integration | Unlicensed |  |
| [Kasmage](https://github.com/ethanvillalobos8/kasmage) | CLI monitoring tool for transaction alerts | Command-line interface, Live transaction monitoring, Alert system, Python-based | [MIT](https://github.com/ethanvillalobos8/kasmage/blob/main/LICENSE) |  |
| [BLanim](https://github.com/ShaiW/blanim) | BlockDAG animation visualization library | Python/Manim extension, BlockDAG animations, Educational visualizations, Open-source | [MIT](https://github.com/ShaiW/blanim/blob/main/LICENSE) |  |


[⬆ Back to Index](#index)

---

### Layer 2 Solutions

| Project | Description | Features | License | Socials |
|---------|-------------|----------|---------|---------|
| [Igra Network](https://igralabs.com) | EVM-compatible based ZK rollup on Kaspa | Based ZK rollup, 3,000+ TPS, Sub-second finality, MEV-resistant, EVM tools compatible, Decentralized sequencer | Proprietary | [X](https://x.com/Igra_Labs)<br>[Discord]([https://discord.com/invite/igralabs](https://discord.gg/igralabs)) |
| [Kasplex L2](https://kasplex.org/) | zkEVM Layer 2 with smart contracts for Kaspa | Full EVM compatibility, $KAS gas token, PLONK zk-SNARKs, Based rollup, GHOSTDAG integration, Mainnet Aug 31 2025 | Proprietary | [X](https://x.com/Kasplex)<br>[Telegram](https://t.me/kasplex) |

[⬆ Back to Index](#index)

---

### Visualization & Educational

| Project | Description | Features | License | Socials |
|---------|-------------|----------|---------|---------|
| [Kaspa Graph Inspector](https://github.com/kaspa-live/kaspa-graph-inspector) | Interactive real-time BlockDAG visualization | Go/Node.js, Real-time DAG display, Network dynamics, Graph analysis tools, Live block visualization | Unlicensed |  |
| [ChainVsDag](https://chainvsdag.com/) | 3D comparison visualization tool | 3D embeddable visualization, Blockchain vs BlockDAG comparison, Interactive demo | Proprietary |  |
| [TX Missile Command](https://tx-missile-command.com/) | Educational blockchain game | Transaction visualization game, Real-time tx flow, Educational gameplay, BlockDAG learning tool | Proprietary |  |

[⬆ Back to Index](#index)

---

### Explorers

| Explorer | Description | Features | License | Socials |
|----------|-------------|----------|---------|---------|
| [Kaspa Explorer](https://explorer.kaspa.org/) | Official open-source blockchain explorer | Real-time blocks, Transaction tracking, Address queries, Network metrics, Open-source | Open Source |  |
| [Kaspa.Stream](https://kaspa.stream/) | Advanced block explorer with real-time data | Real-time block data, Transaction analysis, Advanced filtering, Live updates | Proprietary |  |
| [Kasplore](https://www.kasplore.com/) | Comprehensive explorer with token support | Block exploration, KRC20 tokens, Transaction search, Address lookup | Proprietary |  |
| [Kasplex Explorer](https://explorer.kasplex.org/) | Official Kasplex Layer 2 explorer | L2 blockchain data, Smart contract tracking, zkEVM support, L2 transactions | Open Source | [X](https://x.com/Kasplex)<br>[Telegram](https://t.me/kasplex_official) |
| [DagScan](https://www.dagscan.xyz/) | L2 explorer with DeFi analytics | Token analytics, Pool data, dApp tracking, DeFi metrics, L2 focus | Proprietary |  |
| [Kaspa Scope](https://www.kaspascope.com/) | Market-integrated explorer platform | Real-time market data, Price charts, Block explorer, Market integration | Proprietary |  |
| [KaspaWave](https://kaspawave.com/) | Community wallet tracking platform | Wallet monitoring, KRC20 tracking, Portfolio view, Community features | Proprietary |  |
| [Look into Kaspa](https://www.lookintokaspa.com/) | Network interaction and visualization platform | Mempool visualizer, Network stats, DAG visualization, Interactive UI | Proprietary |  |
| [kaspa-explorer](https://github.com/lAmeR1/kaspa-explorer) | React.js open-source explorer | React-based, Block exploration, Transaction search, Open-source, Modern UI | Open Source |  |

[⬆ Back to Index](#index)

---

### Mining

#### Mining Pools

| Pool | Description | Features |
|------|-------------|----------|
| [WoolyPooly](https://woolypooly.com/en/coin/kas) | Major multi-coin mining pool | 0.9% fees, High hashrate, Efficient performance, Auto-payouts, Global servers |
| [KaspaPool](https://kaspa-pool.org/) | Kaspa-optimized mining pool | PPLNS payout system, SOLO mining, Pool statistics, Low latency |
| [kNodes](https://kaspa-nodes.org/) | Free solo mining platform | 0% fees, Solo mining focus, No registration, Community-driven, Free service |
| [Kat Pool](https://katpool.xyz/) | Open-source community mining pool | Open-source code, Community-driven, Transparent operations, Fair distribution |
| [HeroMiners](https://kaspa.herominers.com/) | Established multi-coin pool | Reliable payouts, Low fees, Global servers, Proven track record |
| [f2pool](https://www.f2pool.com/) | Major global mining pool | Consistent payouts, Established since 2013, Multi-coin support, Enterprise-grade |

[⬆ Back to Index](#index)

---

### Exchanges

#### Centralized Exchanges (CEX)

| Exchange | Description | Features |
|----------|-------------|----------|
| [Kraken](https://www.kraken.com/) | US-based major exchange (Est. 2011) | Spot/Futures trading, Apple Pay, Fiat on-ramp, Regulated, High liquidity |
| [Bybit](https://www.bybit.com/) | UAE-based derivatives exchange (Est. 2018) | Spot/Futures/Derivatives, High leverage, Trading bots, Copy trading |
| [KuCoin](https://www.kucoin.com/) | Seychelles exchange (Est. 2017) | Spot/Futures/Margin, 700+ coins, Trading bots, Lending |
| [Gate.io](https://www.gate.io/) | Comprehensive trading platform | Spot/Futures/Margin, 1400+ coins, Copy trading, NFT marketplace |
| [MEXC Global](https://www.mexc.com/) | Major centralized exchange | Spot/Futures, New token listings, Low fees, Global access |
| [Bitget](https://www.bitget.com/) | Trading platform with derivatives | Spot/Futures, Copy trading, Trading bots, Launchpad |
| [HTX](https://www.htx.com/) | Global cryptocurrency exchange | Spot/Futures, 500+ coins, Staking, Derivatives |
| [Uphold](https://uphold.com/) | US platform for crypto/fiat/metals (Est. 2013) | Multi-asset trading, Fiat support, Regulated, Metals trading |
| [WhiteBIT](https://whitebit.com/) | EU-regulated Lithuanian exchange (Est. 2018) | High volume, Spot trading, Fiat on-ramp, EU compliance |
| [Poloniex](https://poloniex.com/) | Established cryptocurrency exchange | Spot/Margin trading, Futures, Lending, Staking |
| [CoinEx](https://www.coinex.com/) | Global crypto exchange | Spot/Margin/Perpetual, AMM, Low fees, Auto-Market Maker |
| [CoinW](https://www.coinw.com/) | Cryptocurrency trading platform | Spot trading, Futures, Margin, Copy trading |
| [BingX](https://bingx.com/) | Exchange with social trading | Spot/Copy trading, Social features, Grid trading, Bots |
| [Bitpanda](https://www.bitpanda.com/) | European cryptocurrency platform | Spot/Staking, Fiat support, EU regulated, Savings plans |
| [Bitrue](https://www.bitrue.com/) | Digital asset exchange | Spot trading, Yield farming, Lending, Power Piggy |

#### Instant Swap & No-KYC Platforms

| Platform | Description | Features |
|----------|-------------|----------|
| [ChangeNOW](https://changenow.io/) | Non-custodial exchange (Est. 2017) | Instant swaps, No KYC, No registration, 500+ coins, API access |
| [SimpleSwap](https://simpleswap.io/) | Instant no-KYC exchange (Est. 2018) | 1500+ cryptos, Loyalty program, No sign-up, Simple UI |
| [Changelly](https://changelly.com/) | Exchange with fiat on-ramp (Est. 2015) | 1000+ cryptos, Fiat purchasing, Mobile app, Buy crypto |
| [StealthEX](https://stealthex.io/) | Privacy-focused exchange (Est. 2018) | 1400+ cryptos, No KYC, Anonymous, Fixed/floating rates |
| [ChangeHero](https://changehero.io/) | Fast non-custodial exchange | 200+ cryptos, Fast swaps, No custody, Competitive rates |
| [Exolix](https://exolix.com/) | Anonymous exchange | 2000+ cryptos, Fixed/floating rates, Anonymous, No limits |
| [Quickex](https://quickex.io/) | Cryptocurrency exchange (Est. 2018) | Hundreds of altcoins, Quick swaps, No registration |
| [Swapzone](https://swapzone.io/) | Non-custodial aggregator | 1000+ cryptos, 18+ services aggregated, Rate comparison |
| [SwapSpace](https://swapspace.co/) | Exchange aggregator | 440+ cryptocurrencies, Best rates, No account, Multiple sources |
| [RocketX](https://www.rocketx.exchange/) | Cross-chain exchange | Multi-chain swaps, Liquidity aggregation, Best execution |
| [LetsExchange](https://letsexchange.io/) | Crypto-to-crypto exchange | Instant swaps, 3500+ pairs, Cashback, No limits |
| [CoinoSwap](https://www.coinoswap.com/) | Non-custodial aggregator | No registration, Best rates, Aggregator, Non-custodial |
| [HoudiniSwap](https://houdiniswap.com/) | Privacy-focused Monero swaps | Monero integration, Anonymous, Cross-chain, Privacy-first |
| [Swyftx](https://swyftx.com/) | Australian crypto exchange | 440+ cryptos, Recurring buys, Stop-loss, Tax reports, AU regulated |
| [Kriptomat](https://kriptomat.io/) | European exchange (Estonia) | 350+ cryptocurrencies, EU regulated, Staking, Fiat support |
| [Nexo](https://nexo.com/) | Digital asset platform | Buy/Earn/Borrow/Trade, Interest accounts, Crypto loans, Credit card |
| [Digital Surge](https://digitalsurge.com.au/) | Australian exchange | 400+ cryptocurrencies, AU regulated, Fiat gateway, Recurring buys |

[⬆ Back to Index](#index)

---

### DeFi & DEX

| Platform | Description | Features |
|----------|-------------|----------|
| [KaspaCom](https://kaspa.com/) | Leading all-in-one DeFi platform on Kaspa | DEX swaps, Lending/Borrowing, NFT marketplace, Token launchpad (LFG.KASPA), KNS domains, Web wallet |
| [ZealousSwap](https://www.zealousswap.com/) | First AMM DEX on Kasplex L2 | Uniswap V2 model, Token swaps, Liquidity provision, Yield farming, L2 native |
| [Kaspa Finance](https://kaspafinance.io/) | Multi-feature DeFi platform | DEX swaps, Liquidity farms, Lending protocols, AI trading tools, Analytics |
| [KSPR DEX](https://app.kspr.exchange/) | DEX and launchpad on Kasplex L2 | Trading platform, Token launches, IDO platform, L2 integration |
| [KRChange](https://krchange.com/) | Premier KRC20 exchange for L1 | L1 token trading, KRC20 swaps, Order book, Trading pairs |
| [Fervent Finance](https://www.fervent.finance/) | First lending/borrowing platform on Kaspa | Lending pools, Borrowing against collateral, Interest rates, Risk management |
| [SeaSwap](https://seaswap.xyz/) | DEX aggregator for best rates | Trade routing optimization, Multi-DEX aggregation, Best price discovery, Slippage protection |
| [Kaskad](https://www.kaskad.app/) | Decentralized lending and borrowing | Collateralized loans, Variable rates, Liquidation system, Risk pools |
| [KYO](https://kyocard.app/) | Crypto payment card service | Pay with crypto, Instant credit, Card payments, No selling required |
| [DEX.cc](https://dex.cc/) | Full-featured DEX with wallet | AMM swaps, Non-custodial wallet, 4K+ TPS, Perpetuals (upcoming), Hashrate derivatives |

[⬆ Back to Index](#index)

---

### KRC-20 & NFT Marketplaces

| Platform | Description | Features | License | Socials |
|----------|-------------|----------|---------|---------|
| [KaspaCom Marketplace](https://kaspa.com/) | Integrated NFT marketplace in KaspaCom DeFi | NFT trading, Yonatoshi holder benefits, Lifetime fee discounts, DeFi integration | Proprietary |  |
| [Spectre Market](https://spectre.market/) | Premier L2 NFT marketplace on Igra Network | L2 NFT trading, Igra integration, Layer 2 speed, Low fees | Proprietary |  |
| [Kasplex Protocol](https://kasplex.org/) | Open-source KRC-20/721 protocol | Data insertion, Open-source indexer, Public APIs, Token standards (KRC-20/721) | Open Source | [X](https://x.com/Kasplex)<br>[Telegram](https://t.me/kasplex_official) |
| [KNS](https://app.knsdomains.org/) | Kaspa Name Service for domains | Domain registration, Name resolution, Secure management, Human-readable addresses | Proprietary |  |
| [Gemlaunch](https://gemlaunch.fun/) | No-code token launchpad | Token creation, Fair launches, No coding, Community launches | Proprietary |  |
| [KRC-20.org](https://krc-20.org/) | KRC-20 token explorer app | Token exploration, Portfolio tracking, Token analytics, Price data | Proprietary |  |

[⬆ Back to Index](#index)

---

### Analytics

| Platform | Description | Features | License | Socials |
|----------|-------------|----------|---------|---------|
| [Kaspalytics](https://www.kaspalytics.com/) | On-DAG network analysis platform | Hashrate data, Difficulty metrics, HODL tools, Network statistics, DAG analytics | Proprietary |  |
| [KaspHub](https://kasphub.com/) | Comprehensive metrics dashboard | Mining calculator, Network analysis, Performance metrics, Real-time data | Proprietary |  |
| [Kaspa Insights](https://www.kaspainsights.com/) | Network insights and analytics platform | Network insights, Performance metrics, Analytics dashboard, Trend analysis | Proprietary |  |

[⬆ Back to Index](#index)

---

### Payment Solutions

#### Payment Gateways & Processors

| Service | Description | Features | License | Socials |
|---------|-------------|----------|---------|---------|
| [NOWPayments](https://nowpayments.io/supported-coins/kas-payments) | Crypto payment gateway for e-commerce | API integration, Plugins, Invoices, Widgets, Donations, E-commerce/gaming | Proprietary |  |
| [CoinPal](https://www.coinpal.io/) | Merchant payment solution | Low-fee payments, Multi-currency conversion, Merchant tools | Proprietary |  |
| [Cryptocurrency Checkout](https://cryptocurrencycheckout.com/) | Non-custodial decentralized gateway | Multi-crypto support, Plugins, Non-custodial, Decentralized | Open Source |  |
| [Kaspa Hub Merchant Solutions](https://kaspahub.org/solutions/) | Business payment integration | Online payments, In-store POS, Donation pages, Business tools | Proprietary | [Discord](https://discord.com/invite/7umFvjcANE) |
| [Kaspapay](https://github.com/Kasplabs/Kaspapay) | Open-source payment gateway | Self-hosted, Full control, Open-source, Developer-friendly | Open Source |  |

#### Fiat On-Ramps

| Service | Description | Features | License | Socials |
|---------|-------------|----------|---------|---------|
| [Topper](https://www.topperpay.com/) | Uphold-powered fiat on-ramp | 200+ cryptocurrencies, Debit/Credit cards, Digital wallets, Multiple payment methods | Proprietary |  |
| [Simplex](https://www.simplex.com/) | Fiat-to-crypto on-ramp | Credit cards, Bank transfers, Global coverage, Regulated | Proprietary |  |
| [Onramp Money](https://onramp.money/) | Kaspa fiat on-ramp | Wallet integration, Fiat purchasing, Easy integration, Kaspa-focused | Proprietary |  |
| [Guardarian](https://guardarian.com/) | Fiat on/off ramp service | 1000+ cryptocurrencies, Competitive rates, Buy/sell, Multiple payment methods | Proprietary |  |

#### Donation Platforms

| Platform | Description | Features | License | Socials |
|----------|-------------|----------|---------|---------|
| [kas.coffee](https://kas.coffee/) | Personalized donation pages | Custom themes, QR codes, Creator pages, Customizable | Proprietary |  |
| [KaspaHub Donation Pages](https://kaspahub.org/nostr/register/) | Creator/streamer donation pages | Easy setup, Customizable, Nostr integration, Creator-friendly | Proprietary | [Discord](https://discord.com/invite/7umFvjcANE) |
| [Kaspa Donations Extension](https://kaspahub.org/kaspa-donations/) | Browser extension for donations | Meta tag integration, Easy implementation, Website integration, Browser extension | Open Source | [Discord](https://discord.com/invite/7umFvjcANE) |
| [KaspaTips](https://www.kaspatips.com/) | Expiring tip pages | Time-limited tips, QR generation, Expiring links, Tipping system | Proprietary |  |

[⬆ Back to Index](#index)

---

### Bridges

| Bridge | Description | Features | License | Socials |
|--------|-------------|----------|---------|---------|
| [Multi-Chain EVM Bridge](https://kaspa.org/) | Cross-chain bridge for Kaspa to EVM networks | 30-40 network support, BNB Chain integration, Multi-chain bridging, EVM compatible | Proprietary |  |
| [RocketX](https://www.rocketx.exchange/) | Cross-chain exchange and bridge | ETH to KAS conversion, Multi-chain swaps, Cross-chain exchange, Liquidity aggregation | Proprietary |  |

[⬆ Back to Index](#index)

---

### ASIC Manufacturers

| Manufacturer | Description | Features |
|--------------|-------------|----------|
| [Bitmain](https://www.bitmain.com/) | Leading ASIC manufacturer with multiple KHeavyHash miners | Antminer KS3 (9.4Th/s), KS5 Pro (21Th/s), KS7 (40Th/s), Global distribution |
| [IceRiver](https://iceriver.io/) | ASIC manufacturer specializing in Kaspa mining hardware | KS2 (20Th/s), KS7 (30Th/s), Efficient cooling systems |
| [Goldshell](https://www.goldshell.com/) | ASIC mining hardware manufacturer | KA Box (1.18Th/s 400W), KA Box Pro (1.6Th/s 600W), E-KA1M (5.5Th/s 1800W), Compact designs |

[⬆ Back to Index](#index)

---

### News & Education

| Platform | Description | Features | Socials |
|----------|-------------|----------|---------|
| [Kaspa.org](https://kaspa.org/) | Official community website | Comprehensive information, Official resources, Getting started guides, Documentation |  |
| [KASmedia](https://www.kasmedia.com/) | Kaspa media outlet | Research articles, Market analysis, News coverage, In-depth reports |  |
| [Kaspa News](https://kaspa.news/) | Real-time news aggregator | News aggregation, Real-time updates, Dashboard, Multi-source |  |
| [Kaspa Wiki](https://wiki.kaspa.org/) | Comprehensive documentation | Guides, How-tos, Technical docs, Beginner-friendly |  |
| [Kaspa Research](https://research.kas.pa/) | Technical discussion platform | Consensus discussions, Mining topics, Privacy research, Community-driven |  |
| [Kaspa Q&A](https://qa.kas.pa/) | Community Q&A platform | Community support, Knowledge base, FAQ, User questions |  |
| [KaspArchive](https://kasparchive.com/) | Factual information resource | Historical data, Facts, Archive, Reference material |  |
| [Kaspa Daily](https://kaspadaily.com/) | Daily news and L2 updates | Daily news, Layer-2 developments, Updates, Blog |  |
| [Kasbun](https://www.kasbun.com/) | Kaspa insights blog | Blog posts, Insights, Analysis, Commentary |  |
| [Kaspa FAQ](https://www.kaspafaq.com/) | Comprehensive FAQ resource | Wallets, Exchanges, Tokens, Beginner guides, Detailed answers |  |
| [Kaspa Flow](https://kaspaflow.com/) | Brazilian Kaspa community | Portuguese community, Events, Education, BR-focused |  |

[⬆ Back to Index](#index)

---

### Tools & Utilities

| Tool | Description | Features | License | Socials |
|------|-------------|----------|---------|---------|
| [MyKai](https://mykai.app/) | Beginner-friendly AI assistant | AI assistance, User guidance, Kaspa queries, Beginner-friendly | Proprietary |  |
| [KasMap](https://kasmap.org/) | Merchant discovery platform | Merchant finder, Real-world adoption tracking, Map interface, KAS acceptance | Proprietary |  |
| [Kaspa Map](https://kaspamap.com/) | Payment locations map | Merchant locations, Payment acceptance, Interactive map, Global coverage | Proprietary |  |
| [The Business Directory](https://tbd.directory/) | Decentralized B2B directory | Business directory, AI-powered, B2B connections, On-chain | Proprietary |  |
| [KasLens](https://kaspa-lens.com/) | AI market analysis tool | Real-time analysis, AI insights, Market data, Price tracking | Proprietary |  |
| [Kaspa Security Center](https://kaspasecuritycenter.com/) | Community security initiative | Security reporting, Incident tracking, Community protection, Transparency | Proprietary |  |
| [KasBay](https://kasbay.org/) | Comprehensive resource hub | Project directory, dApp listing, Resource aggregation, Community hub | Proprietary |  |
| [KasStamp](https://kasstamp.com/) | Digital artifact stamping | On-chain stamping, Verification, Digital artifacts, Open-source | Open Source |  |
| [KasProve](https://kasprove.pages.dev/) | Digital signature service | Signature inscription, Verification, Proof of existence, On-chain | Open Source |  |
| [Kaspa Life](https://www.kaspalife.org/) | Social media content creator | Content creation, Social media templates, Marketing materials, Community tools | Proprietary |  |
| [Kaspa Globe](https://kaspaglo.be/) | Network visualization globe | Interactive 3D globe, Network peers, Real-time visualization, Global nodes | Proprietary |  |
| [Kaspa Node Map](https://nodes.kaspa.ws/) | Public node map | Node discovery, Real-time data, Node locations, Network health | Proprietary |  |
| [Kaspa.Host](https://kaspa.host/) | Node connectivity tester | P2P-gRPC testing, Accessibility checks, Node diagnostics, Connection testing | Proprietary |  |
| [Kaspa Network Hashrate](https://hashrate.kaspa.ws/) | Hashrate visualization | Hashrate tracking, Charts/graphs, Network health, Historical data | Proprietary |  |
| [Kaspa Address Labels](https://labels.kaspa.ws/) | Address labeling tool | Public labels, Address transparency, Wallet identification, Community-driven | Proprietary |  |

[⬆ Back to Index](#index)

---

### Communication & Social

| Platform | Description | Features | License | Socials |
|----------|-------------|----------|---------|---------|
| [Kasia](https://github.com/K-Kluster/Kasia) | P2P encrypted messaging on Kaspa L1 | E2E encryption, Decentralized, On-chain messaging, Privacy-focused, No central server | [ISC](https://github.com/K-Kluster/Kasia/blob/main/LICENSE) | [Discord](https://discord.gg/vuKyjtRGKB) |
| [K](https://ksocialnetwork.pages.dev/) | Decentralized microblogging | GHOSTDAG-powered, Censorship-resistant, Ultra-low cost (~0.00002 KAS), Transparency, On-chain social | Proprietary |  |
| [Kaspeak](https://kaspeak.net/) | Decentralized messenger | On-Kaspa messaging, Decentralized architecture, Private communication, SDK integration | Proprietary | [X](https://x.com/KaspeakOfficial)<br>[Telegram](https://t.me/kaspeak_en) |
| [Kaspa Tipbot](https://kaspa-bot.com/) | Reddit tipping bot | Non-custodial, r/Kaspa integration, Tipping system, Reddit bot, Community rewards | Proprietary |  |

[⬆ Back to Index](#index)

---

### Gaming & Entertainment

| Project | Description | Features | License | Socials |
|---------|-------------|----------|---------|---------|
| [Vivoor](https://vivoor.xyz/) | Kaspa-powered streaming platform | Kaspa payments, Streaming platform, Content monetization, Creator rewards | Proprietary |  |
| [KasPixel](https://kaspixel.xyz/) | Collaborative pixel art canvas | r/place-inspired, Collaborative art, Pixel drawing, Community creation, Interactive canvas | Proprietary |  |
| [TX Missile Command](https://tx-missile-command.com/) | Educational blockchain arcade game | Real Kaspa transactions, Arcade gameplay, Transaction visualization, Educational | Proprietary |  |
| [PPKAS](https://ppkas.space/) | Play-to-earn gaming platform | KRC-20 token, Play-to-earn mechanics, Gaming app, Rewards system | Proprietary |  |
| [Kasplay.fun](https://kasplay.fun) | Web3 arcade storing game scores directly in Kaspa BlockDAG | Real on-chain transactions, Ultra-fast confirmation, No wallet required, Data layer demo | Proprietary |  |


[⬆ Back to Index](#index)

---

### Jobs & Marketplace

| Platform | Description | Features | Socials |
|----------|-------------|----------|---------|
| [Proof of Works](https://www.proofofworks.com/) | First fully on-chain job platform on Kaspa | On-chain hiring & payroll, Smart contract job management, Immutable reputation system, DAO dispute resolution, ZK-Resume privacy module, Automatic KAS payouts | [X](https://x.com/ProofOfWorksKAS)<br>[Telegram](https://t.me/+WxraM9RZITBlNDhh) |
| [TheCryptoSky](https://thecryptosky.com/) | Marketplace for goods, services, and jobs in KAS | Real-time transaction insights, KAS payments, Marketplace listings, Job board, Community marketplace |  |
| [KaspaJobs](https://kaspajobs.com/) | First job board built for Kaspa blockchain | 100% crypto payments, Trustless hiring, Freelance & full-time jobs, Developer/designer/writer/marketer categories, Direct KAS compensation |  |
| [KaspaTaxi](https://kaspataxi.kasperience.xyz/) | Decentralized ride-booking service | Blockchain-based ride-booking, Kaspa payments, Decentralized transportation platform |  |

[⬆ Back to Index](#index)

---

### Merchandise

| Store | Description | Features | Socials |
|-------|-------------|----------|---------|
| [Rock The Kaspa](https://www.rockthekaspa.com/) | Kaspa-themed clothing and apparel | T-shirts/hoodies/accessories, KAS payment support, 10% profits to CMF, Multiple payment methods, Baby/youth apparel, Embroidered items | [X](https://x.com/rock_the_kaspa) |
| [Proof of Prints](https://proofofprints.com/) | 3D printing for crypto projects | Kaspa 3D printed items, Custom designs, Collectible models, Etsy-based store |  |
| [Kascoin Shop](https://kascoin.shop/) | Hand-poured unique collectible Kaspa coins | Hand-poured metal coins, Copper/tin & silver variants, Limited/numbered editions, Custom patina finishes, NowPayments & QR code KAS payments | [X](https://x.com/Burke1Dong) |
| [KaspaShirts](https://kaspashirts.com/) | Kaspa-themed apparel in sizes S-5XL | Spreadshop platform, Multiple size options (S-5XL), Kaspa pride apparel, Various merchandise items |  |
| [KaspaBuy](https://kaspabuy.shop/) | First e-commerce platform with direct KAS payments | Direct $KAS payment support, Live price display, 7 product categories, Apparel/jewelry/tech accessories, CoinGecko API integration |  |
| [SLOWLIKEBTC](https://slowlikebtc.printify.me/) | Print-on-demand crypto apparel | 52+ items, Printify platform, Apparel/drinkware/accessories, Personalization options, Turtle mascot branding, Multiple payment methods |  |

[⬆ Back to Index](#index)

---

### Visualization & Educational

| Repository | Description | License |
|------------|-------------|---------|
| [Kaspa Graph Inspector](https://github.com/kaspa-live/kaspa-graph-inspector) | Interactive real-time visualization of Kaspa's BlockDAG with network dynamics and graph analysis tools | Unlicensed |

[⬆ Back to Index](#index)

---

## Archive / Inactive Projects

*Projects listed here had inactive or unreachable websites at the time of archival. They may return to the active list if they become available again.*

### Archived Wallets

| Wallet | Description | Features | License | Status |
|--------|-------------|----------|---------|--------|
| [Unity Wallet](https://unitywallet.app/) | Multi-chain Web3 gateway with AI features | AI assistant, Kaspa/NEAR/Cosmos support, WalletConnect, Sub-accounts, KYT risk assessments | Proprietary | Website unreachable (timeout) |

### Archived Marketplaces

| Platform | Description | Features | License | Status |
|----------|-------------|----------|---------|--------|
| [kNFT](https://knft.io/) | Dedicated Kaspa NFT exchange | NFT minting/trading, Fast confirmations, Low fees, Kaspa native | Proprietary | Website unreachable (redirect loop) |

### Archived Bridges

| Project | Description | Features | License | Status |
|---------|-------------|----------|---------|--------|
| [Wrapped Kaspa (wKAS)](https://wkas.org/) | Wrapped KAS token bridge for DeFi | Ethereum/BNB Chain, wKAS token standard, Cross-chain DeFi access, ERC-20 compatible | Proprietary | Website unreachable (DNS failure) |

### Archived Communication

| Platform | Description | Features | License | Status |
|----------|-------------|----------|---------|--------|
| [Verum](https://verumonkas.com/) | Decentralized social network | Social platform, Decentralized, Community-driven, Kaspa-based | Proprietary | Website unreachable (timeout) |

[⬆ Back to Index](#index)

---

## Credits & Acknowledgments

### Primary Data Sources

**[KaspaHub.org](https://kaspahub.org/)**
- Comprehensive Kaspa ecosystem directory
- Primary source for project discovery and categorization
- Licensed under MIT License

**Individual Project Repositories**
- GitHub repositories verified for accurate license information
- Project websites for descriptions and features

### Community

This resource list is built by and for the Kaspa community. Special thanks to:

- **All Kaspa project developers and maintainers** - For building an incredible ecosystem
- **The KaspaHub team** - For maintaining the comprehensive ecosystem directory
- **Contributors to this awesome-list** - For helping keep this resource up-to-date
- **The broader Kaspa community** - For fostering innovation and collaboration

### Note

This is a community-maintained directory. While we strive for accuracy, we cannot guarantee the security, reliability, or current status of listed projects. Always do your own research before using any service or application.

To add your project or suggest improvements, please see the [Contributing](#contributing) section below.

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

To add your project:
1. Fork this repository
2. Add your project in the appropriate category
3. Follow the format: `| [Project Name](URL) | Description | [License](License URL) |`
4. Submit a Pull Request

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
