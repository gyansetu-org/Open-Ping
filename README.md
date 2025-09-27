# Open-Ping
An open-source, PHP-powered, anonymous messaging relay platform — connect, chat, and broadcast messages securely without sign-ups.

## Features
- Zero signup anonymous messaging
- Host sessions via QR codes
- WebSocket realtime messaging (Node.js)
- Redis for session & queueing, MySQL for persistence
- Basic sanitization, rate-limiting, moderation queue


## Tech Stack
- PHP (REST API)
- Node.js (WebSocket server)
- Redis (session store, pub/sub)
- MySQL (persistence)
- Docker for local dev


## Quickstart (dev)
1. Clone repo
2. Copy `.env.example` to `.env` and fill credentials
3. `make up`
4. Visit `https://localhost` (mkcert recommended)


## Contribution
See `CONTRIBUTING.md` for dev setup and how to contribute.


## License
MIT — see LICENSE file.
