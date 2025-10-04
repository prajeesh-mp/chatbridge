# ChatBridge

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/prajeesh-mp/chatbridge?style=social)](https://github.com/prajeesh-mp/chatbridge/stargazers)

**ChatBridge** is an **open-source live chat tool** that connects website visitors directly to **Slack**. Each visitor becomes a thread in a Slack support channel, making customer support fast, simple, and centralized. ChatBridge is designed to be **self-hosted** or optionally used as a **cloud-hosted SaaS** for managed support.

---

## Features

- Lightweight website widget (<20KB)
- Real-time Slack integration (visitor chat = Slack thread)
- Self-hosted or cloud-hosted options
- Open-source and developer-friendly
- Easy Docker deployment for self-hosting

---

## Monorepo Structure

```

chatbridge/
├── apps/
│ ├── web/ # Frontend widget
│ ├── api/ # Backend API
├── docker/ # Docker Compose and Dockerfiles
├── docs/ # Documentation
├── README.md
├── LICENSE
└── package.json # Root workspace config

```

---

## Quick Start

### 1. Clone the repo

```bash
git clone https://github.com/prajeesh-mp/chatbridge.git
cd chatbridge
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start development environment

```bash
# Start backend API
npm run dev:api

# Start frontend widget
npm run dev:web
```

### 4. Docker (optional)

```bash
docker-compose up --build
```

This will start the backend and database ready for self-hosted deployment.

---

## Contributing

We welcome contributions! Please see [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

- Bug reports and feature requests are welcome via GitHub issues.
- Pull requests should follow the monorepo structure and TypeScript conventions.

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](./LICENSE) file for details.

---

## Contact / Community

- GitHub: [https://github.com/prajeesh-mp/chatbridge](https://github.com/prajeesh-mp/chatbridge)
- Slack / Discord community coming soon for early adopters.

---

## Roadmap

- Multi-channel support (Teams, Telegram, Discord)
- Advanced analytics dashboard
- Cloud-hosted subscription plan
- Improved widget customization

---

**Built with ❤️ by Prajeesh MP**
