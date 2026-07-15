<div align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=26&pause=1000&color=FFFFFF&center=true&vCenter=true&width=1050&lines=Hi%2C+I%27m+Manas+Raj;SDE+Intern+%40+IIT+Ropar+%7C+LeetCode+Knight+%7C+2051;Full-Stack+Development+%7C+Competitive+Programming;Machine+Learning+%7C+Deep+Learning+%7C+RAG;Systems+Programming" alt="Typing SVG" />
</div>

<div align="center">
<a href="https://www.linkedin.com/in/manas-raj-a9293330b/"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" /></a>
<a href="mailto:manasraj850@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" /></a>
<a href="https://github.com/manaskng"><img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white" /></a>
<a href="https://leetcode.com/Manas_RJ1024/"><img src="https://img.shields.io/badge/LeetCode-FFA116?logo=leetcode&logoColor=white" /></a>
<img src="https://komarev.com/ghpvc/?username=manaskng&color=blueviolet&style=flat" />
</div>

<br/>

## 👨‍💻 About Me

Computer Engineering student at **Delhi Technological University (DTU)** — CGPA **9.13**.

I build high-performance software across systems programming, distributed systems, AI, and full-stack engineering. Recent work spans a **zero-dependency DPI engine at 438K pkt/s**, a **RAG-powered collaborative developer platform**, an **async ML opportunity aggregator**, and a **recursive-descent compiler**.

**Current focus**
- **Systems** — DPI, packet analysis, low-level C++17
- **Agentic AI** — RAG pipelines, vector search, LLM orchestration
- **Compilers** — parsing, IR, CFG optimizations
- **Distributed systems** — microservices, async ETL, caching layers

---

## 🚀 Featured Projects

<table>
<tr>
<th width="50%">🛡️ PacketSentinel</th>
<th width="50%">🔗 Relay</th>
</tr>
<tr>
<td valign="top">

**Multi-threaded Deep Packet Inspection & Malware Detection Engine**

- **438K pkt/s** via lock-free pipeline (FNV-1a sharding), zero mutex contention on the hot path
- Byte-level TLS SNI / HTTP Host / DNS parsing via `std::string_view`, zero heap allocs
- Shannon entropy + Welford variance anomaly in O(1) memory; Random Forest **97% precision**
- **1.7× speedup** over baseline; classifies **15+ app types** from live traffic

<sub>`C++17` · `Python` · `scikit-learn` · `libpcap` · `Scapy` · `CMake`</sub>

<a href="https://github.com/manaskng/PacketSentinel">Code</a> · <a href="https://packet-sentinel.vercel.app">Live</a>

</td>
<td valign="top">

**Adaptive RAG-Powered Collaborative Developer Ecosystem**

- Custom RAG: **768-dim Gemini embeddings** + Atlas Vector Search, **sub-50ms** retrieval across 10K+ docs (**60× over regex**)
- Real-time collab editor (Socket.IO), **11 compiled languages**, dual-compiler failover, **50+ rooms**
- Redis sliding-window rate limiter + dual Gemini model failover
- **40+ REST endpoints**, Dockerized CI/CD, MongoDB TTL auto-purge

<sub>`MERN` · `Socket.IO` · `Redis` · `Gemini API` · `Docker` · `Vector Search`</sub>

<a href="https://github.com/manaskng/DevNexus">Code</a> · <a href="https://devnexus-app.vercel.app">Live</a>

</td>
</tr>
<tr>
<th>🔍 OppLens</th>
<th>⚙️ AstraC Compiler</th>
</tr>
<tr>
<td valign="top">

**Distributed Opportunity Aggregator & ML Recommendation Engine**

- Fault-tolerant Playwright ETL across **5 platforms**, **5K+ opps/week**; composite-key hashing cuts writes **~95%**
- Atlas Vector Search (HNSW): O(N) → O(log N), **~10× speedup**; sentence-transformers dedup
- Hybrid recommender — TF-IDF + Collaborative Filtering + Vector Search in a FastAPI microservice
- Redis cache: p95 inference **400ms → <80ms** (80% reduction)

<sub>`Next.js` · `FastAPI` · `Python` · `sentence-transformers` · `Redis` · `Playwright`</sub>

<a href="https://github.com/manaskng/opp-lens">Code</a> · <a href="https://dev-event-sync.vercel.app">Live</a>

</td>
<td valign="top">

**C-Subset Recursive-Descent Compiler**

- Hand-written recursive-descent parser → AST → semantic analysis (type checking, scope resolution)
- 3-address IR (TAC) with basic-block CFG — constant folding, DCE, copy propagation → **~25% fewer instructions**
- 100+ pytest cases: pointer arithmetic, nested scopes, register spilling
- Symbol-table-driven linker helper across translation units

<sub>`C++17` · `CMake` · `pytest`</sub>

<a href="https://github.com/manaskng/MiniC_Compiler">Code</a>

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

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
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)

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

</div>

---

## 📊 GitHub & Competitive Programming Stats

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

## 🏆 Competitive Programming & Achievements

| | | |
|---|---|---|
| 🥇 | **Goldman Sachs India Hackathon 2026** | Rank 1 · 100/100 · 15,000+ submissions · Recursive JSON→TypeScript parser in C++ |
| ⚔️ | **LeetCode Knight** | Top 2% · Rating 2051 · 800+ problems · Rank 307/35,237 (Biweekly 174) |
| 📘 | **AlgoUniversity DP Camp** | Top 2.5% of 40,000 · Codeforces Master mentorship |
| 🎓 | **SDE Intern @ IIT Ropar** | Vicharanashala Lab · 2 merged PRs · Setup pipeline + UI bug fix |
| 🌟 | **GDG Solution Challenge 2025** | Certificate of Achievement · AI-driven solution |
| 🔖 | **GitHub Badges** | Pull Shark · Starstruck |

---

## 🐍 Contribution Activity

<div align="center">
<img src="https://github.com/manaskng/manaskng/blob/output/github-contribution-grid-snake.svg" alt="Contribution Snake" width="100%" />
</div>

---

<div align="center">
<i>Open to SDE internships, research collaborations, and open-source contributions.</i>
<br/><br/>
<a href="mailto:manasraj850@gmail.com">manasraj850@gmail.com</a>
</div>
