# 🧠 SciLitMiner
### A System for Scientific Literature Mining and Knowledge Discovery

**SciLitMiner** is an intelligent, end-to-end system designed to accelerate **data-driven scientific discovery** through advanced **literature mining**, **dataset extraction**, and **domain-specific knowledge reasoning**.

Initially developed for **materials science**, SciLitMiner automates the ingestion and analysis of scientific literature to uncover hidden relationships between materials, processes, microstructure, and properties—empowering researchers to move from information overload to actionable insights.

---

## 🚀 Overview

Recent advances in **data mining** and **AI-assisted discovery** have enabled automation in literature-based research. However, existing tools and digital libraries often fall short in retrieving and evaluating publications for highly specific scientific questions.

**SciLitMiner** bridges this gap by combining **federated literature ingestion**, **dataset-aware retrieval**, and **retrieval-augmented generation (RAG)** tailored for scientific reasoning.

---

## 🧩 Key Features

- **Federated Literature Ingestion**  
  Seamlessly integrates with multiple digital libraries and repositories for large-scale literature collection.

- **Dataset-Aware Retrieval**  
  Identifies publications containing **embedded scientific datasets**, including those within **visual elements** (e.g., figures, tables, plots).

- **Intelligent Querying & Ranking**  
  Applies advanced retrieval techniques and metadata enrichment for **context-aware** literature exploration.

- **Knowledge Reasoning via RAG**  
  Combines domain-specific reasoning and **retrieval-augmented generation (RAG)** using **large language models (LLMs)** for high-quality insights.

- **Extensible Architecture**  
  Built to support multiple research domains beyond materials science, enabling automated literature-based discovery across disciplines.

---

## 🧪 Case Studies

### 1. Creep Behavior of γ-TiAl Alloys
SciLitMiner analyzed hundreds of publications to map the interplay between material composition, processing routes, microstructure, and creep rate.  
The knowledge reasoning workflow, powered by OpenAI LLMs, achieved **>90% “good” (>3/5)** ratings by domain experts across qualitative evaluation metrics.

### 2. Model Comparison and Benchmarking
A comparative study demonstrated that SciLitMiner’s RAG-based workflow **outperformed GPT-4.5-turbo with web search**, **Perplexity**, and **Elicit** in reliability.  
Open-source LLMs were also benchmarked as **drop-in replacements** for proprietary models, showing **comparable or superior performance**.

---

## ⚙️ System Architecture

SciLitMiner is composed of modular, containerized components supporting **scalable deployment**:

- **Frontend:** [scilitminer-frontend](https://github.com/vipulg13/scilitminer-frontend.git)  
- **Backend (Synchronous API):** [scilitminer-backend-sync](https://github.com/vipulg13/scilitminer-backend-sync.git)  
- **Backend (Asynchronous Processing):** [scilitminer-backend-async](https://github.com/vipulg13/scilitminer-backend-async.git)
- **Backend (LLM Service):** [scilitminer-llmservice](https://github.com/vipulg13/scilitminer-llmservice.git)

### Core Dependencies
- [MongoDB](https://www.mongodb.com/) – NoSQL for Metadata & content storage  
- [Elasticsearch](https://www.elastic.co/) – Full-text and semantic search  
- [Monstache](https://rwynn.github.io/monstache/) – Real-time data sync between MongoDB and Elasticsearch
- [Grobid](https://github.com/kermitt2/grobid) – A machine learning software for extracting information from scholarly documents
- [pdfigures2](https://github.com/allenai/pdffigures2) - Given a scholarly PDF, extract figures, tables, captions, and section titles
- [PDFigCapX](https://github.com/pengyuanli/PDFigCapX) - Given a scholarly PDF, extract figures, tables, captions, and section titles
- [PUB2TEI](https://github.com/kermitt2/Pub2TEI) - Service for converting and enhancing heterogeneous publisher XML formats into TEI

> **Note:** Instructions for setting up a **sandbox environment** using **Docker** and **Kubernetes** will be added soon.

---

## 🧱 Planned Features

- 🔍 Advanced visual dataset parsing and reasoning (e.g., scientific plots, graphs, micrographs)  
- 🧩 Domain-agnostic ontology and schema support for extracting structured datasets from scientific disciplines  
- ☁️ Cloud-native deployment templates and monitoring (e.g., a single dockerfile, HELM charts)   

---

## 🤝 Contributing

Contributions are welcome!  
Please check out each repository’s issue tracker for open tasks, feature requests, and contribution guidelines.

---

## 📜 License

This project is licensed under the **GNU General Public License v3.0**.  
See the individual repositories for details.

---

## 📧 Contact

For questions or collaboration opportunities, please create an issue.
