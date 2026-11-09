<!--
Siddh Jain (@nls-forev) profile README
-->

<div align="center">

  <a href="https://linkedin.com/in/siddh-jain-aiml" target="_blank">
    <img src="assets/header.svg" width="100%" alt="Siddh Jain header banner"/>
  </a>

  <a href="https://github.com/nls-forev">
    <img src="assets/typing_headline.svg" width="820" height="54" alt="Terminal-Bench 2 and 3 task author, AI evaluation and red-teaming, RAG systems and LLM fine-tuning"/>
  </a>

  <p align="center">
    <strong>Bengaluru, India 🇮🇳</strong> &nbsp;|&nbsp;
    <strong>AI Trainer @ Handshake AI</strong> &nbsp;|&nbsp;
    <strong>I build Terminal-Bench tasks, then find where frontier agents break</strong>
  </p>

  <p align="center">
    <img src="https://img.shields.io/badge/Terminal--Bench-2%20%26%203%20Task%20Author-00C7B7?style=for-the-badge&logo=gnubash&logoColor=white" alt="Terminal-Bench"/>
    <img src="https://img.shields.io/badge/Task%20Code-40K%2B%20Lines-7C3AED?style=for-the-badge&logo=checkmarx&logoColor=white" alt="Task code"/>
    <img src="https://img.shields.io/badge/Agent%20Trials-700%2B%20Run%20%26%20Read-FF0055?style=for-the-badge&logo=target&logoColor=white" alt="Agent Trials"/>
    <img src="https://img.shields.io/badge/Harbor-Agent%20Eval%20Harness-38D39F?style=for-the-badge&logo=gnubash&logoColor=white" alt="Harbor"/>
    <img src="https://img.shields.io/badge/Docker-Sandboxed%20Environments-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
    <img src="https://img.shields.io/badge/Verifiers-Deterministic%20pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="Verifiers"/>
  </p>

  <p align="center">
    <a href="https://linkedin.com/in/siddh-jain-aiml" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
    <a href="mailto:rj07605@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
    <a href="https://github.com/nls-forev"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
    <a href="https://hf.co/spaces/Klasta/curarag" target="_blank"><img src="https://img.shields.io/badge/Live%20Demo-CuraRAG%20on%20HF%20Spaces-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Live Demo"/></a>
    <a href="https://x.com/SiddhJainUX" target="_blank"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"/></a>
  </p>

  <p align="center">
    <img src="assets/terminal_card.svg" width="100%" alt="Siddh Jain terminal card"/>
  </p>

  <p align="center">
    <img src="assets/animated_kpis.svg" width="100%" alt="20+ tasks built, 850+ harness runs, 40K+ lines of task code, 300+ commits, 100+ verifier tests, 10 task categories"/>
  </p>

</div>

---

### 🌟 Overview

> **Terminal-Bench 2 & 3 task author: 20+ tasks, 850+ harness runs, 40K+ lines of task code.** Since June 2026 I've written tasks for **Terminal-Bench 2 and 3** in the Handshake AI Fellowship. Each task is a hard, realistic engineering job that an AI agent must finish on its own in a Linux terminal, inside a Docker container, graded by deterministic tests on what it leaves on disk.
>
> I build every part: the environment and seed data, the instruction, the oracle solution, and the verifier. Then I calibrate. The oracle has to score 1.0, a do-nothing agent has to score 0.0, and frontier agents have to fail most of their runs. I've run **700+ agent trials** and read the transcripts to find the exact step where each model went wrong, then hardened the task until the failures were real and fair.
>
> Outside Terminal-Bench I build and evaluate LLM systems: a clinical RAG app with verified citations, and a QLoRA fine-tune of Llama-3.1-8B checked with blind pairwise judging.

---

### 🧪 Terminal-Bench task categories I've built in

<p align="center">
  <img src="https://img.shields.io/badge/ML%20Training-%26%20ML%20Infrastructure-FF6F00?style=for-the-badge&logo=pytorch&logoColor=white" alt="ML Training"/>
  <img src="https://img.shields.io/badge/Machine%20Learning-%26%20AI-7C3AED?style=for-the-badge&logo=tensorflow&logoColor=white" alt="Machine Learning"/>
  <img src="https://img.shields.io/badge/Systems-Infrastructure%20%26%20Operations-326CE5?style=for-the-badge&logo=linux&logoColor=white" alt="Systems"/>
  <img src="https://img.shields.io/badge/Data%20Processing-%26%20ETL-10B981?style=for-the-badge&logo=apacheairflow&logoColor=white" alt="Data Processing"/>
  <img src="https://img.shields.io/badge/Build%20%26%20Release-Dependency%20Management-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Build & Release"/>
  <img src="https://img.shields.io/badge/File%20%26%20Media-Operations-E11D48?style=for-the-badge&logo=ffmpeg&logoColor=white" alt="File & Media"/>
  <img src="https://img.shields.io/badge/Security-AppSec-DC2626?style=for-the-badge&logo=owasp&logoColor=white" alt="Security"/>
  <img src="https://img.shields.io/badge/Software-Engineering-0EA5E9?style=for-the-badge&logo=gnubash&logoColor=white" alt="Software"/>
  <img src="https://img.shields.io/badge/Scientific%20Computing-Domain%20Science-8B5CF6?style=for-the-badge&logo=numpy&logoColor=white" alt="Scientific Computing"/>
  <img src="https://img.shields.io/badge/Hardware-Embedded%20%26%20Low--Level-64748B?style=for-the-badge&logo=arm&logoColor=white" alt="Hardware"/>
</p>

### 🧭 What building them taught me

- **Never ship anything an agent can test guesses against.** Tasks that shipped a checksum or hash got dropped, because agents spent their runs testing guesses against it and timed out. The accepted ones grade the files the agent produces.
- **An obscure fact doesn't make a task hard.** An fp16 loss-scaling rule a model got wrong three times out of three was solved 2 of 2 once the task named the release, because the agent fetched the source and read it.
- **Agents settle early on what counts as evidence.** They decide which files matter in the first few steps, then miss a deciding value in a column they already wrote off. That was the one weakness that held up in my probes.
- **Read the transcript before trusting the score.** One model's trace showed my own answer key was wrong, and I fixed the key.

---

### 🎭 What I work on

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>💻 Terminal-Bench & agent evaluation</h4>
      <ul>
        <li><strong>20+ tasks built</strong> for Terminal-Bench 2 and 3 across <strong>10 categories</strong>, covering ML training, systems, data pipelines and security.</li>
        <li>Ran <strong>700+ agent trials</strong> in sandboxed Docker and read the transcripts to find the step where each model went wrong.</li>
        <li>Deterministic pytest graders that check the files an agent produces and ignore how it got there.</li>
        <li>A local Docker harness that cuts a task calibration cycle from hours to about <strong>15 minutes</strong>.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🎯 Red-teaming & eval design</h4>
      <ul>
        <li>Found that models decide early which files count as evidence, then miss a deciding value in a column they've written off. I use this to design harder tasks.</li>
        <li>Screened candidate facts by asking a model each one cold, three times, and dropped any it already knew.</li>
        <li>Hand-built golden sets, LLM-as-judge with independent citation checks, and rubrics that grade correctness instead of length.</li>
        <li>Blind pairwise evals judged in both orders to cancel position bias.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🧠 LLM engineering</h4>
      <ul>
        <li>Hybrid retrieval: BM25 plus Qdrant dense vectors, fused with Reciprocal Rank Fusion, then cross-encoder reranking over 1,800+ chunks.</li>
        <li>QLoRA fine-tuning of Llama-3.1-8B on <strong>52K instructions</strong> on a single A10G GPU.</li>
        <li>Typed FastAPI services deployed on Hugging Face Spaces.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🚢 ML, MLOps & research</h4>
      <ul>
        <li>Physics-informed models (DeepONet, PINN) for GNSS ionospheric correction at IIT Tirupati, <strong>~0.7 TECU RMSE</strong>.</li>
        <li>A pipeline that turned raw RINEX files into a <strong>~760K-sample</strong> training set.</li>
        <li>Train, gate, deploy, drift-check and retrain loops with GitHub Actions, MLflow, DVC and Evidently.</li>
      </ul>
    </td>
  </tr>
</table>

---

### ⚡ How a Terminal-Bench task gets built

<p align="center">
  <img src="assets/agentic_pipeline.svg" width="100%" alt="Task pipeline: real job, environment, oracle and tests, agent trials, transcripts, accepted"/>
</p>

---

### 🛠️ Tech stack

<div align="center">

  <p align="center">
    <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,fastapi,django,docker,linux,bash,git,githubactions,aws,mongodb,redis,postgres,vscode&theme=dark" alt="Tech stack"/></a>
  </p>

#### 💻 Terminal-Bench, agent evaluation & red-teaming
<p>
  <img src="https://img.shields.io/badge/Terminal--Bench-2%20%26%203%20Task%20Author-00C7B7?style=for-the-badge&logo=gnubash&logoColor=white" alt="Terminal-Bench"/>
  <img src="https://img.shields.io/badge/Harbor-Agent%20Eval%20Harness-38D39F?style=for-the-badge&logo=gnubash&logoColor=white" alt="Harbor"/>
  <img src="https://img.shields.io/badge/Adversarial%20Red--Teaming-Failure%20Analysis-FF0055?style=for-the-badge&logo=target&logoColor=white" alt="Adversarial Red-Teaming"/>
  <img src="https://img.shields.io/badge/Deterministic%20Graders-pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="Deterministic Graders"/>
  <img src="https://img.shields.io/badge/Golden%20Sets-LLM--as--Judge-7C3AED?style=for-the-badge&logo=openai&logoColor=white" alt="Golden Sets"/>
  <img src="https://img.shields.io/badge/Blind%20Pairwise%20Evals-Position--Bias%20Free-F97316?style=for-the-badge&logo=codeforces&logoColor=white" alt="Blind Pairwise Evals"/>
</p>

#### 🧠 LLMs, RAG & fine-tuning
<p>
  <img src="https://img.shields.io/badge/Hugging%20Face-Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face"/>
  <img src="https://img.shields.io/badge/QLoRA-PEFT%20%7C%20TRL%20%7C%20Unsloth-F59E0B?style=for-the-badge&logo=pytorch&logoColor=white" alt="QLoRA"/>
  <img src="https://img.shields.io/badge/Qdrant-Vector%20Search-DC244C?style=for-the-badge&logo=qdrant&logoColor=white" alt="Qdrant"/>
  <img src="https://img.shields.io/badge/Hybrid%20Retrieval-BM25%20%2B%20Dense%20%2B%20RRF-3B82F6?style=for-the-badge&logo=elasticsearch&logoColor=white" alt="Hybrid Retrieval"/>
  <img src="https://img.shields.io/badge/LangChain-LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/Cross--Encoder-Reranking-10B981?style=for-the-badge&logo=semanticweb&logoColor=white" alt="Cross-Encoder"/>
</p>

#### 🚢 MLOps, containers & cloud
<p>
  <img src="https://img.shields.io/badge/Docker-Sandboxed%20Environments-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/MLflow-Tracking-0194E2?style=for-the-badge&logo=mlflow&logoColor=white" alt="MLflow"/>
  <img src="https://img.shields.io/badge/Weights%20%26%20Biases-Experiments-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black" alt="Weights & Biases"/>
  <img src="https://img.shields.io/badge/DVC-Data%20Versioning-13ADC7?style=for-the-badge&logo=dvc&logoColor=white" alt="DVC"/>
  <img src="https://img.shields.io/badge/AWS-EC2%20GPU%20%7C%20S3-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS"/>
</p>

#### ⚡ Languages & data
<p>
  <img src="https://img.shields.io/badge/Python-PyTorch%20%7C%20scikit--learn-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/SQL-PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL"/>
  <img src="https://img.shields.io/badge/Bash-Linux%20CLI-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash"/>
  <img src="https://img.shields.io/badge/C-Systems-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C"/>
  <img src="https://img.shields.io/badge/XGBoost-ONNX-EB5424?style=for-the-badge&logo=onnx&logoColor=white" alt="XGBoost"/>
  <img src="https://img.shields.io/badge/MongoDB-Redis-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
</p>

</div>

---

### 💼 Journey & impact

| When | Role | What I did |
| :--- | :--- | :--- |
| **Jun 2026 - now** | **AI Trainer, Handshake AI Fellowship** | Terminal-Bench 2 and 3 task author: **20+ tasks** across 10 categories, **850+ harness runs**, **40K+ lines** of task code |
| **May 2026** | **BCA, Artificial Intelligence, Jain University** | CGPA 8.84 / 10 |
| **Jul - Dec 2025** | **ML Intern, IIT Tirupati** | Physics-informed GNSS models at **~0.7 TECU RMSE**, a 760K-sample training pipeline |

#### 🏛️ Results in numbers
- 💻 **20+ Terminal-Bench tasks:** hard terminal problems with deterministic graders, built to make frontier agents fail most of the time.
- 🎯 **850+ harness runs, 700+ of them frontier-agent trials:** every failure traced to the step where the model's reasoning broke.
- 🧱 **40K+ lines of task code and 300+ commits:** Docker environments, oracle solutions, data generators and 100+ deterministic verifier tests.
- 🧪 **10 task categories:** ML training and infrastructure, systems operations, data and ETL, build and release, security, and five more.
- 🩺 **56/56 golden-set answers:** CuraRAG, with all **12/12** unanswerable questions refused and 90.9% citation accuracy.
- 📈 **30% wins vs 11.5% losses:** TuneForge's fine-tuned Llama-3.1-8B against the base model, blind pairwise, 200 held-out prompts.
- ⚡ **Hours to 15 minutes:** task calibration cycle after I built a local Docker harness.

---

### 🚀 Featured repositories

<div align="center">

| Project | Focus area | Technologies | GitHub link |
| :--- | :--- | :--- | :--- |
| **`cura-rag`** | 🩺 **Clinical RAG with verified citations** | FastAPI, Qdrant, BM25, cross-encoder, LLM judge | [![Repo](https://img.shields.io/badge/Explore-Repo-cyan?style=flat-square&logo=github)](https://github.com/nls-forev/cura-rag) [![Demo](https://img.shields.io/badge/Live-Demo-yellow?style=flat-square&logo=huggingface)](https://hf.co/spaces/Klasta/curarag) |
| **`TuneForge`** | 🧠 **QLoRA fine-tune + blind pairwise eval** | Llama-3.1-8B, PEFT, TRL, Unsloth, A10G | [![Repo](https://img.shields.io/badge/Explore-Repo-blue?style=flat-square&logo=github)](https://github.com/nls-forev/TuneForge) |
| **`FraudGuard`** | 🛡️ **Self-retraining fraud detection MLOps** | XGBoost, ONNX, FastAPI, Evidently, GitHub Actions | [![Repo](https://img.shields.io/badge/Explore-Repo-green?style=flat-square&logo=github)](https://github.com/nls-forev/FraudGuard) |
| **`transformer-from-scratch`** | 📐 **Transformer encoder, module by module** | PyTorch, Jupyter | [![Repo](https://img.shields.io/badge/Explore-Repo-purple?style=flat-square&logo=github)](https://github.com/nls-forev/transformer-from-scratch) |
| **`lstm-autoencoder-anomaly-detection`** | 📉 **Time-series anomaly detection** | PyTorch, seq2seq LSTM | [![Repo](https://img.shields.io/badge/Explore-Repo-orange?style=flat-square&logo=github)](https://github.com/nls-forev/lstm-autoencoder-anomaly-detection) |
| **`kaggle-as-a-live-streaming-server`** | 🎥 **GPU live streaming on Kaggle** | FastAPI, FFmpeg, NVENC, HLS | [![Repo](https://img.shields.io/badge/Explore-Repo-red?style=flat-square&logo=github)](https://github.com/nls-forev/kaggle-as-a-live-streaming-server) |

</div>

---

### ✍️ Writing

**"The Liminal Layers of Deep Learning"** on Medium (July 2026), on why many ResNet blocks learn near-identity mappings and how that solves the degradation problem.

---

### 💬 Connect & collaborate

<div align="center">

Open to Terminal-Bench and agent-evaluation projects: task authoring, task review and red-teaming. I also take on RAG, fine-tuning and eval-set work.

<p align="center">
  <a href="https://linkedin.com/in/siddh-jain-aiml"><img src="https://img.shields.io/badge/LinkedIn-siddh--jain--aiml-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:rj07605@gmail.com"><img src="https://img.shields.io/badge/Email-rj07605%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<img src="assets/footer.svg" width="100%" alt=""/>

</div>
