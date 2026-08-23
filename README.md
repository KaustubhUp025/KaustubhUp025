<div align="center">

# Hi there 👋

**Building tools that catch what linters can't**

`distributed systems` · `ML infrastructure` · `agentic AI` · `GPU kernels` · `code analysis`



[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kaustubh-upadhyay-b3674b217)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/KaustubhUp025)
[![Quorum Live](https://img.shields.io/badge/Quorum_Live-Demo-4f46e5?style=for-the-badge&logo=google-cloud&logoColor=white)](https://quorum-3fnjzg6adq-uc.a.run.app/demo)

</div>

---

## 💡 About Me

```python
class Kaustubh:
    role      = "Software Engineer → ML Infrastructure"
    education = "B.Tech ECE, IIIT Jabalpur '24"
    building  = ["agentic code reviewers", "GPU kernel optimizers", "semantic search engines"]
    interests = ["distributed systems", "ML infra", "CUDA", "developer tooling"]
    fun_fact  = "Merged a fix into containerd/nerdctl — found a thundering-herd bug with an AI agent I built"
```

I build **agentic developer tools** — systems that use LLMs not for chat, but to *find real bugs*, *optimize real kernels*, and *search real codebases*. My projects have found coordination bugs in **vLLM**, **aiokafka**, and **containerd**, and I'm currently diving deep into GPU systems and ML infrastructure.

---

## 🔨 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### <img src="https://raw.githubusercontent.com/KaustubhUp025/quorum/main/src/quorum/static/mark.svg" width="22"/> [Quorum](https://github.com/KaustubhUp025/quorum)
**AI-powered distributed coordination linter**

[![Live Demo](https://img.shields.io/badge/Live_Demo-Cloud_Run-4f46e5?style=flat-square)](https://quorum-3fnjzg6adq-uc.a.run.app/demo)
[![CI](https://img.shields.io/github/actions/workflow/status/KaustubhUp025/quorum/ci.yml?style=flat-square&label=CI)](https://github.com/KaustubhUp025/quorum/actions)
[![Tests](https://img.shields.io/badge/tests-259%20passing-brightgreen?style=flat-square)]()

Reviews MRs/PRs for coordination anti-patterns — missing fencing tokens, retries without jitter, Kafka auto-commit pitfalls, saga compensation gaps — that static linters and generic AI reviewers miss.

**Real impact:** Found bugs in 9 open-source projects (vLLM, aiokafka, containerd/nerdctl). Got a [fix merged](https://github.com/containerd/nerdbox/pull/218) into containerd. Zero false positives across all runs.

`Gemini 2.5 Pro` · `GitLab MCP` · `Cloud Run` · `Vertex AI` · `SARIF`

</td>
<td width="50%" valign="top">

### 🧪 [KernelSmith](https://github.com/KaustubhUp025)
**Agentic GPU kernel optimizer**

🏗️ *Currently building — Google Cloud Hackathon*

An agentic system that profiles, analyzes, and optimizes GPU kernels. Feed it a CUDA/Triton kernel, and it iteratively benchmarks, identifies bottlenecks (memory bandwidth, occupancy, warp divergence), and rewrites for better performance.

Built for the Google Cloud **"All Things Agentic" Hackathon** (Taskmaster track) and my ML infrastructure portfolio.

`CUDA` · `Triton` · `Gemini` · `Google Cloud` · `Profiling`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🔍 [Quolab](https://github.com/KaustubhUp025)
**Semantic code search engine**

Hybrid code search combining dense embeddings (Qwen3) with BM25 lexical search, fused via Reciprocal Rank Fusion. Backed by pgvector for vector storage and exposed as a FastMCP streamable-HTTP server.

Search your codebase by *meaning*, not just text — "find the retry logic with backoff" finds it even if no function is named `retry`.

`Qwen3` · `pgvector` · `BM25` · `RRF` · `FastMCP`

</td>
<td width="50%" valign="top">

### 🤖 [SemSorter](https://github.com/KaustubhUp025/SemSorter)
**AI-powered robotic hazard sorting**

[![Live Demo](https://img.shields.io/badge/Live_Demo-Render-4f46e5?style=flat-square)](https://semsorter.onrender.com)

A multimodal AI agent controls a Franka Panda robotic arm in MuJoCo simulation — watches a conveyor belt via live camera, detects hazardous items with Gemini VLM, and executes pick-and-place operations via LLM function-calling.

Built on the **Vision-Agents SDK** by GetStream.

`MuJoCo` · `Gemini VLM` · `Deepgram STT` · `ElevenLabs TTS` · `FastAPI`

</td>
</tr>
</table>

<details>
<summary><b>📂 More projects</b></summary>
<br/>

| Project | Description | Tech |
|---------|-------------|------|
| [**AdLingo**](https://github.com/KaustubhUp025/AdLingo) | Audio-to-multilingual advertisement generator | JavaScript |
| [**Aushadhi**](https://github.com/KaustubhUp025/Aushadhi) | Drug recommendation system for diabetic patients | Python |
| [**sktime** (contrib)](https://github.com/KaustubhUp025/sktime) | Contributed `GeometricMeanAbsoluteError` metric | Python |
| [**ml-engineering**](https://github.com/KaustubhUp025/ml-engineering) | ML engineering exercises and experiments | Python |
| [**handson-mlp**](https://github.com/KaustubhUp025/handson-mlp) | Hands-on ML practice notebooks | Jupyter |

</details>

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**ML / AI**

![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Triton](https://img.shields.io/badge/Triton-6C3483?style=for-the-badge&logoColor=white)

**Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)

**Tools & Frameworks**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=KaustubhUp025&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&ring_color=58a6ff" width="49%" alt="GitHub Stats"/>
<img src="https://github-readme-streak-stats.herokuapp.com?user=KaustubhUp025&theme=github-dark-blue&hide_border=true&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" width="49%" alt="Streak Stats"/>

<br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KaustubhUp025&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8" width="40%" alt="Top Languages"/>

</div>

---

## 📈 Contribution Graph

<img src="https://github-readme-activity-graph.vercel.app/graph?username=KaustubhUp025&theme=github-compact&hide_border=true&bg_color=0d1117&color=58a6ff&line=58a6ff&point=c9d1d9&area=true&area_color=1f6feb" width="100%" alt="Contribution Graph"/>

---

## 🎯 What I'm Up To

- 🔧 **Building** [KernelSmith](https://github.com/KaustubhUp025) — agentic GPU kernel optimization
- 🔍 **Shipping** [Quolab](https://github.com/KaustubhUp025/quolab) — semantic code search with hybrid retrieval
- 📚 **Learning** CUDA internals, Triton compiler, ML systems design
- 🎯 **Targeting** ML infrastructure & GPU systems roles
<!-- - 🎓 **Planning** Georgia Tech OMSCS (Machine Learning specialization) -->

---

<div align="center">

<img src="https://komarev.com/ghpvc/?username=KaustubhUp025&color=1f6feb&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile Views"/>

<br/><br/>

*"SonarQube doesn't have rules for saga compensation. Semgrep can't reason across service boundaries. CodeRabbit can't search the full repo. [Quorum can.](https://github.com/KaustubhUp025/quorum)"*

</div>
