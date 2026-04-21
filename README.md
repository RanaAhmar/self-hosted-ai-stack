# 🏠 Self-Hosted AI Stack

<div align="center">
  <img src="https://img.shields.io/badge/Status-Active-success.svg" alt="Status Active" />
  <img src="https://img.shields.io/badge/Deployment-Docker-blue.svg" alt="Deployment Docker" />
  <p><strong>A complete, privacy-first, self-hosted AI architecture deployed entirely via Docker Compose.</strong></p>
</div>

## ✨ Overview

Tired of paying for API tokens or worrying about proprietary data leaving your network? The **Self-Hosted AI Stack** is a declarative Docker Compose environment that spins up a completely private, local AI ecosystem in minutes.

It includes a lightweight LLM runner, a vector database for Retrieval-Augmented Generation (RAG), and a modern web UI for interaction—all communicating securely on a private Docker bridge network.

## 📦 Stack Components

- **Ollama**: Local LLM Inference Engine (GPU accelerated if available).
- **ChromaDB / Qdrant**: High-performance Vector Database for embeddings.
- **AnythingLLM / Open-WebUI**: A sleek, user-friendly frontend interface.
- **LiteLLM**: An AI gateway to standardize API calls across different local models.

## 🚀 Quick Start

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/RanaAhmar/self-hosted-ai-stack.git
    cd self-hosted-ai-stack
    ```

2.  **Configure Environment**:
    ```bash
    cp .env.example .env
    # Adjust variables like model paths or ports if necessary
    ```

3.  **Deploy**:
    ```bash
    docker-compose up -d
    ```

4.  **Access the UI**:
    Open your browser and navigate to `http://localhost:3000`.

## 🤝 Contributing

Contributions to improve performance, add new integrations, or update tool versions are welcome! Please open an issue or submit a pull request.



---

## 🚀 Discover More from Stackaura

If you found this tool useful, check out our other high-performance web utilities and follow **Ahmar Hussain** for more open-source excellence.

### 🌟 Featured Projects
- **[Free LLM APIs](https://github.com/RanaAhmar/free-llm-apis)** - A curated list of zero-cost AI endpoints.
- **[Awesome MCP Servers](https://github.com/RanaAhmar/awesome-mcp-servers)** - The ultimate collection of Model Context Protocol implementations.
- **[System Design Cheatsheet](https://github.com/RanaAhmar/system-design-cheatsheet)** - Master complex architectures in minutes.
- **[Next.js SaaS Starter](https://github.com/RanaAhmar/nextjs-saas-starter)** - The fastest way to launch your next product.

### 🔗 Stay Connected
- **Website:** [stackaura.com](https://www.stackaura.com/)
- **Author:** [Ahmar Hussain](https://github.com/RanaAhmar)

---


