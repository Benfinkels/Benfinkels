# Hi, I'm Ben Finkelstein 👋

**Applied AI Engineer & Systems Builder**  
Specializing in **Local/Edge AI Systems**, **Parameter-Efficient Fine-Tuning (LoRA)**, **Privacy-First RAG**, and **Econometric Attribution Modeling**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/)
[![GitHub](https://img.shields.io/badge/GitHub-Benfinkels-181717?style=flat&logo=github)](https://github.com/Benfinkels)
[![Email](https://img.shields.io/badge/Email-Benfinkels%40gmail.com-D14836?style=flat&logo=gmail)](mailto:Benfinkels@gmail.com)

---

## 🛠️ Core Technical Focus

- **Local & Edge Intelligence:** Building privacy-first, zero-cloud RAG architectures and local model inference pipelines using **Ollama**, **LanceDB**, and lightweight SLMs.
- **Fine-Tuning & MLOps:** Domain adaptation of open foundation models (Gemma, Llama) using **Unsloth**, **LoRA/QLoRA**, synthetic dataset generation, and automated PII scrubbers.
- **Multimodal AI & Computer Vision:** High-precision optical cropping, serial-number OCR, and multimodal document understanding (Gemini 1.5 Pro).
- **Statistical Modeling & Marketing Science:** Cross-channel incrementality, time-lagged econometric regression (NNLS / Ridge), and causal impact estimation.

---

## 🚀 Featured Engineering Projects

| Project | Tech Stack | Highlights |
| :--- | :--- | :--- |
| [**Open Home Inventory**](https://github.com/Benfinkels/open-home-inventory) | `Python` `OpenCV` `Multimodal AI` `pytest` `CI/CD` | Autonomous multimodal home insurance inventory. Performs lossless optical crops to extract micro-details (serial numbers) and reconciles against digital receipts. Fully offline & local-first. |
| [**Open Email LoRA**](https://github.com/Benfinkels/open-email-lora) | `PyTorch` `Unsloth` `LoRA` `Gemma` `Docker` `Ollama` | End-to-end pipeline for personalized email triage: automated PII sanitization, parameter-efficient fine-tuning on custom data, and containerized local inference runtime. |
| [**Manor RAG**](https://github.com/Benfinkels/manor-rag) | `Python` `LanceDB` `Ollama` `Vector Search` | Zero-cloud, local-first RAG engine designed for indexing technical documentation, appliance manuals, and home infrastructure records with zero subscription fees. |
| [**EVC Attribution Impact Model**](https://github.com/Benfinkels/Cross-Channel-Attribution-Analyzer-EVC-Impact-Model) | `Python` `scikit-learn` `NNLS Regression` `Colab` | Statistical modeling framework measuring cross-channel conversion lift driven by YouTube Engaged-View Conversions (EVCs) on downstream search and direct traffic. |
| [**YouTube Ad Creative Analyzer**](https://github.com/Benfinkels/Ad-Creative-Analyzer) | `Gemini 1.5 Pro` `React` `Node.js` `Express` | Multimodal ad evaluator grading video creatives against Google's empirical ABCD framework (Attention, Branding, Connection, Direction). |

---

## 💻 Tech Stack & Tooling

```
Languages:        Python, JavaScript/TypeScript, SQL, Shell, C++
AI / ML:          PyTorch, Hugging Face, Unsloth, LoRA/PEFT, Transformers, scikit-learn
GenAI & Local:    Ollama, LanceDB, Gemini API, LangChain / LlamaIndex, vLLM
Data & Analytics: Pandas, NumPy, SciPy, Matplotlib, Seaborn
DevOps & Cloud:   Docker, GitHub Actions (CI/CD), Git, Linux, Google Cloud (GCP)
```

---

## 📐 Engineering Philosophy

1. **Local-First & Data Sovereignty:** Whenever possible, build systems that respect user privacy by processing sensitive data locally before touching any external network.
2. **Empirical Measurement:** Avoid treating LLMs as magic black boxes. Evaluate with verifiable benchmarks, regression metrics, and strict unit testing.
3. **Engineering Rigor:** Every project deserves clean modular design, automated test suites, type safety, and reproducible one-command environments.
