<!-- BlackRoad SEO Enhanced -->

# ulackroad apps

> Part of **[BlackRoad OS](https://blackroad.io)** — Sovereign Computing for Everyone

[![BlackRoad OS](https://img.shields.io/badge/BlackRoad-OS-ff1d6c?style=for-the-badge)](https://blackroad.io)
[![BlackRoad Forge](https://img.shields.io/badge/Org-BlackRoad-Forge-2979ff?style=for-the-badge)](https://github.com/BlackRoad-Forge)
[![License](https://img.shields.io/badge/License-Proprietary-f5a623?style=for-the-badge)](LICENSE)

**ulackroad apps** is part of the **BlackRoad OS** ecosystem — a sovereign, distributed operating system built on edge computing, local AI, and mesh networking by **BlackRoad OS, Inc.**

## About BlackRoad OS

BlackRoad OS is a sovereign computing platform that runs AI locally on your own hardware. No cloud dependencies. No API keys. No surveillance. Built by [BlackRoad OS, Inc.](https://github.com/BlackRoad-OS-Inc), a Delaware C-Corp founded in 2025.

### Key Features
- **Local AI** — Run LLMs on Raspberry Pi, Hailo-8, and commodity hardware
- **Mesh Networking** — WireGuard VPN, NATS pub/sub, peer-to-peer communication
- **Edge Computing** — 52 TOPS of AI acceleration across a Pi fleet
- **Self-Hosted Everything** — Git, DNS, storage, CI/CD, chat — all sovereign
- **Zero Cloud Dependencies** — Your data stays on your hardware

### The BlackRoad Ecosystem
| Organization | Focus |
|---|---|
| [BlackRoad OS](https://github.com/BlackRoad-OS) | Core platform and applications |
| [BlackRoad OS, Inc.](https://github.com/BlackRoad-OS-Inc) | Corporate and enterprise |
| [BlackRoad AI](https://github.com/BlackRoad-AI) | Artificial intelligence and ML |
| [BlackRoad Hardware](https://github.com/BlackRoad-Hardware) | Edge hardware and IoT |
| [BlackRoad Security](https://github.com/BlackRoad-Security) | Cybersecurity and auditing |
| [BlackRoad Quantum](https://github.com/BlackRoad-Quantum) | Quantum computing research |
| [BlackRoad Agents](https://github.com/BlackRoad-Agents) | Autonomous AI agents |
| [BlackRoad Network](https://github.com/BlackRoad-Network) | Mesh and distributed networking |
| [BlackRoad Education](https://github.com/BlackRoad-Education) | Learning and tutoring platforms |
| [BlackRoad Labs](https://github.com/BlackRoad-Labs) | Research and experiments |
| [BlackRoad Cloud](https://github.com/BlackRoad-Cloud) | Self-hosted cloud infrastructure |
| [BlackRoad Forge](https://github.com/BlackRoad-Forge) | Developer tools and utilities |

### Links
- **Website**: [blackroad.io](https://blackroad.io)
- **Documentation**: [docs.blackroad.io](https://docs.blackroad.io)
- **Chat**: [chat.blackroad.io](https://chat.blackroad.io)
- **Search**: [search.blackroad.io](https://search.blackroad.io)

---


[![PWA](https://img.shields.io/badge/PWA-50_apps-FF6B2B.svg)](https://apps.blackroad.io)
[![Offline First](https://img.shields.io/badge/offline-first-00D4FF.svg)](https://blackroad.io)
[![Installable](https://img.shields.io/badge/installable-service_worker-CC00AA.svg)](https://blackroad.io)



Application suite for the BlackRoad OS platform. 8 services spanning project management, streaming, blockchain, and infrastructure monitoring.

## Applications

| App | Stack | Description |
|-----|-------|-------------|
| **RoadMap** | Next.js, TypeScript, WebSockets | Project planning with real-time Kanban boards |
| **RoadWork** | Node.js, Express | Job board with AI matching |
| **RoadWorld** | Go, Gin, WebGL | Earth exploration and virtual environments |
| **RoadChain** | Rust, Actix-web, SHA-256 | Blockchain verification and immutable storage |
| **RoadCoin** | Python, FastAPI, Redis | Equity crowdfunding and crypto payments |
| **RoadView** | Node.js | Creative suite — design, video, AI generation |
| **PitStop** | Go, Gin | Infrastructure dashboard with real-time metrics |
| **RoadSide** | Node.js, Socket.io | Deployment portal and server connections |

## Deploy

```bash
# Deploy all
./DEPLOY_ALL.sh

# Deploy one app
~/blackroad-deploy/br-deploy deploy ~/blackroad-apps/roadmap aria64
```

## Architecture

Apps run on Raspberry Pi nodes (aria64) and DigitalOcean droplets behind Caddy reverse proxy.

```bash
# Check deployments
~/blackroad-deploy/br-deploy list aria64

# View logs
~/blackroad-deploy/br-deploy logs roadmap aria64
```

## Project Structure

```
blackroad-apps/
  roadmap/        # Project planning
  roadwork/       # Job portal
  roadworld/      # Earth exploration
  roadchain/      # Blockchain
  roadcoin/       # Crowdfunding
  roadview/       # Creative suite
  pitstop/        # Infrastructure dashboard
  roadside/       # Deploy portal
  DEPLOY_ALL.sh   # Batch deploy script
```

## License

Copyright 2026 BlackRoad OS, Inc. All rights reserved.
