<div align="center">

# Alena Simonian

**Senior AI Full-Stack Engineer** · Los Angeles

*From weights to a response someone can trust.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alena-simonian-3b876658)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:alena.simonian369@gmail.com)

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=2600&pause=1400&color=A78BFA&center=true&vCenter=true&width=760&lines=GPU+inference%2C+measured+at+p95;Retrieval+that+can+show+its+sources;Interfaces+for+people+who+ship+models;FastAPI%2C+React%2C+and+the+path+between" alt="What I work on" />

<br>

</div>

<br>

I work on the part of an AI product that has to survive contact with users: the request path, the retrieval, the evaluation, and the screen where a person decides the model is ready.

That is model serving under real concurrency. It is answers that can point at a source. It is the tooling around both — traces, comparisons, search — so the system is legible, not just impressive in a demo.

Right now that work is at **Baseten**: deployment, inference routing, and the product surface on top of it. Before that, ML developer tooling at **Weights & Biases**, personalization and ranking at **Snap**, and full-stack product engineering at **Hulu**.

---

### How I think about the stack

**Latency is a product decision.**  
PyTorch and vLLM on GPUs, with batching, KV-cache behavior, and concurrency treated as one problem. A config that wins a single-request benchmark and falls over under load is not fast.

**If it cannot cite, it does not get to sound sure.**  
Chunking, embeddings, metadata filters, vector search. Evaluation for relevance, groundedness, and latency — not a vibe check on the answer.

**The interface is part of the system.**  
React and TypeScript in front of Python and Go services. Experiment history, traces, document search, the workflow an engineer actually lives in.

---

### Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,ts,react,go,fastapi,pytorch,postgres,redis,docker,kubernetes,aws,prometheus,grafana,githubactions&perline=14" alt="Python, TypeScript, React, Go, FastAPI, PyTorch, PostgreSQL, Redis, Docker, Kubernetes, AWS, Prometheus, Grafana, GitHub Actions" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/vLLM-6C4DFF?style=flat-square" alt="vLLM" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white" alt="pgvector" />
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white" alt="Terraform" />
  <img src="https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" alt="Apache Spark" />
</p>

---

### On the bench

**Knowledge assistant** — document ingestion, semantic retrieval, and cited answers, with an eval loop for relevance, groundedness, and response time. FastAPI and React on PostgreSQL and pgvector.

**Inference benchmarks** — time-to-first-token, end-to-end latency, token throughput, concurrency, and GPU memory. Continuous batching and KV-cache behavior, read as tradeoffs.

---

<div align="center">

**Baseten** · previously **Weights & Biases**, **Snap**, **Hulu**

Open to hard infrastructure problems, and to products where the model is only half the work.

</div>

