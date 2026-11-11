<div align="center">

# Hi, I'm Abdulhadi 👋

### AI Engineer & Founder
**LLM infrastructure · Agentic systems · Model evaluation · Production Python**

📍 Karachi, Pakistan &nbsp;•&nbsp; 🌍 Remote-friendly &nbsp;•&nbsp; ✅ Open to work

[![Website](https://img.shields.io/badge/Website-thetrillioniar.me-111827?style=for-the-badge&logo=googlechrome&logoColor=white)](https://thetrillioniar.me)
[![Portfolio](https://img.shields.io/badge/Portfolio-abdulhadi--sodeom.netlify.app-0f766e?style=for-the-badge&logo=netlify&logoColor=white)](https://abdulhadi-sodeom.netlify.app/)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-thetrillioniar-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/thetrillioniar)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Abdulhadi%20Junaid-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdulhadi-junaid-485795378)
[![Email](https://img.shields.io/badge/Email-Contact%20me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abdulhadijunaidahmedkhan@gmail.com)

</div>

---

## 👤 About

AI engineer and founder with **3 years of hands-on experience** building with LLMs, since before tools like Claude Code and Codex existed. I run my own AI products in production, so I deal with the unglamorous parts: provider routing, reliability, cost, evaluation, servers and deployments.

I'm strongest where applied AI meets platform engineering:

- 🔌 **API platforms:** OpenAI- and Anthropic-compatible routing, provider adapters, proxies
- 📊 **Model evaluation:** benchmarking open-weight models with repeatable pipelines
- 🤖 **Agentic systems:** multi-agent orchestration in Python/FastAPI
- 🧪 **Model optimization:** quantization and distillation research
- 🖥️ **Self-hosted infrastructure:** Ubuntu servers, Docker, Cloudflare Tunnel, Oracle Cloud

---

## 🚀 Projects

| Project | What it is | Stack | Status |
|---|---|---|---|
| **[Trillionir AI](https://thetrillioniar.me)** | Flat-rate LLM inference API with OpenAI/Anthropic-compatible routing, built for developers who need an API that just works and never returns an "out of credits" error | Python, OpenAI SDK, API routing | 🟢 Live |
| **[Sodeom](https://sodeom.com)** | Privacy-first search engine. Also hosts an OpenAI-compatible proxy endpoint (`sodeom.com/v1`) used across my other projects | SearXNG, Python | 🟢 Live |
| **TriMind** | Open-source research on LLM quantization and distillation, centered on Qwen3-8B (FP32 / INT4 / INT2 / Q2_K / BitNet comparisons), with quantized models published on Hugging Face | PyTorch, Transformers, LLaMA-Factory, TRL, DeepSpeed | 🟢 Published on [Hugging Face](https://huggingface.co/thetrillioniar) |
| **[Model Evaluation Pipeline](https://social.thetrillioniar.me/)** | Benchmarks open-weight models (Gemma 4 31B, Devstral 24B, Rnj-1 8B, SmolLM 135M and more) through a custom OpenAI-compatible endpoint, with published MMLU / MMLU-Pro / coding / GSM8K scores | `openbench`, Python, Ubuntu | 🟡 Ongoing |
| **[Fine-tuning Datasets](https://huggingface.co/thetrillioniar)** | Claude/OpenAI fine-tuning dataset (29 datasets → OpenAI JSONL, ~1.5M rows, 1,100+ downloads/mo) and Mythos-5 / Fabel-5 model outputs | Hugging Face, JSONL | 🟢 Published |
| **TriageDesk** | Multi-agent customer support orchestrator with a custom `BaseAgent` framework built directly on the OpenAI SDK. Previously self-hosted behind a Cloudflare Tunnel | Python, FastAPI, OpenAI SDK | ⚪ Not currently deployed |
| **[Blog Pipeline](https://blogs.thetrillioniar.me)** | AI-powered cron system that auto-writes and publishes posts (100+ articles, 87 topics), with MCP-driven web search, model selection and a newsletter | Python, MCP, cron | 🟢 Live |
| **[chat-to-video](https://github.com/Abdulhadi446/chat-to-video)** | Describe a video, get a rendered MP4: LLM storyboard → deterministic FFmpeg renderer → Piper narration, with a difficulty router that hands hard jobs to an autonomous agent | Python, FFmpeg, LLM routing | 🔵 Open source · hackathon build |
| **[paperclip](https://github.com/Abdulhadi446/paperclip)** | Chat → PDF: the model writes HTML, renders real A4 pages, streams a PDF; attach PDF/Word/MD/CSV to edit them | Python, headless Chrome, Playwright | 🔵 Open source · hackathon build |
| **[Porsche 911 Showcase](https://github.com/Abdulhadi446/porsches)** | Fan site covering every 911 generation: 161 spec'd variants, 179 prerendered routes, WebGL hero, media on Cloudflare R2 (live demo being rehosted) | Next.js, React Three Fiber, GSAP, Cloudflare R2 | 🔵 Open source · [Repo](https://github.com/Abdulhadi446/porsches) |
| **[HCM Lite](https://github.com/Abdulhadi446/hcm-lite)** | AI-assisted HCM built at the Saylani Hackathon (Oct 2026): tool-calling AI over its own SQLite DB, 18/18 E2E tests | Python, AI tool-calling, SQLite | 🔵 Open source |
| **[Aura Counter](https://auracounter.sodeom.com)** | Satirical Sodeom side project with a full account system: signup, login/logout, sessions, cookies and email | Web backend, auth, email | 🟢 Live |
| **[Image Collector (Vista Cars)](https://vistacars.thetrillioniar.me)** | LangGraph agent that picks a car a day, harvests its photoshoot, has Gemma-4 rank candidates by "aura", then auto-commits images to GitHub, updates the gallery site and posts a carousel to [Instagram](https://www.instagram.com/vistacarz/) | Python, LangGraph, Flask, Gemma-4, Make.com | 🟢 Live · [Repo](https://github.com/Abdulhadi446/image-collector) |

---

## 🛠️ Tech Stack

**Languages & Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenAI SDK](https://img.shields.io/badge/OpenAI%20SDK-412991?style=flat-square&logo=openai&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-111827?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![Make](https://img.shields.io/badge/Make-6D00CC?style=flat-square)

`LLaMA-Factory` `TRL` `DeepSpeed` `openbench` `Quantization` `Distillation`

**Infrastructure & Hosting**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-C74634?style=flat-square&logo=oracle&logoColor=white)

`SearXNG`

---

## 💼 What I Can Do For a Team

- **Integrate and route LLM providers:** build adapters and compatible API layers so apps can switch models without rewrites
- **Evaluate models properly:** set up benchmark pipelines so model choices are based on results, not hype
- **Build agent workflows:** orchestrators that route, act and hand off, written in clean production Python
- **Optimize models:** quantize and distil open models for cheaper, faster inference
- **Run what I build:** deploy, monitor and debug on real servers

---

## 🎓 Education & Training

- **Agentic AI Program (Batch-3), SMIT**, Dec 2025 to Aug 2026

---

## 📌 Currently

- Running and improving **Trillionir AI** and **Sodeom**
- Extending the model evaluation pipeline and publishing results
- Looking for **remote AI / ML engineering, applied AI and agent infrastructure** roles (7-day notice period)

---

## 📫 Contact

| | |
|---|---|
| 📧 Email | [abdulhadijunaidahmedkhan@gmail.com](mailto:abdulhadijunaidahmedkhan@gmail.com) |
| 💼 LinkedIn | [linkedin.com/in/abdulhadi-junaid-485795378](https://linkedin.com/in/abdulhadi-junaid-485795378) |
| 🌐 Website | [thetrillioniar.me](https://thetrillioniar.me) |
| 🗂️ Portfolio | [abdulhadi-sodeom.netlify.app](https://abdulhadi-sodeom.netlify.app/) |
| 🤗 Hugging Face | [huggingface.co/thetrillioniar](https://huggingface.co/thetrillioniar) |
| 🐙 GitHub | [github.com/Abdulhadi446](https://github.com/Abdulhadi446) |
| 🎮 itch.io | [abdulahdi.itch.io](https://abdulahdi.itch.io) |
| 📝 Blog | [blogs.thetrillioniar.me](https://blogs.thetrillioniar.me) |

<div align="center">

*Building things that just work.*

</div>
