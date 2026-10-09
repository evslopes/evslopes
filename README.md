# Olá, eu sou Elvis Lopes! 👋

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/evslopes/)
[![Portfólio](https://img.shields.io/badge/Portfólio-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white)](https://evslopes.github.io/portifolio-jhh/index.html)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:evs.lopes@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/evslopes)

**Engenheiro de Software Sênior | Arquiteto de Soluções | Especialista em Sistemas Críticos & Edge AI**  
*Rio de Janeiro, RJ - Brasil*

</div>

---

## 👨‍💻 Sobre Mim

* 🎯 **Perfil & Atuação:** Engenheiro de Software e Arquiteto com sólida experiência no ciclo de vida completo de soluções corporativas e produtos de alta criticidade. Especialista em unir práticas de **SRE/DevOps** (alta disponibilidade, resiliência e observabilidade) a arquiteturas modernas de software (**Clean Architecture**, **DDD**, **Microsserviços** e **Edge-First AI**).
* 🎓 **Formação Acadêmica:** 
  * Pós-graduação em **Software Architecture** pela **FIAP** (Foco em Cloud-Native, Microsserviços e Sistemas Distribuídos).
  * Graduação em **Análise e Desenvolvimento de Sistemas** pelo **Instituto Infnet**.
* 💡 **Especialidades Técnicas:** Clean Architecture, Domain-Driven Design (DDD), Edge-First AI (On-Device LLMs & RAG local), Arquiteturas Reativas, SAGA Patterns, C4 Model, Criptografia Zero-Knowledge, Infraestrutura como Código (Terraform/IaC), Containerização & Orquestração (Docker/Kubernetes) e Troubleshooting L3 em bancos de alta volumetria (Oracle/PostgreSQL).

---

## 🚀 Projetos & Cases em Destaque

### 🕊️ [pwE (Pray With Me)](https://evslopes.github.io/portifolio-jhh/pwe.html)
> **Aplicativo de Lectio Divina (Leitura Orante) com Inteligência Artificial Híbrida & Privacidade Zero-Knowledge**

* **IA Edge-First & RAG On-Device:** Inferência pastoral local via **Gemma 4 E2B** acelerada em GPU/NPU no smartphone com a engine **LiteRT-LM** (Android/Kotlin nativo) e RAG 100% no dispositivo via **TFLite** (`all-MiniLM-L6-v2`, 384 dimensões e Mean Pooling), garantindo soberania total dos dados devocionais do usuário.
* **Escadaria Gemini & Nuvem Resiliente:** Integração inteligente com a família **Google Gemini** (Gemini 3.5 Flash Lite, 3.6 e 3.7 Flash via Firebase Remote Config) com *Smart Retry* (backoff exponencial com jitter) e cache de sessão.
* **Engenharia & Qualidade Impecável:** **Clean Architecture** modular em Flutter com decomposição em **6 sub-BLoCs desacoplados** (`flutter_bloc`), tratamento funcional de erros com `dartz` (`Either<Failure, Success>`), **931 testes automatizados** (unitários, widgets, golden tests e acessibilidade tipográfica 1.15x), **34 ADRs formais** e governança contínua com comitê de **16 subagentes especialistas de IA** no Google Antigravity.
* **Segurança & Nuvem Serverless:** Criptografia em repouso **AES-256-GCM** no Hive com chaves derivadas via PBKDF2 ancoradas no hardware (Android Keystore e iOS Keychain) e pipeline litúrgico automatizado no **GCP (Cloud Run Jobs + Cloud Scheduler)** ingerindo dados canônicos da CNBB.
* 🔗 [Ver Estudo de Caso Completo](https://evslopes.github.io/portifolio-jhh/pwe.html)

---

### 👶 [BabeView (Baby Monitor P2P Hub)](https://evslopes.github.io/portifolio-jhh/babeview-case.html)
> **Hub de Monitorização Multi-Câmera (N-para-1) com Baixa Latência**

* **Streaming P2P de Alta Resiliência:** Conexão Full-Duplex de vídeo e áudio em tempo real entre dispositivos utilizando **WebRTC P2P** nativo (`flutter_webrtc`).
* **Conectividade Heterogênea:** Suporte a câmeras de segurança IP via **RTSP/ONVIF** com aceleração de hardware (H.264/H.265) via C/C++ bindings do `media_kit`.
* **Zero-Config Discovery:** Pareamento automático de dispositivos na mesma rede local via mDNS (`nsd`).
* **Arquitetura Reativa:** Construído com **Flutter**, **Clean Architecture** e **Riverpod** para gestão de estado assíncrono complexo e carrossel multi-stream sem sobrecarga de memória.
* 🔗 [Ver Estudo de Caso Completo](https://evslopes.github.io/portifolio-jhh/babeview-case.html)

---

### 🌙 Sleep O'Clock
> **Relógio Noturno Inteligente, Preservação de Melatonina & Sleep Trainer Infantil**

* **Higiene do Sono & Melatonina:** Modo Noturno adulto minimalista com acionamento por gesto do **Modo Vermelho**, minimizando emissão de espectros azuis durante o ciclo circadiano.
* **Modo Infantil (Sleep Trainer):** Interface lúdica sem textos para crianças pré-escolares, com transições visuais solenes entre noite (Lua/estrelas) e hora de despertar (Sol/nuvens).
* **Proteção Ativa Anti-Burn-in:** Micro-deslocamentos sutis (`AnimatedAlign`) a cada minuto no display para preservar painéis OLED e AMOLED contra retenção permanente de imagem.
* **Arquitetura:** Desenvolvido em **Flutter** com **Clean Architecture**, **BLoC** (`flutter_bloc`), injeção modular com `get_it`, `go_router`, controle gestual de brilho, wakelock nativo e telemetria anônima com Firebase.

---

### ☁️ [FIAP SOAT Cloud-Native Platform](https://evslopes.github.io/portifolio-jhh/postech-FIAP-SOAT-case.html)
> **Arquitetura Distribuída de Microsserviços e Infraestrutura como Código (Pós-Tech FIAP)**

* **Microsserviços Autônomos:** Desacoplamento de domínio em 4 microsserviços autônomos assíncronos (Clientes, Pagamentos, Pedidos e Produção) construídos com **Java / Spring Boot** sob **Clean Architecture**.
* **Persistência Híbrida & API Gateway:** Integração relacional (**PostgreSQL**) e chave-valor de altíssima escala (**DynamoDB**), isolando redes privadas via API Gateway.
* **SRE, Cloud & IaC:** Provisionamento 100% automatizado na **AWS** via **Terraform** (IaC), orquestração de contêineres em **Kubernetes** com suporte a **HPA (Horizontal Pod Autoscaling)** e esteiras automatizadas de CI/CD com **GitHub Actions**.
* 🔗 [Repositório GitHub](https://github.com/evslopes/postech-FIAP-SOAT) | [Ver Estudo de Caso Completo](https://evslopes.github.io/portifolio-jhh/postech-FIAP-SOAT-case.html)

---

### 🤱 [Infraestrutura Mãe da Prole](https://evslopes.github.io/portifolio-jhh/maedaprole-infra.html)
> **Arquitetura DevOps, Orquestração e SRE para Plataforma de Saúde Materna**

* **Orquestração Multi-Repo Resiliente:** Parametrização e isolamento de redes virtuais fechadas com **Docker Compose**, mitigando custos e garantindo segurança contra exposição de portas de dados.
* **Stack Integrada:** Integração estável entre API Corporativa (**Java / Spring Boot**), **Strapi Headless CMS v5**, Frontend PWA (**Vue.js / Vite**) e banco de dados relacional **PostgreSQL 14**.
* **Automação & Qualidade:** Gestão segura de variáveis e segredos, pipelines de entrega contínua no **GitHub Actions** e validação E2E multi-repositório com **Cypress**.
* 🔗 [Ver Estudo de Caso Completo](https://evslopes.github.io/portifolio-jhh/maedaprole-infra.html)

---

### 🏢 [Nexus Enterprise](https://evslopes.github.io/portifolio-jhh/nexus-enterprise.html)
> **Ecossistema Corporativo Escalável e Integração de Agentes de IA**

* Plataforma backend corporativa de alta performance integrando o ecossistema robusto da JVM (**Java / Spring Boot**) a microsserviços assíncronos em **Python** para integração direta com **agentes de Inteligência Artificial**.
* Ambientes conteinerizados via **Docker** e orquestrados em **Kubernetes** para garantir resiliência e alta escalabilidade em operações B2B de missão crítica.
* 🔗 [Ver Estudo de Caso Completo](https://evslopes.github.io/portifolio-jhh/nexus-enterprise.html)

---

## 🛠 Stack Tecnológica & Competências

### 🧠 Arquitetura, IA & Práticas de Engenharia
![Clean Architecture](https://img.shields.io/badge/Clean%20Architecture-00599C?style=for-the-badge&logoColor=white)
![Domain--Driven Design](https://img.shields.io/badge/Domain--Driven%20Design-0A84FF?style=for-the-badge&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75C2?style=for-the-badge&logo=googlebard&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow%20Lite-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![TDD](https://img.shields.io/badge/TDD%20%2F%20Golden%20Tests-4CAF50?style=for-the-badge&logoColor=white)
* Clean Architecture, Domain-Driven Design (DDD), Edge AI (LiteRT-LM / Gemma 4), Cloud AI (Gemini 3.5/3.6/3.7), RAG On-Device, Vector Search, OCR (ML Kit), Microsserviços, SAGA Patterns, C4 Model, Criptografia AES-256-GCM.

### ☁️ Cloud, DevOps, Infraestrutura & SRE
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
* **Google Cloud Platform:** Cloud Run, Cloud Scheduler, Cloud Firestore, Firebase.
* **AWS:** DynamoDB, S3, IAM, VPC, LocalStack.
* **Containers & IaC:** Kubernetes (Deployments, HPA, Services), Docker, Terraform, GitHub Actions CI/CD.

### 📱 Mobile & Frontend
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=webrtc&logoColor=white)
* Flutter (Canal Stable), BLoC (`flutter_bloc`), Riverpod, GetIt, GoRouter, dartz (Programação Funcional), Kotlin nativo, Swift, Vue.js / Vite, WebRTC P2P, media_kit (RTSP/ONVIF).

### ⚙️ Backend, Linguagens & Bancos de Dados
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
* Java 17/21 (Spring Boot, Spring Data, Spring Security), Python (IA/Automação), TypeScript/Node.js, PostgreSQL, Oracle DB (tuning L3, otimização de queries), Hive (NoSQL criptografado local), Redis.

---

## 📊 Estatísticas do GitHub

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=evslopes&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Estatísticas do GitHub" height="175" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=evslopes&layout=compact&theme=tokyonight&hide_border=true" alt="Linguagens Mais Utilizadas" height="175" />

</div>

---

## 📫 Contato & Networking

* 💼 **LinkedIn:** [linkedin.com/in/evslopes](https://www.linkedin.com/in/evslopes/)
* 🌐 **Portfólio & Case Studies:** [evslopes.github.io/portifolio-jhh](https://evslopes.github.io/portifolio-jhh/index.html)
* ✉️ **E-mail:** [evs.lopes@gmail.com](mailto:evs.lopes@gmail.com)
* 🐙 **GitHub:** [github.com/evslopes](https://github.com/evslopes)

<div align="center">
  <sub>Construindo sistemas de alto impacto, combinando engenharia rigorosa, arquitetura limpa e tecnologia de ponta. 🚀</sub>
</div>
