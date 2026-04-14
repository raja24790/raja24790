# Pattanaik Ramswarup

I build practical local AI products for founders, developers, and operators who want useful automation without sending private data to the cloud.

Currently shipping through [LocalAIMaster.com](https://localaimaster.com): local agents, RAG systems, Ollama stacks, fine-tuning workflows, and automation scripts that people can run on their own machines.

## Featured Products

| Product | What it helps you do | Start here |
| --- | --- | --- |
| [RAG Starter Kit](https://github.com/raja24790/rag-starter-kit) | Chat with PDFs, docs, CSVs, and notes locally with citations using Ollama, ChromaDB, FastAPI, and Streamlit. | `docker compose up -d` |
| [AI Agent Starter Kit](https://github.com/raja24790/ai-agent-starter-kit) | Run local research, code review, and data analysis agents with tool calling. | `python agents/research_agent.py` |
| [Fine-Tuning Starter Kit](https://github.com/raja24790/fine-tuning-starter-kit) | Prepare datasets, train LoRA adapters, convert to GGUF, and run custom models in Ollama. | `python scripts/train_lora.py` |
| [Ollama Docker Templates](https://github.com/raja24790/ollama-docker-templates) | Start local AI stacks such as Open WebUI, n8n, Flowise, ChromaDB, Langfuse, Dify, LibreChat, and multi-GPU Ollama. | `docker compose up -d` |
| [Local AI Automation Scripts](https://github.com/raja24790/local-ai-automation-scripts) | Automate summarization, code review, data extraction, email writing, and research workflows offline. | `python scripts/...` |
| [Ollama Prompt Pack](https://github.com/raja24790/ollama-prompt-pack) | Use 500+ prompts and Modelfiles for coding, writing, analysis, RAG, business, and creative work. | `./scripts/install-all.sh` |

## What I Am Building

- Local AI workflows that run without API keys after setup.
- Developer kits that are useful in the first 5 minutes.
- Docker-first templates for people who want fewer moving parts.
- Applied AI tools for invoices, documents, code, research, and internal operations.
- Public repos with real examples, clean setup steps, and issues that are easy for contributors to pick up.

## Start With These

```bash
# Local document Q&A
git clone https://github.com/raja24790/rag-starter-kit
cd rag-starter-kit
docker compose up -d

# Local agents
git clone https://github.com/raja24790/ai-agent-starter-kit
cd ai-agent-starter-kit
pip install -r requirements.txt
ollama pull llama3.1
python agents/research_agent.py "Compare three RAG chunking strategies"
```

## Tech I Use

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-4A4A4A?style=flat)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)

## Open Source Roadmap

- Publish the local AI product kits as clean public repositories.
- Add screenshots, quickstart GIFs, and sample data for each repo.
- Mark beginner-friendly issues for docs, examples, and integrations.
- Build small demo videos for the most useful workflows.
- Keep releases practical: one command setup, clear examples, and no hidden cloud dependency.

## Connect

- Website: [LocalAIMaster.com](https://localaimaster.com)
- GitHub: [@raja24790](https://github.com/raja24790)
- Email: [support@localaimaster.com](mailto:support@localaimaster.com)

If any repo saves you time, star it and open an issue with the next workflow you want automated.
