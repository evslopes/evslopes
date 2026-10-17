# Hi, I'm Elvis Lopes (Elvis Herllain) 👋

**Senior Software Engineer & Solutions Architect** · Rio de Janeiro, Brazil  
🌐 **[Portfolio (EN)](https://jhhsolutions.dev/en/index.html)** | **[Portfólio (PT-BR)](https://jhhsolutions.dev/)** | 💼 **[LinkedIn](https://www.linkedin.com/in/evslopes/?locale=en-US)** | 🚀 **[Flagship App: pwE](https://pwe.jhhsolutions.dev/?lang=en)**

### About Me / Sobre Mim

🇺🇸 **EN:** Senior Software Engineer, Tech Lead, and Solutions Architect (Postgraduate in Software Architecture @ FIAP) combining **5+ years sustaining mission-critical enterprise B2B systems at Serasa Experian** (SRE, L3 RCA, Oracle DB, Distributed Systems) with **full-cycle product engineering at JHH Solutions** (Java/Spring Boot, Flutter/Dart, Cloud-Native AWS/GCP, and Dual On-Device Edge AI).

🇧🇷 **PT:** Engenheiro de Software Sênior, Tech Lead e Arquiteto de Soluções (Pós-graduado em Software Architecture pela FIAP), unindo a confiabilidade de **sistemas corporativos críticos B2B na Serasa Experian** (SRE, Troubleshooting L3, Oracle DB) à engenharia de ciclo completo na **JHH Solutions** (Java/Spring Boot, Flutter/Dart, AWS/GCP e IA On-Device).

### Featured Production & Architecture Showcases / Projetos em Destaque

| Project / Produto | Architecture & Production Metrics | Live / Case Study |
| :--- | :--- | :--- |
| **[pwE — Pray With Me](https://pwe.jhhsolutions.dev/?lang=en)**<br>*(Flagship Cross-Platform App — Android, iOS, Web)* | **333 Dart files**, **193 test suites (≥70% CI gate)**, **50 ADRs**, **Clean Arch + DDD** (7 features, 13 BLoCs, 32 UseCases, `dartz` Either), **Dual Edge AI** (Gemma 4 E2B via Kotlin JNI/Swift C API on LiteRT-LM + 384-d BERT TFLite RAG), **Dart AOT Worker on GCP Cloud Run + GCS Static CDN (>98% offload)**, **Langfuse LLMOps**, **AES-256-GCM + Encrypted Hive**, **18 ARB Locales (668 keys)** | [Live App (EN)](https://pwe.jhhsolutions.dev/?lang=en) · [Live App (PT)](https://pwe.jhhsolutions.dev/pt-br/) · [Architecture Case](https://jhhsolutions.dev/pwe.html) |
| **[BabeView — P2P Monitoring Hub](https://jhhsolutions.dev/babeview-case.html)**<br>*(Real-Time Multi-Camera Streaming)* | **Flutter, Riverpod, DDD, WebRTC P2P** (Full-Duplex HD Audio/Video), **RTSP/ONVIF** IP Camera decoding (H.264/H.265 via C/C++ `media_kit`), Zero-Config LAN discovery (**mDNS**) | [Architecture Case](https://jhhsolutions.dev/babeview-case.html) |
| **[FIAP SOAT Cloud-Native Platform](https://github.com/evslopes/postech-FIAP-SOAT)**<br>*(Distributed Microservices & IaC)* | **Java, Spring Boot, Clean Architecture**, 4 Autonomous Microservices, **PostgreSQL + AWS DynamoDB**, API Gateway, **Terraform (IaC)**, **Kubernetes (HPA)**, **GitHub Actions CI/CD** | [GitHub Repo](https://github.com/evslopes/postech-FIAP-SOAT) · [Case Study](https://jhhsolutions.dev/postech-FIAP-SOAT-case.html) |
| **[Mãe da Prole Platform & Android App](https://github.com/evslopes/MDP-Android)**<br>*(Full-Cycle Mobile & Containerized Infra)* | Native Android (**Kotlin**, MVVM, Google Play release) + Unified **Docker** infrastructure (**Java/Spring Boot API, Vue.js PWA, Strapi v5 CMS, PostgreSQL 14**) | [Android Repo](https://github.com/evslopes/MDP-Android) · [Infra Case](https://jhhsolutions.dev/maedaprole-infra.html) |

### Core Stack & Architecture Specialties

- **Architecture & Governance:** Clean Architecture, Domain-Driven Design (DDD), Microservices, SAGA Patterns, C4 Model, UML, BPMN, ADRs, FinOps, Zero-Knowledge Security (AES-256-GCM / PBKDF2).
- **Backend, Mobile & Edge AI:** Java (Spring Boot), Flutter / Dart (`flutter_bloc`, `go_router`, `get_it`, `dartz`), Kotlin (JNI), Swift C Interop, Python, On-Device LLMs (Gemma 4 / LiteRT-LM), Local Vector RAG (TFLite BERT 384d), Google Gemini API, Langfuse (LLMOps), WebRTC, RTSP/ONVIF.
- **Cloud, SRE & DevOps:** Google Cloud Platform (Cloud Run Jobs, GCS Static CDN, Firebase), AWS, Kubernetes, Docker, Terraform (IaC), GitHub Actions (CI/CD), L3 Incident Response & Root Cause Analysis (RCA).
- **Data & Persistence:** Oracle DB (Advanced SQL & Query Tuning), PostgreSQL, DynamoDB, Cloud Firestore, Encrypted Hive (`HiveAesCipher`), Neo4j, Cassandra.
