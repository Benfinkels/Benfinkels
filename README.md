# Hi, I'm Ben Finkelstein 👋

**Analytical Lead, Applied AI Systems Builder**  
Specializing in **Local/Edge AI Systems**, **Parameter-Efficient Fine-Tuning (LoRA)**, **Privacy-First RAG**, and **Econometric Attribution Modeling**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/)
[![GitHub](https://img.shields.io/badge/GitHub-Benfinkels-181717?style=flat&logo=github)](https://github.com/Benfinkels)
[![Email](https://img.shields.io/badge/Email-Benfinkels%40gmail.com-D14836?style=flat&logo=gmail)](mailto:Benfinkels@gmail.com)

---

## 🛠️ Core Technical Focus

- **Local & Edge Intelligence:** Building privacy-first, zero-cloud RAG architectures, Wake-on-LAN ephemeral GPU clusters, and local model inference pipelines using **Ollama**, **LanceDB**, and lightweight SLMs (`Gemma 4`, `Phi-4`, `Qwen 3.5`).
- **Fine-Tuning & MLOps:** Domain adaptation of open foundation models using **Unsloth**, **LoRA/QLoRA**, deterministic evaluation harnesses, and automated PII scrubbers.
- **Multimodal AI & Computer Vision:** High-precision optical ROI cropping, edge camera ISP tripwires, serial-number OCR, and multimodal document understanding.
- **Statistical Modeling & Marketing Science:** Cross-channel incrementality, time-lagged econometric regression (NNLS / Ridge), and causal impact estimation.

---

## 🚀 Featured Engineering Projects

| Project | Tech Stack | Highlights |
| :--- | :--- | :--- |
| [**Zero-Idle AI Doorbell Sentry (v2)**](https://github.com/Benfinkels/zero-idle-ai-sentry) | `Python` `Gemma 4` `Ollama` `MIPS Linux` `ACPI S3/S5` | Event-driven 2.5W camera Wake-on-LAN tripwire paired with a sleeping GPU server (`2.5W` S3 day / `0W` S5 night, `~3.5s` resume). Spatial walkway ROI crop, Discord + SMS inline photo alerts, and **>97% energy reduction**. |
| [**Trick-or-Treat Sentry (v1)**](https://github.com/Benfinkels/trick-or-treat-sentry-) | `Python` `Gemma 4` `Ollama` `PIL` `Discord API` | Zero-cloud Halloween visitor & costume classifier. Analyzed 1,683 porch frames at `$0.00` API cost with fast grayscale pixel-diff gating (`<5ms`) and IR-cut color cast correction. |
| [**Citadel CRM**](https://github.com/Benfinkels/citadel-crm) | `Python` `SQLite WAL` `LanceDB` `Gemma 4` | Local-first relationship knowledge graph & personal CRM with priority-weighted entity resolution, hybrid semantic search, and sub-500ms SLM omnibox extraction. |
| [**Local Agent Evals**](https://github.com/Benfinkels/local-agent-evals) | `Python` `Ollama` `pytest` `JSON Schema` | Deterministic benchmark suite evaluating local SLMs (`Gemma 4`, `Qwen 3.5`, `Phi-4`, `DeepSeek-R1`) on tool calling, self-healing code loops, and Bayesian math. |
| [**Open Home Inventory**](https://github.com/Benfinkels/open-home-inventory) | `Python` `OpenCV` `Multimodal AI` `pytest` `CI/CD` | Autonomous multimodal home insurance inventory. Performs lossless optical crops to extract micro-details (serial numbers) and reconciles against digital receipts. |
| [**Open Email LoRA**](https://github.com/Benfinkels/open-email-lora) | `PyTorch` `Unsloth` `LoRA` `Gemma` `Docker` `Ollama` | End-to-end pipeline for personalized email triage: automated PII sanitization, parameter-efficient fine-tuning on custom data, and containerized local inference runtime. |
| [**Manor RAG**](https://github.com/Benfinkels/manor-rag) | `Python` `LanceDB` `Ollama` `Vector Search` | Zero-cloud, local-first RAG engine designed for indexing technical documentation, appliance manuals, and home infrastructure records with zero subscription fees. |
| [**EVC Attribution Impact Model**](https://github.com/Benfinkels/Cross-Channel-Attribution-Analyzer-EVC-Impact-Model) | `Python` `scikit-learn` `NNLS Regression` `Colab` | Statistical modeling framework measuring cross-channel conversion lift driven by YouTube Engaged-View Conversions (EVCs) on downstream search and direct traffic. |
| [**YouTube Ad Creative Analyzer**](https://github.com/Benfinkels/Ad-Creative-Analyzer) | `Gemini 1.5 Pro` `React` `Node.js` `Express` | Multimodal ad evaluator grading video creatives against Google's empirical ABCD framework (Attention, Branding, Connection, Direction). |

---

## 💻 Tech Stack & Tooling

```
Languages:        Python, JavaScript/TypeScript, SQL, Shell, C++, Monkey C
AI / ML:          PyTorch, Hugging Face, Unsloth, LoRA/PEFT, Transformers, scikit-learn
GenAI & Local:    Ollama, Gemma 4, LanceDB, Gemini API, llama.cpp, vLLM
Data & Analytics: Pandas, NumPy, SciPy, Matplotlib, Seaborn, SQLite WAL
DevOps & Systems: Docker, Systemd, Linux ACPI/Power Orchestration, GitHub Actions, GCP
```

---

## 📐 Engineering Philosophy

1. **Local-First & Data Sovereignty:** Whenever possible, build systems that respect user privacy by processing sensitive data locally before touching any external network.
2. **Empirical Measurement:** Avoid treating LLMs as magic black boxes. Evaluate with verifiable benchmarks, regression metrics, and strict unit testing.
3. **Engineering Rigor:** Every project deserves clean modular design, automated test suites, type safety, and reproducible one-command environments.
