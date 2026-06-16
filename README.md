# **LIKHITH ADITHYA**

**AI/ML Engineer  Open Source Contributor**  
Building production-grade multi-agent systems and AI infrastructure. Developing scalable ML pipelines and autonomous reasoning systems for real-world problems.

<div align="left">
  <a href="https://www.credly.com/users/likhithadithya"><img alt="Credly" src="https://img.shields.io/badge/Credly-Certifications-FF6B00?style=flat-square&logo=credly&logoColor=white" /></a>
  <a href="https://www.skills.google/public_profiles/f34847e8-c3db-4453-8ec4-139e26a435d4"><img alt="Google Skills" src="https://img.shields.io/badge/Google-Skills%20Profile-4285F4?style=flat-square" /></a>
  <a href="https://linkedin.com/in/likhith-adithya"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="https://openai.com/"><img alt="OpenAI" src="https://img.shields.io/badge/OpenAI-Developer-412991?style=flat-square&logo=openai&logoColor=white" /></a>
  <a href="https://gdg.community.dev/"><img alt="Google Developer Group" src="https://img.shields.io/badge/GDG-Community-4285F4?style=flat-square&logo=google&logoColor=white" /></a>
</div>

---

## **💡 WHAT I BUILD**
I architect and ship multi-agent systems, distributed AI infrastructure, and production ML pipelines. I work with standardized protocols like MCP to enable agent interoperability, optimize inference, [...]

- **Multi-Agent Systems & MCP:** Build Agent-to-Agent (A2A) communication patterns, implement Model Context Protocol (MCP) for standardized tool interoperability, design agentic loop architectures
- **AI Infrastructure:** Develop distributed inference systems, retrieval pipelines, and real-time data systems with latency optimization and production robustness.
- **Production ML:** Ship end-to-end ML systems with evaluation frameworks, automated deployment, and monitoring strategies.
- **Developer Tools:** Build CLI tools and IDE extensions that bring AI capabilities directly to developers.
- **Open Source:** Contribute to production AI systems, build reusable frameworks, and maintain code for real-world usage.

---

## **🚀 SHIPPED PROJECTS**

### **[AI-CLI-PRO](https://github.com/likhith-adithya/AI-CLI-PRO-Public)** ⭐ **LATEST**
*Python • Multi-Agent CLI • VS Code Extension • Gemini • Claude • Copilot*

- **What I Built:** One-click AI agent launcher directly from VS Code. Integrated Gemini, Claude, and Copilot into a seamless CLI experience. The fastest way to access multiple AI models from your terminal.

- **Technical Implementation:**
  - Multi-agent orchestration for different LLM providers
  - VS Code extension integration with CLI commands
  - Environment-based configuration for API keys
  - Async task execution for responsive UX
  - Real-time streaming responses

- **Results:** Production-ready developer tool with comprehensive docs and active development. Deployed to users for daily AI agent access.

### **[NVIDIA LLAMA-3 HYBRID RAG](https://github.com/likhith-adithya/Nvidia-Llama-RAG)**
*Python • NVIDIA NIM • ChromaDB • SerpAPI • Gradio • FastAPI • CLI*

- **What I Built:** Professional, modular hybrid Retrieval-Augmented Generation (RAG) system using NVIDIA Llama-3.3 LLM with real-time web search (SerpAPI) and persistent local vector database (ChromaDB).

- **Technical Implementation:**
  - **Intelligent Query Routing:** LLM-based router that automatically classifies queries between LOCAL (documents), WEB (search), or NONE (conversation)
  - **Hybrid Retrieval Pipeline:** Integrates SerpAPI for live web search with ChromaDB vector database using `all-MiniLM-L6-v2` embeddings
  - **Multi-Format Ingestion:** Supports `.txt` and `.pdf` files with automatic chunking, embedding, and persistent storage
  - **Stateful Memory Management:** Maintains rolling conversation history buffer for multi-turn dialogue context
  - **Error Handling & Fallback:** Graceful degradation with automatic fallback to general knowledge on missing keys or empty databases
  - **Flexible Deployment:** Gradio web UI (`http://127.0.0.1:7860`), lightweight CLI, and FastAPI REST server (`http://0.0.0.0:8000`)
  - **Comprehensive Testing:** 13+ unit tests (mocked) + integration tests with live API validation
  - **Production Architecture:** Modular src/ structure, environment-based configuration, no hardcoded secrets

- **Results:** Production-ready RAG system with comprehensive documentation, multi-mode deployment (web/CLI/API), 13+ test suite, and demonstrated handling of edge cases like fallback routing and memory management.

### **[DEBUG AI AGENT](https://github.com/likhith-adithya/GITHUB-DEBUG-AI-AGENT)**
*Python 3.12+ • Pydantic • Async/Await • Google ADK • MCP • Agent-to-Agent Protocol*

- **What I Built:** Enterprise-scale multi-agent system for GitHub repository analysis. Implemented primary orchestrator agent that dynamically spawns specialized Debug Agents via A2A protocol. Integrated MCP specification.

- **Technical Implementation:**
  - **Implemented MCP Specification:** Built MCP server for standardized tool/resource sharing between orchestrator and specialist agents, enabling interoperable multi-agent workflows
  - **Agent Delegation System:** Designed A2A protocol for agent spawning, task assignment, and result aggregation with proper error handling and retry logic
  - **Multi-LLM Support:** Built abstraction layer supporting OpenAI, Google Gemini, local Ollama/vLLM with unified interface
  - **Production Architecture:** Strict typing with Pydantic, async/await concurrency, CLI interface, environment configuration, structured logging
  - **Tool Integration:** Integrated GitHub API with MCP-compliant tool protocol for code analysis, bug detection, security scanning

- **Results:** Deployable agent framework with extensible architecture. Demonstrated sophisticated coordination patterns and standardized protocol implementation.

### **[STOCK-FORECAST](https://github.com/likhith-adithya/Stock-Forecast)**
*Python • Streamlit • Pandas • Prophet • Real-time Data Analysis*

- **What I Built:** Interactive Streamlit app for real-time stock analysis and AI-driven price forecasting. Features live market data, sector-wise stock charts, technical indicators, news sentiment analysis.

- **Technical Implementation:**
  - Real-time market data integration
  - Sector-wise filtering and dynamic charting
  - Technical indicator calculations
  - News sentiment analysis for market context
  - Prophet time-series forecasting for price predictions

- **Results:** Full-stack analytics tool with customizable date ranges, sector selection, and chart types for informed investing decisions.

---

## **🛠️ TECHNICAL TOOLKIT**

### **💻 LANGUAGES & BACKENDS**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

### **🧠 AI & ML FRAMEWORKS**
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-111111?style=flat-square)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white)
![NVIDIA NIM](https://img.shields.io/badge/NVIDIA_NIM-76B900?style=flat-square&logo=nvidia&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/-HuggingFace-FDEE21?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-8B5CF6?style=flat-square)
![Gradio](https://img.shields.io/badge/Gradio-FF4B4B?style=flat-square&logo=gradio&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

* **Agent Protocols & Frameworks:** Model Context Protocol (MCP), LangChain, Pydantic, Google ADK, Ollama, vLLM
* **Tools & Libraries:** NumPy, Apache Spark, functools, async/await, Prophet, SerpAPI
* **Vector Databases:** ChromaDB, Pinecone, FAISS
* **Evaluation & Monitoring:** RAGAS, MLflow, structured logging, error tracking

### **☁️ CLOUD & DEVOPS**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-0078D4?style=flat-square&logo=visual-studio-code&logoColor=white)

---

## **📚 CERTIFICATIONS & CREDENTIALS**
- 🚀 **[Credly Certifications](https://www.credly.com/users/likhithadithya)** — AI credentials
- ☁️ **[Google Skills Profile](https://www.skills.google/public_profiles/f34847e8-c3db-4453-8ec4-139e26a435d4)** — Google training
- 👨‍💻 **OpenAI Developer Community** — Active member
- 🤖 **Google Developer Group** — Community contributor

---

## **📊 GITHUB ACTIVITY**
<div align="center">
  <img src="https://ghchart.rshah.org/0A66C2/likhith-adithya" alt="GitHub Contribution Graph" />
</div>

---

## **NEXT**
Seeking internship or junior engineer roles in AI/ML systems engineering. Open to roles focused on multi-agent systems, inference infrastructure, developer tools, or production ML platforms.

[Connect on LinkedIn](https://linkedin.com/in/likhith-adithya) | [View my repositories](https://github.com/likhith-adithya)
