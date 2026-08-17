<h1 align="center">Yousef Hossam</h1>

<h3 align="center">AI Engineer — grounded LLM systems, real-time computer vision, production backends</h3>

<p align="center">
  I build AI that has to be right: retrieval that refuses to answer without sources,<br>
  agents that cannot act without your agreement, and trackers that run in real time on a CPU.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/yousef-hossam/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://github.com/Yousef-7ossam">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="mailto:yousef7hossam778@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Yousef-7ossam&style=flat-square&color=0A66C2&label=Profile+views" alt="Profile views">
</p>

---

## About

I work on the part of AI that decides whether a system can be trusted in production.

Most of my recent work is a healthcare platform where an AI assistant answers questions
about real patient data. That constraint shaped how I build: the language model never
touches the database, it can only request a named tool the backend decides it may use;
general medical answers come only from approved, human-reviewed sources with verified
citations; and nothing gets booked or cancelled without explicit agreement from the person
in a later turn, matched against the exact action that was proposed.

The same instinct shows up in my computer vision work — a multi-object tracker written
from the algorithm up rather than pulled from a library, so every association decision is
one I can explain and tune.

I work in **Arabic and English**, and I build AI systems that do the same.

---

## What I Specialize In

<table>
  <tr>
    <th align="left">Area</th>
    <th align="left">What I Build</th>
    <th align="left">Core Tech</th>
  </tr>
  <tr>
    <td><b>Grounded RAG</b></td>
    <td>Retrieval pipelines that cite their sources and refuse when the corpus has nothing relevant — no context, no model call</td>
    <td>Custom chunking, embeddings, cosine retrieval, citation verification</td>
  </tr>
  <tr>
    <td><b>Tool-Calling Agents</b></td>
    <td>Role-scoped agents where identity is injected server-side and write actions pass a two-turn confirmation gate</td>
    <td>Bounded agent loops, tool schemas, RBAC, provider-agnostic LLM facade</td>
  </tr>
  <tr>
    <td><b>AI Safety Layers</b></td>
    <td>Validation over every model answer — emergency detection, fabricated-citation checks, dose and diagnosis flagging</td>
    <td>Prompt libraries, response validators, provider-independent pre-checks</td>
  </tr>
  <tr>
    <td><b>Computer Vision</b></td>
    <td>Real-time multi-object detection and tracking on commodity CPU hardware</td>
    <td>YOLOv8, ONNX Runtime, Kalman filtering, appearance re-ID, OpenCV</td>
  </tr>
  <tr>
    <td><b>Production Backends</b></td>
    <td>REST APIs with role-based access control, database-level integrity guarantees and real test coverage</td>
    <td>Django, DRF, PostgreSQL, pytest, Docker</td>
  </tr>
  <tr>
    <td><b>Bilingual AI</b></td>
    <td>Systems that retrieve, reason and answer in Arabic and English, including mixed-script input in one turn</td>
    <td>Arabic normalisation, bilingual tokenisation, Arabic-Indic digit handling</td>
  </tr>
</table>

---

## Tech Stack

### Generative AI / LLM

![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white)
![Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![OpenAI Compatible](https://img.shields.io/badge/OpenAI--Compatible%20APIs-412991?style=for-the-badge&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-1A73E8?style=for-the-badge)
![Tool Calling](https://img.shields.io/badge/Tool%20Calling-6C3483?style=for-the-badge)
![Prompt Engineering](https://img.shields.io/badge/Prompt%20Engineering-0F766E?style=for-the-badge)

### Computer Vision

![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)
![ONNX Runtime](https://img.shields.io/badge/ONNX%20Runtime-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Tesseract OCR](https://img.shields.io/badge/Tesseract%20OCR-2C7A7B?style=for-the-badge)
![Kalman Filter](https://img.shields.io/badge/Kalman%20Filtering-455A64?style=for-the-badge)
![Multi-Object Tracking](https://img.shields.io/badge/Multi--Object%20Tracking-B7472A?style=for-the-badge)

### Backend

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/Django%20REST%20Framework-A30000?style=for-the-badge&logo=django&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20APIs-25A162?style=for-the-badge)
![RBAC](https://img.shields.io/badge/RBAC%20%26%20AuthZ-374151?style=for-the-badge)

### Data

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Vector Search](https://img.shields.io/badge/Vector%20Search-7B1FA2?style=for-the-badge)

### DevOps & Tools

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## Featured Projects

### Roshada — Connected Healthcare Platform with a Grounded AI Assistant

<a href="https://github.com/Yousef-7ossam/Roshada">
  <img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Roshada repository">
</a>

<p>
  <img src="https://img.shields.io/github/languages/top/Yousef-7ossam/Roshada?style=flat-square&color=3776AB" alt="Top language">
  <img src="https://img.shields.io/github/stars/Yousef-7ossam/Roshada?style=flat-square&color=181717&logo=github" alt="Stars">
  <img src="https://img.shields.io/github/last-commit/Yousef-7ossam/Roshada?style=flat-square&color=2EA043" alt="Last commit">
</p>

A healthcare platform where patients, doctors, laboratories, radiology centres and
pharmacies share one set of appointments, records and prescriptions — with an AI assistant
that answers from the platform's own data and an approved medical knowledge base.

**The problem.** A single course of care crosses four organisations, each on a different
system. The patient ends up carrying the information between them from memory, doctors
prescribe without knowing what's obtainable nearby, and released reports reach patients
only when someone remembers.

**What I built.**

- **Grounded RAG built in-repo** — parsing, chunking, embedding, storage and retrieval,
  with no LangChain or LlamaIndex. If retrieval returns nothing relevant, the model is
  never called and a fixed refusal is returned. Citations are checked against what was
  actually sent; a fabricated source number marks the answer degraded rather than being
  silently edited.
- **Role-scoped tool-calling agent** — 14 tools, gated by role. No tool schema contains a
  person identifier, so a patient cannot express a question about another patient. Write
  actions require agreement in a *later* turn, matched against the exact proposed action
  and arguments.
- **The LLM never reaches the database.** It requests a named tool; the backend decides
  whether that tool exists for the caller and injects the authenticated identity itself.
- **AI safety layer** — emergency detection that runs before and independently of the
  provider, dose/diagnosis flagging, and validation over every answer.
- **Bilingual Arabic/English** retrieval, reasoning and confirmation handling.
- **National-ID OCR** using Tesseract and a YOLO field detector to auto-fill signup.
- **1132 tests passing** across 20 modules, run against real PostgreSQL — never SQLite —
  so the suite exercises the same constraints production relies on.

`Python` · `Django 5.2` · `DRF` · `PostgreSQL` · `Streamlit` · `Groq` · `RAG` · `Tool-Calling Agents` · `Docker` · `pytest`

<br>

### ByteTrack++ — Real-Time CPU Multi-Person Tracker

<a href="https://github.com/Yousef-7ossam/ByteTrack-Plus-Plus-Person-Tracker">
  <img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="ByteTrack++ repository">
</a>

<p>
  <img src="https://img.shields.io/github/languages/top/Yousef-7ossam/ByteTrack-Plus-Plus-Person-Tracker?style=flat-square&color=3776AB" alt="Top language">
  <img src="https://img.shields.io/github/stars/Yousef-7ossam/ByteTrack-Plus-Plus-Person-Tracker?style=flat-square&color=181717&logo=github" alt="Stars">
  <img src="https://img.shields.io/github/last-commit/Yousef-7ossam/ByteTrack-Plus-Plus-Person-Tracker?style=flat-square&color=2EA043" alt="Last commit">
</p>

A real-time multi-person detection and tracking system that runs entirely on CPU,
combining YOLOv8 ONNX inference with a from-scratch implementation of the ByteTrack
association algorithm.

**The problem.** Multi-object tracking usually assumes a GPU. Getting persistent, stable
identities on commodity CPU hardware means the association logic itself has to do the work
that compute would otherwise paper over.

**What I built.**

- **Two-stage ByteTrack association** — high-confidence detections match tracks first,
  then unmatched tracks are offered to low-confidence detections, recovering objects a
  single-threshold tracker would drop.
- **Kalman filtering** with a constant-velocity model for smooth box prediction.
- **Appearance re-identification** via HSV colour histograms, recovering lost track IDs
  after occlusion instead of spawning a new one.
- **Motion estimation** classifying each person as approaching, receding or moving
  directionally, using bounding-box height as a depth proxy.
- **Robot follow mode** — click-to-lock a target and generate steering commands from
  horizontal offset and depth.

`Python` · `YOLOv8` · `ONNX Runtime` · `OpenCV` · `NumPy` · `Kalman Filter` · `Re-ID`

---

## GitHub Statistics

<p align="center">
  <img height="190" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Yousef-7ossam&theme=github_dark" alt="Top languages by commit">
  <img height="190" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Yousef-7ossam&theme=github_dark" alt="Repositories per language">
</p>

---

## Current Focus

- **Retrieval that scales** — moving from exhaustive cosine scan to approximate nearest
  neighbour, and making grounding conversation-aware so follow-up questions keep their
  referent.
- **Agent reliability** — tightening the confirmation gate and expanding role-scoped tool
  coverage without widening what a model can express.
- **Evaluation** — measuring grounded answers the way they should be measured: citation
  faithfulness and refusal correctness, not just fluency.
- **Deployment** — taking the container setup to a real production environment.

---

## Connect

<p align="center">
  <a href="https://www.linkedin.com/in/yousef-hossam/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:yousef7hossam778@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://github.com/Yousef-7ossam">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
</p>

<p align="center">
  <i>Open to AI/ML engineering opportunities — LLM systems, computer vision, and applied AI in production.</i>
</p>
