<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Biky%20Dev&fontSize=52&fontColor=00F7FF&animation=fadeIn&fontAlignY=38&desc=AI%20Engineer%20%7C%20Python%20%7C%20LLMs%20%7C%20Full-Stack&descAlignY=60&descAlign=50" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=3500&pause=1000&color=00F7FF&center=true&vCenter=true&width=900&lines=Building+real+AI+systems+that+ship.;Multi-Agent+LLMs+%7C+RAG+Pipelines+%7C+Computer+Vision;Python+%7C+FastAPI+%7C+LangGraph+%7C+PostgreSQL;May+2026+Graduate+%E2%80%94+Ready+to+contribute+from+day+one." />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</p>

---

## 👋 About Me

I'm **Biky Dev** — an AI engineer who builds things that actually run in production.

I graduated in May 2026 with a B.Tech in Computer Science from Kurukshetra University. Over the past year I've shipped a face attendance system running at 30 FPS in live classrooms, built multi-agent LLM pipelines with real streaming, and trained custom CNNs from scratch on real agricultural datasets.

I care about writing clean Python, making systems that don't fall over, and understanding what's actually happening inside the models — not just calling APIs.

**What I work with day to day:**
- Python, FastAPI, LangChain, LangGraph, LangSmith
- PyTorch, TensorFlow, Keras, Hugging Face
- PostgreSQL, Redis, FAISS, Pinecone
- OpenCV, MTCNN, ONNX
- Docker, AWS, Git

---

## 🚀 Projects I've Shipped

### 🤖 Multi-Agent LLM Workflow Orchestrator
**[github.com/Biky2/multi-agent-llm-orchestrator](https://github.com/Biky2/multi-agent-llm-orchestrator)**

A production-ready orchestration system where 4 specialized agents — Researcher, Planner, Executor, Validator — collaborate autonomously to complete complex tasks. Built with LangGraph state machines, dual-layer memory (Redis for session context, PostgreSQL for long-term history), and real-time SSE streaming with first-token latency under 200ms. Automatically retries if the Validator scores confidence below 60%.

`Python` `LangGraph` `FastAPI` `Redis` `PostgreSQL` `SSE` `Ollama`

---

### 🗂️ RAGChat — Intelligent RAG-Based Chatbot
**[github.com/Biky2/ragchat](https://github.com/Biky2/ragchat)**

Enterprise document chatbot with hybrid dense + sparse retrieval (Reciprocal Rank Fusion). Upload PDFs, DOCX, or TXT files and ask questions against your knowledge base. Every answer cites which chunks it came from. Three chunking strategies: fixed, sentence-boundary, and semantic. Pinecone as primary vector store with automatic FAISS fallback. Reduced irrelevant responses by 60% over naive retrieval.

`Python` `LangChain` `Pinecone` `FAISS` `FastAPI` `sentence-transformers` `BM25` `PostgreSQL`

---

### 🌿 CropGuard — Plant Disease Diagnosis
**Python · TensorFlow · Custom CNN · ONNX · XGBoost**

Custom CNN architecture trained from scratch (no pretrained backbone) on a 15-class crop disease dataset covering Pepper, Potato, and Tomato. Achieved 90%+ classification accuracy. Exported to ONNX and applied post-training quantization, cutting inference latency by 40% for edge deployment. Fused tabular metadata with XGBoost alongside the vision model to improve diagnostic confidence.

`Python` `TensorFlow` `Keras` `ONNX`  `Scikit-Learn` `Computer Vision`

---

### 📷 Face Attendance System *(@ LearnXChain)*
**Python · OpenCV · MTCNN · FastAPI · PostgreSQL**

Built during my role at LearnXChain. Real-time biometric attendance system running at 30 FPS using OpenCV and MTCNN face detection, improving verification accuracy by 25%. Multi-threaded inference pipeline with a concurrent FastAPI backend persisting session logs to PostgreSQL, supporting 100+ concurrent users.

`Python` `OpenCV` `MTCNN` `FastAPI` `PostgreSQL` `Multi-threading`

---

## 🛠 Tech Stack

| Area | Tools |
|---|---|
| **AI / ML** | PyTorch · TensorFlow · Keras · Hugging Face · ONNX · Scikit-Learn · XGBoost |
| **LLMs & RAG** | LangChain · LangGraph · Llama 3.2 · BERT · Transformers · FAISS · Pinecone |
| **Computer Vision** | OpenCV · MTCNN · CNNs · ONNX Quantization |
| **Backend** | Python · FastAPI · Node.js · PostgreSQL · Redis · MongoDB |
| **Data** | Pandas · NumPy · SMOTE · BM25 · sentence-transformers |
| **Infrastructure** | Docker · AWS · Git · CI/CD |
| **Frontend** | React · Next.js · TypeScript · Tailwind |

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Biky2&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Biky2&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Biky2&layout=compact&theme=tokyonight&hide_border=true" />
</p>

---

## 📡 Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Biky2&theme=react-dark&hide_border=true" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Biky2/Biky2/output/github-contribution-grid-snake-dark.svg" />
</p>

---

## 🏆 Highlights

- 🔥 Built and shipped 3 production AI projects in 2025-2026
- 🤖 Multi-agent LLM system with real-time SSE streaming live on GitHub
- 🌿 Custom CNN trained from scratch — 90%+ accuracy, deployed to edge
- 📷 Computer Vision system running at 30 FPS in a live classroom
- 🎓 B.Tech Computer Science, Kurukshetra University — May 2026

---

## 💼 Open To

- AI engineering and LLM systems roles
- Computer Vision and ML engineering
- Full-stack roles with Python/FastAPI backend
- Research engineering positions

---

## 📬 Contact

<p align="center">
  <a href="mailto:deobiky@gmail.com">
    <img src="https://img.shields.io/badge/Email-deobiky@gmail.com-informational?style=flat-square&logo=gmail" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/dev-biky/">
    <img src="https://img.shields.io/badge/LinkedIn-dev--biky-blue?style=flat-square&logo=linkedin" />
  </a>
  &nbsp;
  <a href="https://github.com/Biky2">
    <img src="https://img.shields.io/badge/GitHub-Biky2-black?style=flat-square&logo=github" />
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" />
</p>
