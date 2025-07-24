# 🧠 AI Suite: Local Multi-Tool AI/ML Development Environment

Welcome to the **AI Suite** – a powerful, containerized AI/ML development environment designed for local, GPU-accelerated workflows using Docker, Open WebUI, and Ollama.

## 🚀 What's Included

This setup includes:

| Tool / Service       | Purpose                                                                 |
|----------------------|-------------------------------------------------------------------------|
| 🧠 **Ollama**         | Run LLMs like LLaMA3, Code LLaMA, Mistral locally via GPU              |
| 🧩 **Open WebUI**     | Elegant web UI for Ollama with RAG, chat templates, file uploads       |
| 📒 **Jupyter**        | Classic notebook environment with Ollama + Python integration          |
| 🐍 **LangChain**      | Chain LLM agents, memory, tools, and prompts                           |
| 🦙 **LlamaIndex**     | Index PDFs, docs, websites for RAG pipelines                          |
| 🧾 **Haystack**       | Advanced retrieval + generative QA pipelines                           |
| 📊 **PandasAI**       | Natural language queries over dataframes                               |
| 🧠 **CrewAI**         | Multi-agent coordination framework for LLMs                            |
| 📢 **Whisper**        | Local speech-to-text using Whisper + Python                            |
| 🎨 **Stable Diffusion** | Local image generation and prompts                                    |
| ⚡ **FastAPI**        | Launch your own ML or inference APIs locally                          |
| 🎛️ **Streamlit**      | Build quick AI dashboards and apps                                     |

---

## 📦 How to Run

### ✅ Prerequisites

- Docker + Docker Compose (with GPU support via NVIDIA Container Toolkit)
- WSL2 on Windows (if applicable)
- At least 16GB RAM and 10GB disk space recommended

### 🛠️ Setup

1. **Clone the repo**
   ```bash
   git clone https://github.com/YOUR_USERNAME/ai-suite.git
   cd ai-suite
2. **Start Everything**
   ```bash
   docker compose up -d --build
3. Visit in Browser
   - Open WebUI: http://localhost:3000
   - Jupyter: http://localhost:8888
   - Streamlit: http://localhost:8501
   - FastAPI Docs: http://localhost:8000/docs
  
### 🗂️ Folder Structure

ai-suite/
├── docker-compose.yml
├── ollama/                  # LLM engine
├── open-webui/              # Web UI for chat & documents
├── jupyter/                 # Python notebooks with LLM access
├── whisper/                 # Audio to text app
├── stable-diffusion/        # Image generation
├── langchain/               # Prompt chains
├── llamaindex/              # RAG document indexing
├── haystack/                # QA pipelines
├── pandasai/                # NL-driven pandas queries
├── fastapi/                 # Custom ML API template
├── streamlit-app/           # Frontend dashboards
└── ai-tools/                # Shared scripts, dependencies

### 📄 Optional Enhancements
- Mount your documents (PDFs, CSVs) into open-webui or jupyter for retrieval-based question answering
- Add .env files for API keys (e.g., for Hugging Face)
- Add notebooks/ directory for storing and versioning your work

### 👨‍💻 Author
Built by Korey Dillon
- [🔗LinkedIn](https://www.linkedin.com/in/korey-dillon)


