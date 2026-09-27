# Muhammad Sohaib Imran

**Software Engineer focused on AI/ML Systems**

I build systems around machine learning models: inference and serving, computer vision pipelines, retrieval infrastructure, evaluation workflows, and backend systems.

Currently studying Computer Science and exploring the engineering problems that appear between a model and a reliable production system.

## Selected Projects

### [VigilAI](https://github.com/sohaib-0897/VigilAi)
**Real-time computer vision and video analytics**

End-to-end video analytics system for turning camera streams into tracked, reviewable events.

- YOLO inference with PyTorch and ONNX Runtime
- ByteTrack multi-object tracking
- Stateful zone, tripwire, dwell, occupancy, and PPE rules
- Bounded frame queues and dedicated CV workers
- PostgreSQL-backed events with annotated evidence
- Reproducible inference benchmarks and held-out evaluation

`Python` `FastAPI` `ONNX Runtime` `OpenCV` `ByteTrack` `PostgreSQL` `Redis` `Next.js`

---

### [LLM Inference Lab](https://github.com/sohaib-0897/llm-inference-lab)
**LLM inference, serving, and performance experiments**

A systems-focused laboratory for understanding how transformer inference behaves under different execution strategies and serving conditions.

- Decoder-only transformer with RoPE, GQA, RMSNorm, and SwiGLU
- KV-cached decoding vs full-prefix recomputation
- Batching, context-length, and output-length experiments
- INT8 weight-only quantization
- PyTorch vs ONNX Runtime measurements
- Real Qwen model serving through Ollama on an RTX 4050
- TTFT, throughput, VRAM, model-size, and concurrency benchmarks

`Python` `PyTorch` `ONNX Runtime` `Ollama` `NumPy` `pytest` `React` `TypeScript`

---

### [OmniOps](https://github.com/sohaib-0897/OmniOps)
**Multimodal retrieval and agent infrastructure**

A system for turning documents, tables, images, and other inputs into traceable evidence for AI workflows.

- Hybrid full-text + vector retrieval
- Evidence provenance and citation lineage
- Persisted agent and runtime events
- Authenticated SSE streaming
- Sandboxed tool execution
- PostgreSQL + pgvector storage

`Python` `FastAPI` `PostgreSQL` `pgvector` `DuckDB` `Docker` `TypeScript`

---

### [InboxLearn](https://github.com/sohaib-0897/InboxLearn)
**Human-in-the-loop machine learning**

Email triage system built around controlled model improvement rather than silent retraining.

- Incremental learning from human corrections
- Candidate model versioning
- Evaluation gates before promotion
- Exact rollback to previous model states
- Reproducible experiments and regression tests
- Hardened model serialization

`Python` `scikit-learn` `SQLite` `Streamlit` `pytest`

---

### [DataShield](https://github.com/sohaib-0897/DataShield)
**Endpoint DLP and incident-response prototype**

Windows endpoint monitoring system connecting filesystem and upload activity with an analyst investigation workflow.

- Endpoint filesystem and removable-media telemetry
- Sensitive-data detection and risk scoring
- Authenticated policy and alert APIs
- Analyst investigation workflow
- PostgreSQL persistence, RBAC, and audit history
- Automated backend and frontend testing

`Python` `FastAPI` `PostgreSQL` `React` `Docker` `pytest`

## Open Source

Contributing fixes and tests to established ML projects.

- [Hugging Face PEFT #3827](https://github.com/huggingface/peft/pull/3827) — fixes OSF adapter re-merging so repeated merges do not double-apply model weight deltas, with regression coverage for merge idempotency.

## Technical Interests

- **ML systems** — inference, serving, benchmarking, optimization, and evaluation
- **Computer vision** — detection, tracking, and real-time video analytics
- **Retrieval** — embeddings, vector search, hybrid retrieval, and provenance
- **AI infrastructure** — agents, tool execution, model lifecycle, and observability
- **Backend systems** — APIs, workers, concurrency, persistence, and event-driven architecture

I care about systems that can be **measured, reproduced, inspected, and challenged**.

## Technologies

**Languages:** Python, TypeScript/JavaScript, SQL, C/C++, C#  
**ML:** PyTorch, scikit-learn, YOLO, ONNX Runtime, OpenCV, ByteTrack  
**Backend:** FastAPI, Flask, SQLAlchemy, REST, SSE, background workers  
**Data:** PostgreSQL, Redis, SQLite, pgvector, DuckDB  
**Infrastructure:** Docker, GitHub Actions, Linux, Ollama  
**Frontend:** React, Next.js, Tailwind CSS

## Current Direction

Going deeper into:

- LLM inference and model serving
- GPU and accelerator-aware ML systems
- model evaluation and reliability
- real-time multimodal systems
- retrieval and agent infrastructure
- open-source ML engineering

## Contact

GitHub: [@sohaib-0897](https://github.com/sohaib-0897)
