# Advanced Imaging Techniques for Lung Cancer Diagnosis 

## 📋 Project Overview
Computed tomography (CT) scans are widely used to diagnose lung conditions due to their ability to provide a detailed overview of the body's respiratory system. This repo contain End to End ML-based classification of CT scan images

<img src="docs/\ctimg.png" alt="GenAI Career Assistant Architecture" width="500">

**Adenocarcinoma**
- **Origin:** Glandular cells that produce mucus, often in the outer parts of the lungs.
- **Associated with:** Most common type in smokers and non-smokers, more frequent in women and younger people.
- **Treatment:** May have targetable gene mutations (like EGFR, ALK) for targeted therapies.

**Squamous Cell Carcinoma**
- **Origin:** Flat, scale-like squamous cells lining the airways (bronchi).
- **Associated with:** Strongly linked to a smoking history, typically found centrally.
- **Treatment:** Less likely to have common adenocarcinoma mutations; may respond to immunotherapy.

**Large Cell Carcinoma**
- **Origin:** Can develop anywhere in the lungs from various cells, appearing "large" under a microscope.
- **Associated with:** Tends to grow and spread quickly.
- **Treatment:** Often diagnosed when cells are too undifferentiated (undeveloped) for specific classification, requiring broader NSCLC treatments.

---
## 🔧 Key Components

```

📁 config/ → YAML config for models, prompts, logging
📁 data/ → Prompts, embeddings, and other dynamic content
📁 examples/ → Minimal scripts to test key features
📁 notebooks/ → Quick experiments and prototyping
📁 tests/ → Unit, integration, and end-to-end tests

📁 src/ → The core engine — all logic lives here:
├── agents/ → Agent classes: planner, executor, base agent
├── memory/ → Short-term and long-term memory modules
├── pipelines/ → Chat flows, doc processing, and task routing
├── retrieval/ → Vector search and document lookup
├── skills/ → Extra abilities: web search, code execution
├── vision_audio/ → Multimodal processing: image and audio
├── prompt_engineering/→ Prompt chaining, templates, few-shot logic
├── llm/ → OpenAI, Anthropic, and custom LLM routing
├── fallback/ → Recovery logic when LLMs fail
├── guardrails/ → PII filters, output validation, safety checks
├── handlers/ → Input/output processing and error management
└── utils/ → Logging, caching, rate limiting, token counting

```
---

## ⚡ Best Practices

- Track prompt versions and results  
- Separate configs using YAML files  
- Structure code by clear module boundaries  
- Cache responses to reduce latency and cost  
- Handle errors with custom exceptions  
- Use notebooks for rapid testing and iteration  
- Monitor API usage and set rate limits  
- Keep code and docs in sync  

---

## 🧭 Getting Started

1. Clone the repo  
2. Install via `requirements.txt`  
3. Set up model configs  
4. Check sample code  
5. Begin in notebooks  

---

## 💡 Development Tips

- Use modular structure  
- Test components early  
- Track with version control  
- Keep datasets fresh  
- Monitor API usage  

---

## 📁 Core Files

- `requirements.txt` – Package dependencies  
- `README.md` – Project overview and usage  
- `Dockerfile` – Container build instructions  
