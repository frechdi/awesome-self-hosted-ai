# Awesome Self-Hosted AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of self-hosted AI tools, LLM inference engines, workflow platforms, and VPS providers optimized for AI workloads. Run AI on your own infrastructure — for privacy, cost control, and full customization.

## Contents

- [LLM Inference & Local Hosting](#llm-inference--local-hosting)
- [AI Workflow & Automation](#ai-workflow--automation)
- [Vector Databases & RAG](#vector-databases--rag)
- [AI Observability & Ops](#ai-observability--ops)
- [VPS Providers for AI Workloads](#vps-providers-for-ai-workloads)
- [GPU Cloud & Rentals](#gpu-cloud--rentals)
- [Hosting Guides & Resources](#hosting-guides--resources)
- [Contributing](#contributing)

---

## LLM Inference & Local Hosting

*Run large language models on your own hardware.*

| Tool | Description | License | GitHub |
|------|-------------|---------|--------|
| [Ollama](https://ollama.ai) | The easiest way to run LLMs locally — one command to pull and serve Llama, Mistral, Gemma, and more | MIT | [GitHub](https://github.com/ollama/ollama) |
| [LM Studio](https://lmstudio.ai) | Desktop app for discovering and running local LLMs — great GUI, OpenAI-compatible server | Proprietary (free) | — |
| [LocalAI](https://localai.io) | Drop-in OpenAI API replacement that runs models locally — supports LLaMA, Whisper, Stable Diffusion | MIT | [GitHub](https://github.com/mudler/LocalAI) |
| [llama.cpp](https://github.com/ggerganov/llama.cpp) | Pure C++ LLM inference — runs on CPU with quantization, the engine behind Ollama and LM Studio | MIT | [GitHub](https://github.com/ggerganov/llama.cpp) |
| [vLLM](https://vllm.ai) | High-throughput LLM serving with PagedAttention — production-grade GPU inference | Apache-2.0 | [GitHub](https://github.com/vllm-project/vllm) |
| [Jan](https://jan.ai) | Open-source desktop AI assistant — local models, no cloud, no data collection | AGPL-3.0 | [GitHub](https://github.com/janhq/jan) |
| [GPT4All](https://www.nomic.ai/gpt4all) | Cross-platform local AI — runs on consumer hardware, supports dozens of models | MIT | [GitHub](https://github.com/nomic-ai/gpt4all) |
| [AnythingLLM](https://useanything.com) | Full-stack local AI platform — document Q&A, agents, multi-user, and API | MIT | [GitHub](https://github.com/Mintplex-Labs/anything-llm) |
| [Open WebUI](https://openwebui.com) | Feature-rich browser UI for Ollama and OpenAI-compatible APIs | MIT | [GitHub](https://github.com/open-webui/open-webui) |
| [text-generation-webui](https://github.com/oobabooga/text-generation-webui) | The original local LLM UI — supports virtually every model format and inference backend | AGPL-3.0 | [GitHub](https://github.com/oobabooga/text-generation-webui) |
| [LibreChat](https://librechat.ai) | Multi-provider AI chat UI — supports OpenAI, Anthropic, Ollama, and local models | MIT | [GitHub](https://github.com/danny-avila/LibreChat) |

---

## AI Workflow & Automation

*Build AI agents, pipelines, and production apps without vendor lock-in.*

| Tool | Description | License | GitHub |
|------|-------------|---------|--------|
| [Dify](https://dify.ai) | LLM app development platform — RAG pipelines, AI agents, and production API in one self-hosted install | Apache-2.0 | [GitHub](https://github.com/langgenius/dify) |
| [n8n](https://n8n.io) | Workflow automation with 400+ integrations and native AI nodes — self-host or cloud | Fair-code | [GitHub](https://github.com/n8n-io/n8n) |
| [Flowise](https://flowiseai.com) | Drag-and-drop LLM flow builder built on LangChain — no code required | Apache-2.0 | [GitHub](https://github.com/FlowiseAI/Flowise) |
| [Langflow](https://langflow.org) | Visual LangChain and LlamaIndex pipeline builder — export to Python | MIT | [GitHub](https://github.com/langflow-ai/langflow) |
| [PrivateGPT](https://privategpt.dev) | Ask questions about your documents — 100% local, no data leaves your machine | Apache-2.0 | [GitHub](https://github.com/zylon-ai/private-gpt) |
| [Cheshire Cat](https://cheshirecat.ai) | AI agent framework — custom memory, plugins, and REST API out of the box | GPL-3.0 | [GitHub](https://github.com/cheshire-cat-ai/core) |
| [Lobe Chat](https://lobehub.com/chat) | Extensible AI chat platform — plugin system, knowledge base, multi-model | Apache-2.0 | [GitHub](https://github.com/lobehq/lobe-chat) |
| [BerriAI LiteLLM](https://litellm.ai) | Unified API proxy for 100+ LLM providers — OpenAI-compatible, with load balancing and spend tracking | MIT | [GitHub](https://github.com/BerriAI/litellm) |
| [Hivekeep](https://hivekeep.app) | Self-hosted platform to run a team of specialized AI agents with persistent memory and a web UI; agents collaborate and build their own tools, mini-apps, and plugins; reachable over Telegram, Slack, Discord, and Matrix; single container (Bun + SQLite) | MIT | [GitHub](https://github.com/MarlBurroW/hivekeep) |

---

## Vector Databases & RAG

*Store and retrieve embeddings for AI apps.*

| Tool | Description | License | GitHub |
|------|-------------|---------|--------|
| [Qdrant](https://qdrant.tech) | High-performance vector database in Rust — best-in-class filtering and payload storage | Apache-2.0 | [GitHub](https://github.com/qdrant/qdrant) |
| [Chroma](https://www.trychroma.com) | Simple embedding database — easy to self-host, popular in RAG tutorials | Apache-2.0 | [GitHub](https://github.com/chroma-core/chroma) |
| [Weaviate](https://weaviate.io) | Full-featured vector database with multi-modal support and built-in modules | BSD-3-Clause | [GitHub](https://github.com/weaviate/weaviate) |
| [Milvus](https://milvus.io) | Enterprise-grade vector database — scales to billions of vectors | Apache-2.0 | [GitHub](https://github.com/milvus-io/milvus) |
| [pgvector](https://github.com/pgvector/pgvector) | Vector similarity search inside Postgres — no new database to manage | PostgreSQL | [GitHub](https://github.com/pgvector/pgvector) |

---

## AI Observability & Ops

*Monitor, trace, and improve your AI applications.*

| Tool | Description | License | GitHub |
|------|-------------|---------|--------|
| [Langfuse](https://langfuse.com) | Open-source LLM observability — traces, evals, prompt management, and cost tracking | MIT | [GitHub](https://github.com/langfuse/langfuse) |
| [Phoenix (Arize)](https://phoenix.arize.com) | AI observability for LLMs and ML models — experiment tracking and hallucination detection | Elastic-2.0 | [GitHub](https://github.com/Arize-ai/phoenix) |
| [PromptLayer](https://promptlayer.com) | Prompt versioning, A/B testing, and request logging for LLM apps | Proprietary | — |

---

## VPS Providers for AI Workloads

*Where to host your self-hosted AI stack — tested for reliability and LLM performance.*

| Provider | Best For | Starting Price | Notes |
|----------|----------|---------------|-------|
| [Hetzner](https://www.hetzner.com/cloud) | Best price/performance in Europe — CPU inference with Ollama | From €3.79/mo | CX22 (2 vCPU, 4GB) handles small models; CAX (ARM) is very efficient |
| [DigitalOcean](https://www.digitalocean.com) | Developer-friendly setup — great docs and one-click apps | From $4/mo | GPU Droplets now available for $2.99/hr (H100) |
| [Vultr](https://www.vultr.com) | GPU cloud at competitive pricing — good US and EU coverage | From $2.50/mo | Cloud GPU instances from $0.20/hr |
| [Linode (Akamai)](https://www.linode.com) | Reliable long-term hosting — strong support and SLA | From $5/mo | Stable choice for production Dify/n8n deployments |
| [Contabo](https://contabo.com) | Highest RAM for the price — good for RAM-hungry LLMs | From €5.99/mo | High RAM VPS (24GB) is very popular for Ollama hosting |
| [OVHcloud](https://www.ovhcloud.com) | European data sovereignty — GDPR-compliant by default | From €3.59/mo | Bare metal GPU servers available |

---

## GPU Cloud & Rentals

*Rent GPUs by the hour for training, fine-tuning, or high-throughput inference.*

| Provider | Best For | Pricing | Notes |
|----------|----------|---------|-------|
| [Lambda Labs](https://lambdalabs.com) | Dedicated GPU instances — H100, A100, A10 | From $0.50/hr | On-demand and reserved instances |
| [Vast.ai](https://vast.ai) | Cheapest GPU rentals — peer-to-peer GPU marketplace | From $0.10/hr | Variable reliability; best for experiments |
| [RunPod](https://www.runpod.io) | Balance of price and reliability — serverless GPU | From $0.19/hr | Serverless option is excellent for burst workloads |
| [Paperspace](https://www.paperspace.com) | ML-focused cloud — good Jupyter and notebook experience | From $0.07/hr | Gradient notebooks included |
| [CoreWeave](https://www.coreweave.com) | Enterprise GPU cloud — H100 clusters at scale | Contact for pricing | Kubernetes-native, used by major AI labs |

---

## Hosting Guides & Resources

*Deploy your self-hosted AI stack — step-by-step guides and community resources.*

| Resource | Description |
|----------|-------------|
| [Dify Hosting Guide](https://dify-hosting.com) | Complete deployment guides for Dify on Hetzner, DigitalOcean, and other VPS providers — from Docker setup to reverse proxy configuration |
| [Best VPS for AI Workloads](https://bestvpsfor.com) | Benchmark comparisons of VPS providers for LLM inference — token/second benchmarks, cost-per-query analysis |
| [Self-Host VPS Guide](https://selfhostvps.com) | Step-by-step tutorials for self-hosting Dify, Coolify, n8n, Nextcloud, and more on your own VPS — from initial setup to production deployment |
| [r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/) | Active community for local LLM discussion — model recommendations, hardware advice, and benchmarks |
| [Ollama Discord](https://discord.com/invite/ollama) | Official Ollama community — help with setup, model selection, and API integration |
| [Awesome LLM](https://github.com/Hannibal046/Awesome-LLM) | Comprehensive list of LLM papers, tools, and frameworks |

---

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

- Tools must be actively maintained (commit within last 6 months for OSS)
- For VPS providers: include an honest note about limitations, not just marketing copy
- One PR per tool addition
- GPU pricing changes fast — include a note if pricing was last verified

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
