<div align="center">

# Ayush Wange

**Backend and AI engineering · MSc Advanced Computer Science @ University of Sheffield**

Building LLM-powered backend systems and exploring cloud and Kubernetes security.

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Ayushwange11@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayush-wange-54b882252/)

</div>

---

## About

I'm an MSc Advanced Computer Science student at the University of Sheffield (2026 to 2027), with a B.Tech in Computer and Communication Engineering from Manipal University Jaipur. I like building backend systems that are tested, containerised and observable, and I'm interested in using knowledge graphs to keep LLM output reliable.

I'm looking for graduate software and AI engineering roles in the UK.

## Highlights

| 0.90 ROC-AUC | 99% recall | 8-stage pipeline | 65 pytest tests | 25+ metrics |
|:---:|:---:|:---:|:---:|:---:|
| Co-authored anomaly detection paper | on DoS and brute-force attacks | natural language to validated PostgreSQL schema | across all 12 project modules | Prometheus, with a Grafana dashboard |

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)

**Frameworks**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

**Data and backend**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j_Cypher-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-555555?style=flat-square)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

**AI and ML**

![Claude API](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white)
![GraphRAG](https://img.shields.io/badge/GraphRAG-4581C3?style=flat-square)
![TF-IDF](https://img.shields.io/badge/TF--IDF-555555?style=flat-square)
![Autoencoders](https://img.shields.io/badge/Autoencoders-555555?style=flat-square)
![Anomaly Detection](https://img.shields.io/badge/Anomaly_Detection-555555?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)

**DevOps and tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Gunicorn](https://img.shields.io/badge/Gunicorn-499848?style=flat-square&logo=gunicorn&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

---

## Selected Work

### SchemaAdvisor: natural language to validated PostgreSQL schemas

Built during my AI Engineer internship at zCon Solutions (Jan to May 2026). It turns natural-language business requirements into validated PostgreSQL schemas through an 8-stage pipeline. A Neo4j knowledge graph constrains the LLM (Claude) output to a predefined taxonomy, which reduces hallucinated tables, columns and invalid SQL.

- **Correct ordering:** Kahn's topological sort orders tables, and DFS-based cycle breaking resolves circular foreign keys. Every generated schema is validated on a live PostgreSQL instance.
- **Hybrid GraphRAG retrieval:** TF-IDF cosine similarity maps requirements to taxonomy concepts without exact keyword matches, with fallback to semantic and keyword matching if the LLM API is unavailable.
- **Production ready:** Docker (multi-stage build, healthchecks), Gunicorn/Uvicorn, Nginx rate limiting, a Redis cache with in-memory fallback, PostgreSQL connection pooling and JWT-secured admin APIs.
- **Observable and tested:** 25+ Prometheus metrics with a Grafana dashboard, and 65 automated pytest tests.
- **CloudAdvisor prototype:** reuses the same pipeline to generate AWS Terraform for VPC, ALB, EC2, RDS and S3 in dependency order.

### Unsupervised anomaly detection for containerised multi-cloud environments

Co-authored paper (Dec 2025) on an autoencoder-based framework that secures Kubernetes clusters against novel multi-cloud attacks. It reached 0.90 ROC-AUC and 99% recall on DoS and brute-force attacks, beating Isolation Forest baselines.

---

## Experience

| Role | Where | When |
|:---|:---|:---|
| AI Engineer Intern | zCon Solutions Pvt Ltd, Pune | Jan to May 2026 |
| Full Stack Developer Intern | 2xCabs, Remote | July to Sept 2025 |

At 2xCabs I built RESTful APIs in Node.js and Express for ride-booking and tracking features.

## Beyond Code

- Captained the Manipal University Jaipur football team (Dec 2024 to Dec 2025), leading 45+ players across the main and development squads
- Played professional esports in Counter-Strike: Global Offensive and ranked among the top 3 players in India

---

<div align="center">

Based in Sheffield, UK ·

</div>

<!--
Optional GitHub stats card. Replace YOUR-USERNAME with your GitHub username, then delete the comment markers around the line below.
![GitHub stats](https://github-readme-stats.vercel.app/api?username=YOUR-USERNAME&show_icons=true&hide_border=true)
-->
