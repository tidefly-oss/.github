<p align="center">
  <img src="https://raw.githubusercontent.com/tidefly-oss/.github/main/assets/tidefly_mascot.png" width="180" alt="Tidefly Mascot" />
</p>

<div align="center">

# Tidefly

**Deploy and manage containers on your own hardware — as simple as Heroku or Railway, but fully self-hosted and open source.**

Built on a lightweight stack (Go + SvelteKit) with zero-config defaults, so you can go from a fresh server to a running app in minutes.

[![Version](https://img.shields.io/github/v/release/tidefly-oss/tidefly-plane?include_prereleases&label=version&color=7c3aed)](https://github.com/tidefly-oss/tidefly-plane/releases)
[![License](https://img.shields.io/badge/license-AGPLv3-06b6d4)](https://github.com/tidefly-oss/tidefly-plane/blob/main/LICENSE)
[![Stars](https://img.shields.io/github/stars/tidefly-oss/tidefly-plane?style=flat&color=7c3aed)](https://github.com/tidefly-oss/tidefly-plane/stargazers)

</div>

---

## Repositories

| Repo                                                                  | Description                                            |
|-----------------------------------------------------------------------|--------------------------------------------------------|
| [tidefly-plane](https://github.com/tidefly-oss/tidefly-plane)         | Go backend — API, deployment engine, worker management |
| [tidefly-agent](https://github.com/tidefly-oss/tidefly-agent)         | Worker agent — runs on remote nodes, connects via mTLS |
| [tidefly-ui](https://github.com/tidefly-oss/tidefly-ui)               | SvelteKit frontend dashboard                           |
| [tidefly-tui](https://github.com/tidefly-oss/tidefly-tui)             | Bubble Tea setup wizard                                |
| [tidefly-templates](https://github.com/tidefly-oss/tidefly-templates) | Service deploy templates                               |
| [tidefly-docs](https://github.com/tidefly-oss/tidefly-docs)           | Documentation (coming soon)                            |

## Features

- 🐳 **Docker & Podman** — full runtime support, auto-detection
- 🚀 **Deploy anything** — Dockerfile, Docker Compose, or service templates
- 🌐 **Automatic routing** — Caddy reverse proxy with Let's Encrypt, zero config
- 🔗 **Multi-node** — Plane/Agent architecture with gRPC mTLS tunnel
- 🔒 **Secure by default** — JWT auth, Argon2id, project isolation, mTLS
- 📊 **Monitoring** — real-time metrics, logs, and notifications via SSE
- 🪝 **Webhooks** — auto-deploy on push from GitHub, GitLab, Gitea, Bitbucket
- 💾 **Backups** — Postgres export to S3-compatible storage or direct `pg_dump` download
- 🧩 **Open source** — AGPLv3, self-hosted, no telemetry