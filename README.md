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

## 🏢 About Stackaura

This repository is maintained by **Stackaura**. We specialize in providing top-tier digital solutions, focusing on cutting-edge web development, premium branding, scalable backend architecture, and private AI infrastructure designed to secure and elevate your business.

**Ready to build something amazing?**
> Visit us at [**Stackaura.com**](https://www.stackaura.com/) to learn more about our services and how we can help scale your next local AI project.

<div align="center">
  <a href="https://www.stackaura.com/">
    <img src="https://img.shields.io/badge/Visit-Stackaura-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Visit Stackaura" />
  </a>
</div>
