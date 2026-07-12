<div align="center">
 <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=26&pause=1000&color=FFFFFF&center=true&vCenter=true&width=1050&lines=Hi%2C+I%27m+Manas+Raj;SDE+Intern+%40+IIT+Ropar+%7C+LeetCode+Knight+%7C+2051;Full-Stack+Development+%7C+Competitive+Programming;Machine+Learning+%7C+Deep+Learning+%7C+RAG;Systems+Programming" alt="Typing SVG" />
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

<br/>

---

## About Me

Computer Engineering student at **Delhi Technological University (DTU)** — CGPA **9.105**.

I build high-performance software across systems programming, distributed systems, AI, and full-stack engineering. My recent work spans a **zero-dependency DPI engine at 438K packets/sec**, a **RAG-powered collaborative developer platform**, an **async ML opportunity aggregator**, and a **recursive-descent compiler**.

**Current focus:**
- Systems programming — DPI, packet analysis, low-level C++17
- Agentic AI — RAG pipelines, vector search, LLM orchestration
- Compiler infrastructure — parsing, IR, CFG optimizations
- Distributed systems — microservices, async ETL, caching layers

---

## Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <p align="center"><strong>PacketSentinel</strong></p>
      <p align="center">
        <a href="https://github.com/manaskng/PacketSentinel">
          <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
        </a>
        <a href="https://packet-sentinel.vercel.app">
          <img src="https://img.shields.io/badge/Live-000000?style=for-the-badge&logo=vercel&logoColor=white" />
        </a>
      </p>
      <p align="center">
        <img src="https://placehold.co/400x200/0d1117/58a6ff?text=PacketSentinel+Demo" width="100%" />
      </p>
      <p><strong>Multi-threaded Deep Packet Inspection & Malware Detection Engine</strong></p>
      <ul>
        <li><strong>438,000 pkt/s</strong> via lock-free pipeline (FNV-1a flow-table sharding) — zero mutex contention on hot path</li>
        <li>Byte-level TLS SNI, HTTP Host, DNS parsing via <code>std::string_view</code> — zero heap allocations on hot path</li>
        <li>Shannon entropy + Welford variance anomaly in O(1) memory; Random Forest <strong>97% precision</strong> on DDoS/C2 datasets</li>
        <li><strong>1.7× speedup</strong> over single-threaded baseline; classifies <strong>15+ application types</strong> from live traffic</li>
      </ul>
      <div align="center">
        <img src="https://img.shields.io/badge/C++17-00599C?style=flat&logo=c%2B%2B&logoColor=white" />
        <img src="https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54" />
        <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white" />
        <img src="https://img.shields.io/badge/libpcap-darkgreen?style=flat" />
        <img src="https://img.shields.io/badge/CMake-064F8C?style=flat&logo=cmake&logoColor=white" />
        <img src="https://img.shields.io/badge/Scapy-3670A0?style=flat" />
      </div>
    </td>
    <td width="50%" valign="top">
      <p align="center"><strong>Relay</strong></p>
      <p align="center">
        <a href="https://github.com/manaskng/DevNexus">
          <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
        </a>
        <a href="https://devnexus-app.vercel.app">
          <img src="https://img.shields.io/badge/Live-000000?style=for-the-badge&logo=vercel&logoColor=white" />
        </a>
      </p>
      <p align="center">
        <img src="https://placehold.co/400x200/0d1117/58a6ff?text=Relay+Demo" width="100%" />
      </p>
      <p><strong>Adaptive RAG-Powered AI Collaborative Developer Ecosystem</strong></p>
      <ul>
        <li>Custom RAG pipeline — <strong>768-dim Gemini embeddings</strong> + Atlas Vector Search, <strong>sub-50ms</strong> semantic retrieval across 10,000+ docs (<strong>60× over regex</strong>)</li>
        <li><strong>RelaySandbox</strong> — real-time collaborative editor (Socket.IO, 13 events), <strong>11 compiled languages</strong>, dual-compiler failover, <strong>50+ concurrent rooms</strong></li>
        <li>Redis sliding-window rate limiter (AI: 10 req/min; Compiler: 15 req/min) with dual Gemini model failover</li>
        <li><strong>40+ REST endpoints</strong>, Dockerized CI/CD, MongoDB TTL auto-purge on activity logs</li>
      </ul>
      <div align="center">
        <img src="https://img.shields.io/badge/MERN-47A248?style=flat&logo=mongodb&logoColor=white" />
        <img src="https://img.shields.io/badge/Socket.IO-010101?style=flat&logo=socket.io" />
        <img src="https://img.shields.io/badge/Redis-DD0031?style=flat&logo=redis&logoColor=white" />
        <img src="https://img.shields.io/badge/Gemini_API-4285F4?style=flat&logo=google&logoColor=white" />
        <img src="https://img.shields.io/badge/Docker-0db7ed?style=flat&logo=docker&logoColor=white" />
        <img src="https://img.shields.io/badge/Vector_Search-47A248?style=flat&logo=mongodb&logoColor=white" />
      </div>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <p align="center"><strong>OppLens</strong></p>
      <p align="center">
        <a href="https://github.com/manaskng/opp-lens">
          <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
        </a>
        <a href="https://dev-event-sync.vercel.app">
          <img src="https://img.shields.io/badge/Live-000000?style=for-the-badge&logo=vercel&logoColor=white" />
        </a>
      </p>
      <p align="center">
        <img src="https://placehold.co/400x200/0d1117/58a6ff?text=OppLens+Demo" width="100%" />
      </p>
      <p><strong>Distributed Opportunity Aggregator & ML Recommendation Engine</strong></p>
      <ul>
        <li>Fault-tolerant Playwright ETL scraping <strong>5 platforms</strong> — <strong>5,000+ opportunities/week</strong>; composite-key hashing cuts redundant writes by <strong>~95%</strong></li>
        <li>Atlas Vector Search (HNSW) replacing O(N) → O(log N), <strong>~10× speedup</strong>; sentence-transformers semantic dedup</li>
        <li>Hybrid NLP recommender — TF-IDF + Collaborative Filtering + Vector Search in decoupled FastAPI microservice</li>
        <li>Redis cache cuts p95 ML inference from <strong>400ms → &lt;80ms</strong> (80% reduction) on high-frequency queries</li>
      </ul>
      <div align="center">
        <img src="https://img.shields.io/badge/Next.js-black?style=flat&logo=next.js&logoColor=white" />
        <img src="https://img.shields.io/badge/FastAPI-005571?style=flat&logo=fastapi" />
        <img src="https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54" />
        <img src="https://img.shields.io/badge/sentence--transformers-F7931E?style=flat" />
        <img src="https://img.shields.io/badge/Redis-DD0031?style=flat&logo=redis&logoColor=white" />
        <img src="https://img.shields.io/badge/Playwright-45ba4b?style=flat&logo=playwright&logoColor=white" />
      </div>
    </td>
    <td width="50%" valign="top">
      <p align="center"><strong>MiniC Compiler <em>(In Progress)</em></strong></p>
      <p align="center">
        <a href="https://github.com/manaskng/MiniC_Compiler">
          <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
        </a>
      </p>
      <p align="center">
        <img src="https://placehold.co/400x200/0d1117/58a6ff?text=MiniC+Compiler" width="100%" />
      </p>
      <p><strong>C-Subset Recursive-Descent Compiler</strong></p>
      <ul>
        <li>Hand-written recursive-descent parser → AST → semantic analysis (type checking, scope resolution)</li>
        <li>3-address IR (TAC) with basic-block CFG — constant folding, dead-code elimination, copy propagation → <strong>~25% instruction reduction</strong></li>
        <li>100+ pytest cases covering pointer arithmetic, nested scopes, register spilling</li>
        <li>Symbol-table-driven linker helper across translation units — mirrors PTXAS front-end responsibilities</li>
      </ul>
      <div align="center">
        <img src="https://img.shields.io/badge/C++17-00599C?style=flat&logo=c%2B%2B&logoColor=white" />
        <img src="https://img.shields.io/badge/CMake-064F8C?style=flat&logo=cmake&logoColor=white" />
        <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white" />
      </div>
    </td>
  </tr>
</table>

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

<table>
  <tr>
    <td>🥇</td>
    <td><strong>Goldman Sachs India Hackathon 2026</strong></td>
    <td>Rank 1 · 100/100 · 15,000+ submissions · Recursive JSON→TypeScript parser in C++</td>
  </tr>
  <tr>
    <td>⚔️</td>
    <td><strong>LeetCode Knight</strong></td>
    <td>Top 2% · Rating 2051 · 800+ problems · Rank 307/35,237 (Biweekly 174)</td>
  </tr>
  <tr>
    <td>📘</td>
    <td><strong>AlgoUniversity DP Camp</strong></td>
    <td>Top 2.5% of 40,000 participants · Codeforces Master mentorship</td>
  </tr>
  <tr>
    <td>🎓</td>
    <td><strong>SDE Intern @ IIT Ropar</strong></td>
    <td>Vicharanashala Lab · 2 merged PRs · Setup pipeline + UI bug fix</td>
  </tr>
  <tr>
    <td>🌟</td>
    <td><strong>GDG Solution Challenge 2025</strong></td>
    <td>Certificate of Achievement · AI-driven solution</td>
  </tr>
  <tr>
    <td>🔖</td>
    <td><strong>GitHub Badges</strong></td>
    <td>Pull Shark · Starstruck</td>
  </tr>
</table>

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
