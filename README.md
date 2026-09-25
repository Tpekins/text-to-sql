# Text-to-SQL-SLM: Fine-Tuning Small Language Models for Code-Mixed Dialects

An open-source software engineering and applied AI framework designed to adapt resource-efficient Small Language Models (SLMs) for database semantic parsing interfaces. This project focuses on executing precise Text-to-SQL translations within low-resource, volatile, code-mixed African dialect environments.

## 🚀 Key Features
* **Parameter-Efficient Fine-Tuning (PEFT):** Core pipelines built using QLoRA to optimize SLMs (e.g., Phi-3, Llama-3-8B) on commodity hardware.
* **Dialect-Resilient Tokenization:** Specialized handling of rapid multi-matrix code-switching syntax.
* **Contextual Schema Injection:** Engineering backend prompts to dynamically map complex linguistic inputs straight into relational SQL database schemas.

## 🛠️ Tech Stack
* **Languages & Core Toolkits:** Python, PyTorch, Hugging Face Transformers, PEFT, TRL
* **Databases:** PostgreSQL / MySQL schemas
* **Architecture:** Context-aware prompt engineering, semantic data pipelines

## 📂 Project Structure
```text
├── data/                  # Low-resource dataset samples & train/test splits
├── src/
│   ├── tuning/            # Fine-tuning scripts (QLoRA config)
│   ├── inference/         # Text-to-SQL query generation pipelines
│   └── evaluation/        # Exact match & execution accuracy scripts
├── schema.sql             # Reference target database schema
└── requirements.txt       # Software dependencies
```

## 📈 Research & Lineage
This software implementation serves as the core technical validation for my master's thesis in Computer Software Engineering. It runs parallel to dataset efforts driven by the **Cameroon AI Lab** organization on Hugging Face to benchmark and stress-test modern AI models against complex structural code-switching.
