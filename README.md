<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7b2ff7,30:f107a3,60:ff6b35,100:00d4ff&height=220&section=header&text=Rakshak%20S&fontSize=72&fontColor=ffffff&fontAlignY=40&desc=LOKI%20%E2%80%A2%20Research%20Engineer%20%E2%80%A2%20Builder%20of%20Systems%20That%20Think&descAlignY=62&descColor=ffffff&descSize=18&animation=fadeIn" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2500&pause=600&color=7B2FF7&center=true&vCenter=true&multiline=false&width=750&lines=Samsung+PRISM+Elite+Track+%E2%80%94+Research+Engineer;GPA+9.80+%2F+10.00+through+Sem+IV;Systems+%2B+AI%2FML+%2B+Security+%2B+Distributed+Systems;Building+things+the+world+hasn%27t+named+yet.)](https://git.io/typing-svg)

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-PRATHVI9607-7b2ff7?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PRATHVI9607)
[![Email](https://img.shields.io/badge/Email-rakshaksujith@gmail.com-f107a3?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rakshaksujith@gmail.com)
[![GPA](https://img.shields.io/badge/GPA-9.80%20%2F%2010.00-ff6b35?style=for-the-badge&logo=academia&logoColor=white)](https://rvce.edu.in)
[![College](https://img.shields.io/badge/RVCE-Bengaluru-00d4ff?style=for-the-badge&logo=googlemaps&logoColor=white)](https://rvce.edu.in)

</div>

---

<div align="center">

```
  I am Loki of Asgard — and I am burdened with glorious purpose.
```

</div>

---

## About Me

```python
class Loki:
    name         = "Rakshak S"
    college      = "RV College of Engineering, Bengaluru"
    degree       = "B.E. Computer Science & Engineering  |  2024 – 2028"
    gpa          = "9.80 / 10.00  (through Sem IV)"
    current_role = "Research Engineer — Samsung PRISM (Elite Track)"

    stack        = ["Systems Programming", "AI/ML", "Kernel Internals",
                    "Distributed Systems", "Security", "Voice AI"]

    building     = "Things that work at the intersection of performance and intelligence."
    philosophy   = "If it doesn't work under pressure, it doesn't work."
```

---

## Experience

<div align="center">

### Samsung PRISM — Research Engineer `Elite Track` | 2025 – 2026

</div>

<table>
<tr>
<td>

**Android Performance Profiling Platform**

Collapsed a manual, multi-tool Android tracing workflow into a one-click job.

- Built a profiling platform: **FastAPI** service over **PostgreSQL** and **MinIO** scheduling **Perfetto**, **Simpleperf**, and **BPFTrace** runs
- **PySide6** worker drives ADB capture, uploads artefacts to S3, streams live job state over **SSE**
- Made multi-gigabyte traces queryable without re-parsing via a disk-cached **Perfetto SQL engine**
- **React / TypeScript (Vite)** dashboard for cross-trace queries and Android NDK Simpleperf reports, with **JWT-scoped workers** isolating every session

</td>
<td align="center" width="260">

![FastAPI](https://img.shields.io/badge/FastAPI-00d4ff?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-7b2ff7?style=flat-square&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-f107a3?style=flat-square&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-ff6b35?style=flat-square&logo=typescript&logoColor=white)
![Perfetto](https://img.shields.io/badge/Perfetto-00d4ff?style=flat-square&logo=android&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-7b2ff7?style=flat-square&logo=jsonwebtokens&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-f107a3?style=flat-square&logo=minio&logoColor=white)
![SSE](https://img.shields.io/badge/SSE-ff6b35?style=flat-square&logo=apacheairflow&logoColor=white)

</td>
</tr>
</table>

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

### AXIOM
**Semantic Runtime Code Intelligence Platform**

`Python` `FastAPI` `PyTorch` `eBPF` `React` `Docker`

Catches cascading failure paths **before deploy** — where static analysis alone sees no runtime behaviour.

- Fused **LLM semantic embeddings** of tree-sitter ASTs across 5 languages with live **eBPF/BCC** kernel syscall traces into a **GNN intent graph**
- Ranked blast radius with **personalized PageRank**
- **ChromaDB** vector search over PostgreSQL trace history
- FastAPI + WebSocket backend feeding a **React/Vite** dashboard and a **VS Code extension** with a live workspace-risk sidebar
- Ships as **Docker Compose** or air-gapped CLI — **50 tests green**

</td>
<td width="50%" valign="top">

### LOKI
**Agentic Voice Desktop Assistant & System Harness**

`Python` `Whisper` `FAISS` `Next.js` `WinRT`

44 modules. One voice. Named after its creator.

- Consolidated **50+ desktop workflows** — WinRT screen OCR, vision Q&A, multi-step automation, **Whisper** transcription, semantic browser-history search, phishing and deepfake detection
- Sentence-level **streaming TTS with barge-in** — speech starts before generation ends
- **Contextual bandit** reranks LLM providers from logged latency and user feedback
- **FAISS + nomic-embed** for long-term semantic recall
- Secrets in **AES-256-GCM** vault behind **PBKDF2** (310 k iterations) — **135 CI tests**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### KubeHeal
**Autonomous Kubernetes Drift & Ransomware Healing**

`PyTorch` `GNN` `Kubernetes` `ONNX` `Prometheus`

Two simultaneous production crises resolved in **under 8 seconds**.

- **GATv2 (3L×8h) + BiLSTM** health model over YAML diffs and 60×15 Prometheus metrics
- **Pre-LN Transformer + Conv1D-SE** security model over 256 Falco syscalls and file-entropy series — both with **conformal confidence intervals**
- Cross-modal **Dependency Correlation Module** — causal chain driving a **5-tier policy** (AUTO-KILL to BENIGN)
- Explained by **SHAP** and natural-language summaries; 3 FastAPI microservices with **RBAC, CRDs**, **ONNX FP16** export

</td>
<td width="50%" valign="top">

### CadForge
**Generative CAD Engine over Model Context Protocol**

`TypeScript` `Python` `MCP` `OpenCASCADE` `npm`

Published `loki-cad-mcp` to npm — real parametric CAD through conversation.

- **11 MCP tools** over JSON-RPC 2.0 — solid creation, fillet / chamfer / shell / boolean / revolve, 9 parametric templates, printability validation, mesh repair
- Export to **STL / STEP / OBJ / GLTF / DXF / SVG**
- Hardened geometry kernel — Zod schemas, path traversal and shell injection rejected, geometry timeouts enforced
- TypeScript MCP server over persistent Python **CadQuery / OpenCASCADE + trimesh** — MIT-licensed, **GitHub Actions CI**

</td>
</tr>
</table>

---

## Achievements

<div align="center">

| Competition | Result | Project |
|---|---|---|
| Honeywell Designathon 2025 | **3rd Place — top 3 of 200+ teams nationwide** | **ReqCluster** — unstructured requirement docs into reviewed, traceable clusters via SBERT + UMAP + HDBSCAN, LLM enrichment, human-in-the-loop overrides, one-click MBSE export (ReqIF / SysML / Jama) |

</div>

---

## Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-7b2ff7?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-f107a3?style=for-the-badge&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-ff6b35?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-00d4ff?style=for-the-badge&logo=javascript&logoColor=white)
![C](https://img.shields.io/badge/C-7b2ff7?style=for-the-badge&logo=c&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-f107a3?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-ff6b35?style=for-the-badge&logo=gnubash&logoColor=white)
![Embedded C](https://img.shields.io/badge/Embedded%20C-00d4ff?style=for-the-badge&logo=c&logoColor=white)

**ML & AI**

![PyTorch](https://img.shields.io/badge/PyTorch-7b2ff7?style=for-the-badge&logo=pytorch&logoColor=white)
![GNNs](https://img.shields.io/badge/GNNs%20(torch--geometric)-f107a3?style=for-the-badge&logo=graphql&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-ff6b35?style=for-the-badge&logo=huggingface&logoColor=white)
![LLMs](https://img.shields.io/badge/LLMs%20%2F%20RAG-00d4ff?style=for-the-badge&logo=openai&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-7b2ff7?style=for-the-badge&logo=meta&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX%20Runtime-f107a3?style=for-the-badge&logo=onnx&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-ff6b35?style=for-the-badge&logo=scipy&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper-00d4ff?style=for-the-badge&logo=openai&logoColor=white)

**Systems & Security**

![eBPF](https://img.shields.io/badge/eBPF%20%2F%20BPFTrace-7b2ff7?style=for-the-badge&logo=linux&logoColor=white)
![Perfetto](https://img.shields.io/badge/Perfetto-f107a3?style=for-the-badge&logo=android&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-ff6b35?style=for-the-badge&logo=linux&logoColor=white)
![Android NDK](https://img.shields.io/badge/Android%20NDK%20%2F%20ADB-00d4ff?style=for-the-badge&logo=android&logoColor=white)
![OAuth](https://img.shields.io/badge/OAuth%202.0-7b2ff7?style=for-the-badge&logo=auth0&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-f107a3?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![AES](https://img.shields.io/badge/AES--256--GCM-ff6b35?style=for-the-badge&logo=letsencrypt&logoColor=white)

**Backend & Cloud**

![FastAPI](https://img.shields.io/badge/FastAPI-00d4ff?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-7b2ff7?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-f107a3?style=for-the-badge&logo=kubernetes&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-ff6b35?style=for-the-badge&logo=nodedotjs&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-00d4ff?style=for-the-badge&logo=socketdotio&logoColor=white)
![MCP](https://img.shields.io/badge/Model%20Context%20Protocol-7b2ff7?style=for-the-badge&logo=anthropic&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-f107a3?style=for-the-badge&logo=prometheus&logoColor=white)
![Microservices](https://img.shields.io/badge/Microservices-ff6b35?style=for-the-badge&logo=apachekafka&logoColor=white)

**Data & Frontend**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-00d4ff?style=for-the-badge&logo=postgresql&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-7b2ff7?style=for-the-badge&logo=databricks&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO%20(S3)-f107a3?style=for-the-badge&logo=amazons3&logoColor=white)
![React](https://img.shields.io/badge/React-ff6b35?style=for-the-badge&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-00d4ff?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7b2ff7?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind%20CSS-f107a3?style=for-the-badge&logo=tailwindcss&logoColor=white)

</div>

---

## GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=PRATHVI9607&show_icons=true&theme=radical&include_all_commits=true&count_private=true&border_radius=12&hide_border=false"/>
&nbsp;&nbsp;
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=PRATHVI9607&layout=compact&langs_count=8&theme=radical&border_radius=12&hide_border=false"/>

<br/><br/>

[![GitHub Streak](https://streak-stats.demolab.com?user=PRATHVI9607&theme=radical&border_radius=12&date_format=j%20M%5B%20Y%5D)](https://github.com/PRATHVI9607)

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=PRATHVI9607&theme=redical&bg_color=ffffff&color=7b2ff7&line=f107a3&point=ff6b35&area=true&hide_border=false&radius=12)](https://github.com/PRATHVI9607)

</div>

---

## Currently Exploring

```
  Advanced kernel internals and eBPF observability at scale
  Graph Neural Networks for distributed system fault prediction
  Agentic AI with long-term memory and autonomous self-improvement
  Model Context Protocol ecosystem and production tooling
  Conformal prediction for uncertainty-aware ML in production
```

---

## Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-PRATHVI9607-7b2ff7?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PRATHVI9607)
[![Email](https://img.shields.io/badge/Email-rakshaksujith@gmail.com-f107a3?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rakshaksujith@gmail.com)
[![Phone](https://img.shields.io/badge/Phone-%2B91%2099456%2097063-ff6b35?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:+919945697063)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00d4ff,30:7b2ff7,60:f107a3,100:ff6b35&height=130&section=footer&text=The%20Tesseract%20has%20shown%20me%20so%20much.&fontSize=18&fontColor=ffffff&fontAlignY=65&animation=fadeIn" />

</div>
