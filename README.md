# MSc AI Acceleration Track (Sept - Dec 2026)

This repository tracks my 192-hour independent engineering sprint alongside my formal MSc AI curriculum. It combines low-level deep learning mechanics (implementing architectures from first principles) with high-level AI system design.

## 📚 Core References
* *Machine Learning with PyTorch and Scikit-Learn* – Sebastian Raschka
* *AI Engineering: Building Applications with Foundation Models* – Chip Huyen

## 🚀 Key Practical Milestones

### 🔹 Phase 1: Traditional ML & Pipeline Engineering (September)
* **Concepts:** Mathematical optimization, data scaling, matrix dimensionality reduction.
* **Artifact:** Developed a clean, reusable preprocessing pipeline class handling feature engineering and outlier removal on messy tabular data.
* **Code Location:** `/1-ml-foundations/`

### 🔹 Phase 2: PyTorch From First Principles (October)
* **Concepts:** Backpropagation calculus, tensor manipulation, prompt engineering metrics.
* **Artifact:** Implemented a Multi-Layer Perceptron (MLP) in raw PyTorch using custom training loops without high-level abstractions. Integrated automated prompt validation via external LLM APIs.
* **Code Location:** `/2-deep-learning/`

### 🔹 Phase 3: Local Vectorized RAG Workspace (November)
* **Concepts:** Attention mechanisms, semantic text embeddings, vector databases.
* **Artifact:** Constructed a local Retrieval-Augmented Generation (RAG) system. It parses academic lecture PDFs, vectorizes the context using local embeddings, indexes them via a vector database, and queries an open-source LLM.
* **Code Location:** `/3-ai-systems/`

### 🔹 Phase 4: Productionization & "AI-as-a-Judge" (December)
* **Concepts:** Model quantization, drift monitoring, LLM evaluation frameworks.
* **Artifact:** Wrapped the Phase 3 RAG workspace into a fast Streamlit user interface, implemented an automated evaluation framework to score response accuracy, and containerised the application using Docker.
* **Code Location:** `/4-production-ml/`

---
*Maintained by an MSc AI Student, UK.*
