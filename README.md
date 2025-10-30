# CortexMesh

> [!NOTE]
> **Status:** Pre-Alpha. This project is currently in the early design and development phase.

CortexMesh is a decentralized P2P network that fuses the power of local devices into a single, unified compute mesh for running large language models. It distributes GGUF model inference across your hardware using Go and `llama.cpp`, enabling you to run models too big for one machine.

## Core Concepts

- **Peer-to-Peer:** No central server required. Nodes auto-discover each other on the local network.
- **Distributed Inference:** A model's layers are sharded across the VRAM of multiple nodes.
- **Single Binary:** All components (P2P logic, inference engine, web UI) are bundled into a single executable for maximum portability.
- **OpenAI-like API:** Interact with your distributed model through a familiar API endpoint.

## The Vision

The goal of CortexMesh is to democratize access to large-scale AI by allowing individuals and small teams to pool their existing consumer hardware (desktops, laptops, even phones via Termux) to run powerful, open-source language models without relying on expensive cloud infrastructure.

---
*This project is being developed in collaboration with an advanced AI engineering agent.*
