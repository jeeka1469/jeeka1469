# Srujan Teja Kunti
AI/ML Engineer building production-grade systems across Agentic AI, Voice AI, RAG, and MLOps.  
Focused on low-latency inference, scalable model deployment, and memory architectures — from research to production.
[Email](mailto:jeeka1469@gmail.com) · [LinkedIn](https://linkedin.com/in/jeeka1469) · [GitHub](https://github.com/jeeka1469)
---
### Currently Building
**[AgentX](https://github.com/jeeka1469/AgentX)** — Production multi-agent orchestration system using LangGraph with dynamic task decomposition, tool-use routing, and self-correction loops. Shared-state coordination via Redis pub/sub, durable task memory on PostgreSQL, full observability with Prometheus and OpenTelemetry. 10+ tool integrations, containerized with Docker Compose.
**[VoiceAI_X](https://github.com/jeeka1469/VoiceAI_X)** — Multilingual real-time voice AI platform supporting 10+ Indian languages. Whisper large-v3 (INT8 ONNX) for STT, VITS2 fine-tuned per language for TTS, sub-150ms end-to-end latency on CPU. Zero-shot voice cloning from 5 seconds of audio. Served on Triton with dynamic batching and async WebSocket streaming.
---
### Selected Work
**Enterprise Semantic Search Engine** — Hybrid dense-sparse retrieval (BGE-M3 + BM25) over 100k+ documents with HyDE query expansion and cross-encoder reranking. 91% top-3 retrieval precision. NER and intent classification on the query layer cut irrelevant retrievals by 38%. Redis cache reduced P99 latency from 420ms to 55ms.
**GenAI Document Intelligence Platform** — Multimodal pipeline ingesting PDFs, spreadsheets, and images via Unstructured.io. Multi-LLM routing layer (GPT-4o / Claude) selecting by task type, cost, and latency SLAs — 42% inference cost reduction. Handles 500+ concurrent document sessions.
**AI Memory Architecture** — Three-tier memory system (working, episodic, semantic) with recency decay and frequency-weighted retrieval for conversational agents. Rolling semantic summaries via a learned decay function cut prompt token overhead by 60% while preserving long-range context.
---
### Research
**[Kolmogorov-Arnold Networks: Benchmarking and Analysis](https://github.com/jeeka1469/KAN-Implementation)** — Rebuilt KAN from scratch in PyTorch with learnable activations on edges. Benchmarked against MLP baselines on nonlinear regression: 20% lower MSE, 1.5x faster convergence. Ablation studies on grid resolution and spline order.
---
### Stack
```
Languages        Python, C++, SQL, JavaScript
Agentic AI       LangGraph, LangChain, Tool Use, Task Planning, Multi-Agent Systems
Voice AI         Whisper, VITS2, ONNX, INT8 Quantization, Triton, Voice Cloning, WebSockets
RAG & NLP        Qdrant, FAISS, BGE-M3, BM25, HyDE, Reranking, NER, spaCy
GenAI            GPT-4o, Claude API, Multi-LLM Routing, Prompt Engineering, Multimodal
DL & Finetuning  PyTorch, LoRA, PEFT, DPO, Instruction Tuning, Transformers, CNNs, LSTMs
Infra & MLOps    Docker, Kafka, Airflow, MLflow, Prometheus, OpenTelemetry, Redis, GitHub Actions
```
---
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=jeeka1469&show_icons=true&hide_border=true&bg_color=00000000&title_color=8b949e&icon_color=8b949e&text_color=8b949e&ring_color=8b949e&hide_title=true&hide_rank=true" height="150" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=jeeka1469&hide_border=true&background=00000000&stroke=30363d&ring=8b949e&fire=c9d1d9&currStreakLabel=8b949e&sideLabels=8b949e&currStreakNum=c9d1d9&sideNums=c9d1d9&dates=8b949e" height="150" />
</div>
