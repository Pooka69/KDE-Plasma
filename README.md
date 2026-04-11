# KDE-Plasma

Programs That Work With KDE Plasma.

## Getting Started with Leon

[Leon](https://getleon.ai/) is an open-source personal assistant that runs on your server, giving you full control over your data and privacy. It uses AI concepts such as Natural Language Processing (NLP), Text-to-Speech (TTS), and Speech-to-Text (STT) to understand and respond to your requests via text or voice.

### Key Features

- **Self-hosted** — runs on your own server; no data leaves your machine unless you choose otherwise.
- **Modular** — add or build skills (modules) to extend Leon's capabilities.
- **Privacy-focused** — can work entirely offline.
- **Open source** — MIT-licensed and community-driven.

### Prerequisites

| Tool | Minimum Version |
|------|-----------------|
| Git | latest |
| Node.js | 16+ |
| npm | 8+ |
| Python | 3.9+ |
| Pipenv | latest |

### Installation

1. **Install the Leon CLI**

   ```bash
   npm install --global @leon-ai/cli
   ```

2. **Create a new Leon instance**

   ```bash
   leon create birth
   ```

   To use the latest development branch instead:

   ```bash
   leon create birth --develop
   ```

3. **Start Leon**

   ```bash
   leon start
   ```

   Leon will launch and you can interact with it from your browser.

### Configuration

Leon's settings live in configuration files inside the project directory. You can:

- Choose a **Speech-to-Text** provider (Google Cloud, Coqui STT for offline, etc.).
- Choose a **Text-to-Speech** provider (Google Cloud, Amazon Polly, offline options, etc.).
- Enable or disable specific skills.

Refer to the [official configuration docs](https://docs.getleon.ai/) for full details.

### Useful Resources

- [Leon Website](https://getleon.ai/)
- [Leon GitHub Repository](https://github.com/leon-ai/leon)
- [Leon Documentation](https://docs.getleon.ai/)
- [Leon Discord Community](https://discord.gg/KtYzmyn)
