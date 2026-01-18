# Bench-Low: Benchmarking Multimodal LLMs in Low-Resource Settings

## 📌 Overview
Bench-Low is a benchmarking framework designed to evaluate lightweight and open-source
multimodal language models under low-resource computational constraints.

This repository focuses on **code, configurations, and evaluation results**.
Model weights and adapters are hosted separately.

---

## 🧠 Evaluated Models
- Mistral (text-only)
- Qwen2-VL
- LLaVA
- Kosmos-2

---

## ⚙️ Repository Structure
```text
├── src/            # Training, evaluation, inference scripts
├── configs/        # YAML configuration files
├── adapters/       # LoRA adapters (via Git LFS)
├── results/        # Benchmark results
└── scripts/        # Execution scripts
