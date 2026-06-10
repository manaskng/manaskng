<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=26&pause=1000&color=FFFFFF&center=true&vCenter=true&width=650&lines=Manas+Raj;SDE+%7C+DTU+CSE;Full+Stack+%7C+Machine+Learning+%7C+Compilers;Generative+AI+%7C+Agentic+AI+Systems;LeetCode+Knight+%E2%80%94+Top+2%25+%7C+Rating+2051" alt="Typing SVG" />
</div>

<div align="center">
  <a href="https://www.linkedin.com/in/manas-raj-a9293330b/">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:manasraj850@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/manaskng">
    <img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white" />
  </a>
  <a href="https://leetcode.com/Manas_RJ1024/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?logo=leetcode&logoColor=white" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=manaskng&color=blueviolet&style=flat" />
</div>

---

## About

B.Tech Computer Engineering student at **Delhi Technological University (DTU)** — CGPA 9.105.

I build full-stack systems, machine learning pipelines, and compiler tooling. My work spans real-time collaborative applications, ML-powered recommendation engines, neural networks, research paper implementations, and low-level compiler design. Currently exploring **Generative AI**, **RAG pipelines**, and **Agentic AI systems**.

- 🏆 **Goldman Sachs India Hackathon 2026** — 100/100, Rank 1 across 15,000+ submissions
- ⚔️ **LeetCode Knight** — Top 2%, Rating 2051, 800+ problems solved
- 📘 **AlgoUniversity DP Camp** — Top 2.5% of 40,000 participants under Codeforces Master mentorship
- 🔬 **Open Source** — Contributor to Vibe (IIT Ropar ed-tech platform), PR #972
- 🎓 **IIT Ropar** — Winter Intern 2026

---

## Projects

### [Relay](https://github.com/manaskng/DevNexus) — Collaborative Developer Workspace · [Live](https://devnexus-app.vercel.app/)
Real-time MERN workspace with collaborative coding sandbox, AI-assisted workflows, and high-performance search.
- Socket.IO collaborative editor with presence indicators, typing awareness, and session-scoped activity logs
- Gemini API integration for AI-assisted code explanation and refactoring
- MongoDB Atlas Search — sub-10ms query latency, ~40% query performance improvement
- Docker deployment, JWT auth, role-scoped access

`MERN` `Socket.IO` `MongoDB Atlas Search` `Gemini API` `JWT` `Docker` `Vercel`

---

### [Evenix](https://github.com/manaskng/Dev-Event_Sync) — ML-Powered Event Discovery, Recommendation & Booking · [Live](https://dev-event-sync.vercel.app)
Full-stack platform aggregating tech events and college societies with personalised ML recommendations.
- Hybrid recommendation microservice — TF-IDF + collaborative filtering via FastAPI + scikit-learn
- Cold-start handling via graceful fallback; adaptive personalisation over user behaviour
- Race-condition-free booking engine using MongoDB atomic operations — 100% write consistency
- NextAuth v5 OAuth, optimistic UI updates, role-aware access control, dynamic OpenGraph images

`Next.js` `TypeScript` `Python` `FastAPI` `scikit-learn` `MongoDB` `Tailwind CSS` `Cloudinary`

---

### [MiniC Compiler](https://github.com/manaskng/minic-compiler) — C-Subset Compiler *
Multi-stage compiler for a C subset, written in C++.
- Hand-written recursive-descent parser, AST construction, semantic analysis (type checking, scope resolution)
- 3-address IR (TAC) with basic-block CFG construction
- Optimizations — constant folding, dead-code elimination, copy propagation (~25% instruction reduction)
- GDB-compatible debug-info emitter (DWARF stubs) and symbol-table-driven linker helper
- 100+ pytest test cases covering pointer arithmetic, nested scopes, register spilling

`C++17` `CMake` `pytest` `DWARF`

---

### Bank Customer Churn Prediction — ANN with TensorFlow & Keras
Neural network model predicting customer churn on 10,000 bank records.
- 3-layer ANN (64→32→16 neurons) — 86.2% accuracy, AUC-ROC 0.87
- Applied Dropout, Batch Normalization, L2 regularization with EarlyStopping and ReduceLROnPlateau
- Threshold optimization (0.3–0.7), permutation importance analysis, optimizer comparison (Adam vs SGD vs RMSprop)
- Identified Age, NumOfProducts, ActiveMember as top churn predictors — projected $4M+ annual retention saving

`Python` `TensorFlow` `Keras` `scikit-learn` `Pandas` `Matplotlib` `Seaborn`

---

### Proximity Forest — Time Series Classifier (Research Implementation)
Implementation and analysis of Proximity Forest (Lucas et al., 2019) as part of DTU CS304 Data Warehousing & Mining.
- Ensemble of randomized Proximity Trees benchmarked on 85 UCR Archive datasets
- Reproduced Gini-impurity splitting with stochastic selection from 11 elastic distance measures (DTW, WDTW, LCSS, ERP, TWE, MSM) sampled per-node — eliminated O(n²) cross-validation overhead
- Validated O(n log n) training and O(log n) classification complexity vs Elastic Ensemble — confirmed 10⁵× speedup on 1M-series SITS dataset
- Produced 32-page technical report with complexity visualisations and critical-difference diagrams

`Python` `NumPy` `scikit-learn` `sktime` `Matplotlib` `Jupyter`

---

## Tech Stack

**Languages**

![C++](https://img.shields.io/badge/C++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-%2300599C.svg?style=flat&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54)
![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E)

**Frontend**

![React](https://img.shields.io/badge/React-%2320232a.svg?style=flat&logo=react&logoColor=%2361DAFB)
![Next.js](https://img.shields.io/badge/Next.js-black?style=flat&logo=next.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-%2338B2AC.svg?style=flat&logo=tailwind-css&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-%23593d88.svg?style=flat&logo=redux&logoColor=white)

**Backend & Infrastructure**

![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=flat&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-%23404d59.svg?style=flat&logo=express&logoColor=%2361DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat&logo=fastapi)
![Socket.io](https://img.shields.io/badge/Socket.io-black?style=flat&logo=socket.io)
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white)

**Databases**

![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=flat&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-%23DD0031.svg?style=flat&logo=redis&logoColor=white)

**AI / ML**

![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=flat&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=flat&logo=keras&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-%23013243.svg?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white)

**Generative AI & Agentic Systems**

![Google Gemini](https://img.shields.io/badge/Gemini%20API-4285F4?style=flat&logo=google&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-000000?style=flat&logo=chainlink&logoColor=white)
![RAG](https://img.shields.io/badge/RAG%20Pipelines-FF6B6B?style=flat)
![Vector Search](https://img.shields.io/badge/Vector%20Search-47A248?style=flat&logo=mongodb&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-%23000000.svg?style=flat&logo=vercel&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat&logo=cmake&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## GitHub & Competitive Programming Stats

<div align="center">
  <img src="https://readme-stats-fast.vercel.app/api?username=manaskng&show_icons=true&theme=dark&include_all_commits=true&count_private=true&hide_border=true" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=manaskng&theme=dark&hide_border=true" width="48%" />
</div>

<br/>

<div align="center">
  <img src="https://leetcard.jacoblin.cool/Manas_RJ1024?ext=heatmap&theme=dark" width="48%" />
  <img src="https://leetcode-stats-six.vercel.app/api?username=Manas_RJ1024&theme=dark" width="48%" />
</div>

---

## Competitive Programming & Achievements

| | |
|---|---|
| 🏆 **Goldman Sachs India Hackathon 2026** | 100/100 · Rank 1 · 15,000+ submissions · Recursive JSON parser in C++ |
| ⚔️ **LeetCode Knight** | Top 2% · Rating 2051 · 800+ problems |
| 📘 **AlgoUniversity DP Camp** | Top 2.5% of 40,000 · Codeforces Master mentorship |
| 🌟 **GDG Solution Challenge** | Certificate of Achievement · AI-driven solution |
| 🔖 **GitHub Badges** | Pull Shark · Starstruck |

---

## Areas of Interest

```
├── Full Stack Engineering       → MERN, Next.js, REST APIs, Real-time Systems (Socket.IO)
├── Machine Learning             → Recommendation Systems, ANN, Time Series Classification
├── Generative AI                → RAG Pipelines, Vector Search, LLM Integration, Embeddings
├── Agentic AI Systems           → Tool-use, Multi-step Reasoning, Agent Orchestration
└── Compiler & Systems Design    → Parsing, AST, IR/CFG, Optimizations, Low-level C++
```

---

## Contribution Activity

<div align="center">
  <img src="https://github.com/manaskng/manaskng/blob/output/github-contribution-grid-snake.svg" alt="Contribution Snake" width="100%" />
</div>

---

<div align="center">
  <i>Open to SDE internships, research collaborations, and open-source contributions.</i>
  <br/><br/>
  <a href="mailto:manasraj850@gmail.com">manasraj850@gmail.com</a>
</div>
