<div align="center">

<img src="assets/banner.svg" alt="Mohamed Arafath T. An animated cluster of nodes: the leader fails, another node is elected, and the cluster recovers." width="100%">

### Building search, database and AI systems that keep working when parts of them fail.

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=3000&pause=1000&color=2F81F7&center=true&vCenter=true&width=520&lines=Search+infrastructure;Database+internals;RAG+and+AI+systems;Security+tooling)](https://mdarafath202006-tech.github.io/Mohamed-Arafath-Portfolio/)

B.Tech Information Technology student in Chennai, India. Open to SDE internships.

[Featured projects](#featured-projects) · [Tech stack](#tech-stack) · [Portfolio](https://mdarafath202006-tech.github.io/Mohamed-Arafath-Portfolio/) · [Résumé](https://mdarafath202006-tech.github.io/Mohamed-Arafath-Resume/) · [Contact](#contact)

</div>

<img src="assets/divider.svg" alt="" width="100%">

I'm an IT undergraduate who prefers building systems to building demos. My projects include a search engine with BM25 ranking, a database engine with write-ahead logging, a RAG backend, a network-security compliance platform, and a Flask platform with seven Claude-powered career tools. I start from how a system should behave when something breaks, write the trade-offs down, then build to them.

If you open one repository first, make it **AI CareerVerse**. It has the tests, CI pipeline and Docker setup.

## About

- **Studying:** B.Tech, Information Technology at St. Peter's College of Engineering and Technology, Chennai (expected May 2028)
- **Focus:** databases and storage engines, search infrastructure, retrieval-augmented generation, security tooling
- **Approach:** fallback paths before happy paths, explicit trade-offs, and reading PostgreSQL, Lucene and LevelDB internals to guide design
- **Looking for:** SDE internships
- **Worth a click:** my [portfolio](https://mdarafath202006-tech.github.io/Mohamed-Arafath-Portfolio/) background is a small cluster. Fail a node and watch it recover.

<img src="assets/divider.svg" alt="" width="100%">

## Featured projects

### AI CareerVerse

*A career platform that connects students with alumni, mentors and job opportunities, with AI tools for resumes, interviews and roadmaps.*

- **Mentorship and referrals:** skill-based alumni recommendations, request and accept/decline flows, referral requests with approve/reject status, and real-time Socket.IO notifications
- **Seven Claude-powered tools:** career chat, resume analyzer (ATS score) and builder, job match, skill-gap analyzer, career roadmap, and interview coach
- **Platform features:** job portal, company pages, a knowledge base of interview experiences and career guides, social feed, communities, follows, and an admin dashboard
- **Why it's interesting:** three user roles (student, alumni, admin), CSRF protection, Redis-backed rate limiting, pytest tests, a GitHub Actions workflow, and Docker plus a Render blueprint. It's structured like a product, not a single-feature demo.

**Stack:** Python · Flask · SQLAlchemy · PostgreSQL · Redis · Flask-SocketIO · Gunicorn · Claude API · Docker · GitHub Actions

[Repository](https://github.com/mdarafath202006-tech/aicareerverse) · Runs locally with seeded demo data (setup is in the repo README)

### Nexus-Comply AI

*A multi-vendor network security compliance and risk platform that turns Cisco, Fortinet and Juniper configurations into one vendor-neutral model.*

- Automatic vendor detection and normalization of Cisco IOS, Fortinet FortiOS and Juniper Junos configs
- Deterministic rules mapped to CIS, NIST, STIG and ISO, with evidence-backed findings and contextual risk scoring
- Cross-device security graph, JWT role-based access and PDF audit reports
- Built for Smart India Hackathon (SIH26155)

**Stack:** Python · FastAPI · React · TypeScript · PostgreSQL · Docker

[Repository](https://github.com/mdarafath202006-tech/nexus-comply-ai)

### Systems and infrastructure

- **[Retrivix](https://github.com/mdarafath202006-tech/Retrivix)**: a local Python search engine with document ingestion, tokenization, an inverted index, persisted indexes and top-K BM25 ranking.
- **[VirelyxDB](https://github.com/mdarafath202006-tech/VirelyxDB)**: a Python relational-storage prototype with schema validation, JSON persistence, equality indexes, CRUD operations and a snapshot-based write-ahead-log recovery demo.
- **[Loreva](https://github.com/mdarafath202006-tech/Loreva)**: a FastAPI RAG prototype that chunks documents, retrieves passages with BM25-style lexical scoring and returns source-grounded extractive answers. Embeddings and LLM synthesis are planned extensions.

### Archived

- **[AlumniConnect](https://github.com/mdarafath202006-tech/alumniconnect)**: an earlier Flask and MySQL mentorship prototype (TF-IDF mentor ranking, Socket.IO chat, JWT API). Archived in October 2026; its ideas continue in AI CareerVerse.

<img src="assets/divider.svg" alt="" width="100%">

## Tech stack

Technologies I've used in the projects above. Where I'm still early, I say so.

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Backend and APIs**
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)

**Databases**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**AI and retrieval:** LLM applications (Claude API), RAG, embeddings, vector search, BM25 and inverted indexes, recommendation systems

**Tooling**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Exploring:** gRPC, Azure AI Foundry (Microsoft Virtual Training Day: Build Agentic AI Solutions)

<img src="assets/divider.svg" alt="" width="100%">

## Currently building and learning

- **Locatrix** (prototype): offline dead-reckoning simulation with heading fusion and CRC-protected location packets; real phone-sensor integration and Bluetooth/LoRa transport remain future work.
- **Studying:** database internals, search infrastructure, and distributed-systems trade-offs

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamed-arafath-t-4b7b49359/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mdarafath202006@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-0D1117?style=flat-square&logo=githubpages&logoColor=white)](https://mdarafath202006-tech.github.io/Mohamed-Arafath-Portfolio/)
[![Résumé](https://img.shields.io/badge/Résumé-4B5563?style=flat-square)](https://mdarafath202006-tech.github.io/Mohamed-Arafath-Resume/)

Open to SDE internships. Email is the fastest way to reach me.

<img src="assets/footer.svg" alt="" width="100%">
