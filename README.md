<p align="left">
  <a href="https://github.com/clchinkc"><img src="https://img.shields.io/badge/AI-Engineer-2563eb?style=flat-square" /></a>
  <a href="https://github.com/clchinkc/story-bench"><img src="https://img.shields.io/badge/evals-benchmark-8b5cf6?style=flat-square" /></a>
  <a href="https://github.com/clchinkc/llm-cloud-inference"><img src="https://img.shields.io/badge/vLLM-production-059669?style=flat-square" /></a>
</p>

Hi, I'm Kevin.

AI Engineer @ Narrative AI — building AI that helps fashion brands coordinate with their manufacturers without drowning in WhatsApp messages and Excel trackers.

HKUST Computer Engineering + AI. Based in Hong Kong.

I build production AI systems, and I've learned a few things the hard way. If you can't measure whether your model is getting better or worse, you're guessing — I built a 34-task LLM-as-judge benchmark because "looks good to me" isn't a test suite. Agents that silently produce garbage when they get stuck are more dangerous than no agent at all, so I design failure recovery into agentic workflows from day one. And inference cost isn't a DevOps afterthought — it's a design constraint that shapes everything from model selection to deployment architecture.

---

## Projects

| Project | What it does | Why I built it |
|---------|-------------|----------------|
| [story-bench](https://github.com/clchinkc/story-bench) | 34-task LLM narrative benchmark with a 3-model judge ensemble | Existing evals weren't catching the failure modes I care about |
| [llm-cloud-inference](https://github.com/clchinkc/llm-cloud-inference) | Production vLLM serving Qwen3-8B-AWQ on Google Cloud Run | Wanted an OpenAI-compatible endpoint that scales to zero instead of idling at $2/hr |
| [document-mcp](https://github.com/clchinkc/document-mcp) | 26 MCP tools for large-scale document management | Documents are the atomic unit of most business workflows — needed structured ops on unstructured content |
| [stockchat](https://github.com/clchinkc/stockchat) | DSPy-powered stock analysis agent with RAG and technical indicators | Built to explore DSPy's optimization pipeline on a real domain with messy data |

### Toolbox

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-1.0-2563eb?style=for-the-badge" />
  <img src="https://img.shields.io/badge/vLLM-production-059669?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/MCP-protocol-8b5cf6?style=for-the-badge" />
</p>

---

## Hackathons

- APRU × Google Tech Policy Hackathon 2025 — AI-powered agricultural credit scoring with NASA satellite imagery and SHAP explainability

---

## Get in touch

- Email: chilonchin@gmail.com
- LinkedIn: [linkedin.com/in/clchinkc](https://www.linkedin.com/in/clchinkc/)

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/clchinkc/clchinkc/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/clchinkc/clchinkc/output/github-contribution-grid-snake.svg" />
  <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/clchinkc/clchinkc/output/github-contribution-grid-snake.svg" />
</picture>

<p align="right">
  <img src="https://komarev.com/ghpvc/?username=clchinkc&style=flat-square&color=2563eb" alt="Profile views" />
</p>
