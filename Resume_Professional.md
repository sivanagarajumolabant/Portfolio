# M. SIVA NAGA RAJU

**Senior Technical Analyst | AI Solutions Architect | Agentic Migration Platform Specialist**

Email: [siva.m504504@gmail.com](mailto:siva.m504504@gmail.com) | Phone: +91-8985111673 | Location: Hyderabad, India  
LinkedIn: [linkedin.com/in/siva-nagaraju-molabanti-b9883a185](https://linkedin.com/in/siva-nagaraju-molabanti-b9883a185)  
Portfolio: [sivanagarajumolabant.github.io/Portfolio](https://sivanagarajumolabant.github.io/Portfolio/)

---

## SUMMARY

Senior Technical Analyst with **7+ years of experience** at Quadrant Technologies, specializing in enterprise-grade AI-powered database migration and release automation for the QMigrator product. Integrated and productionized a multi-agent migration ecosystem across Release Agent, Migration Agent, API Agent, UI Agent, DB Agent, DevOps Agent, Testing Automation, and execution triage/remediation flows, using LangGraph, FastAPI, Azure DevOps, and Google's A2A/ADK-style agent-to-agent SDK patterns.

- Integrated independently developed agent services into a unified QMigrator release workflow with A2A communication, status tracking, DevOps automation, and test feedback loops
- Achieved 98% automation in database schema conversion across Oracle, PostgreSQL, SQL Server, Snowflake, Databricks, and Sybase-to-SQL Server modernization paths
- Reduced migration error resolution time by 75% — from 2 hours to 8 minutes — through AI triage, remediation, validation, and rerun loops
- Delivered enterprise migration automation for UHG, Elevance Health/Carelon, eBay, Nike, and Apollo Hospitals

---

## SKILLS

**AI & Generative AI:** LangChain, LangGraph, Multi-Agent Systems, Google A2A/ADK-style Agent SDK Integration, RAG Architecture, Prompt Engineering, Agentic AI, Pydantic AI, NLP  
**Agent Orchestration:** FastAPI Agent Services, A2A JSON-RPC, Agent Cards, Webhook Signals, LangGraph Checkpointing, Human-in-the-Loop Review, Multi-Agent Release DAGs  
**Large Language Models:** Azure OpenAI GPT-4, Anthropic Claude, Google Gemini, Groq, Ollama  
**Vector Databases:** ChromaDB, FAISS, Pinecone, Milvus, Qdrant  
**AI Evaluation:** DeepEval, Ragas, AI Guardrails, AI Safety, Quality Assurance  
**Embeddings:** OpenAI Embeddings, HuggingFace Embeddings, Ollama Embeddings  
**Programming Languages:** Python (Expert), SQL (Advanced), JavaScript  
**Backend Frameworks:** FastAPI, Django, Django REST Framework, Flask, Streamlit  
**API Development:** RESTful APIs, A2A Protocol APIs, JSON-RPC, GraphQL, Swagger, OpenAPI  
**Data Engineering:** Pandas, NumPy, Apache Airflow, Celery, ETL Pipelines, Matplotlib, Seaborn  
**Databases:** PostgreSQL, Oracle, SQL Server, MySQL, MongoDB, Redis  
**Data Platforms:** Snowflake, Databricks, Delta Lake  
**Database Skills:** Query Optimization, Performance Tuning, PL/SQL, PL/pgSQL, T-SQL, Index Design  
**Cloud - Azure:** AKS, ACR, Azure DevOps, Key Vault, Pipelines, Azure PostgreSQL, Azure Blob Storage  
**Cloud - AWS:** ECS, Fargate, ECR, API Gateway, Lambda, S3, EC2, RDS  
**DevOps & Containers:** Docker, Kubernetes, Helm Charts, ArgoCD, Azure Pipelines, GitHub Actions, GitLab CI/CD  
**Frontend:** Angular 17, ReactJS, JavaScript, TypeScript, HTML5, CSS3, Material UI  
**Testing:** Playwright Automation, Pytest, Selenium, E2E Status Polling, Automated Remediation Loops  
**Tools:** Git, GitHub, GitLab, Bitbucket, JIRA, Confluence, Postman, VS Code, PyCharm, Cursor, Windsurf

---

## WORK EXPERIENCE

### Quadrant Technologies — Hyderabad, India
**Senior Technical Analyst** | March 2019 - Present (7+ Years)

---

### Product: QMigrator — Enterprise Database Migration Platform
**Core Product Developer and AI Solutions Architect** | 2019 - Present  
Platform URL: [qcam.qmigrator.ai](https://qcam.qmigrator.ai/)

QMigrator is Quadrant Technologies' flagship enterprise database migration platform that automates end-to-end schema conversion, data migration, and code translation across heterogeneous database environments. Key contributor since inception — built and evolved the platform from a feature management system to a full-scale AI-powered migration solution.

- Built and maintained the core migration platform serving 15+ enterprise clients over 7 years
- Evolved the product from manual feature-based conversion (2019) to fully autonomous AI-driven migration (2025)
- Processed 100,000+ database objects across Oracle, PostgreSQL, SQL Server, Snowflake, and Databricks
- Delivered 15+ large-scale enterprise migrations with 98% automation rate

---

#### QMigrator Development: Agentic Release and Migration Automation Platform | 2025 - Present

Integrated and productionized a multi-agent QMigrator automation platform. Several component agents were developed by different contributors/teams; my role focused on end-to-end integration, orchestration, request/status lifecycle, A2A communication, DevOps hand-off, testing automation, and production readiness.

**Release Agent — Multi-Agent Orchestration and Status Control**
- Integrated Release Agent as the central controller for migration releases, using a configurable agent DAG to run Assessment, Conversion, Data Migration, Testing Workload, API, UI, DB, and DevOps components
- Implemented Google A2A/ADK-style agent-to-agent integration using Agent Cards, JSON-RPC message/send, task polling, webhook signals, and shared job correlation
- Added release request persistence, component-level status tracking, checkpointer-backed recovery, DevOps build status polling, and QCam UI progress updates
- Stack: Python, FastAPI, LangGraph, PostgreSQL checkpointing, Google A2A SDK patterns, Azure DevOps, YAML configuration

**Migration Agent — AI Migration Path Generation Engine**
- Integrated Assessment, Conversion, Data Migration, and Testing Workload agents as standalone LangGraph workflows exposed through REST and A2A server endpoints
- Supported migration path generation, reference selection, template adaptation, validation/fix loops, PR creation, artifact publishing, and upstream hand-off between agents
- Extended the platform to allow common dispatcher/main file updates when required while preserving existing function signatures
- Stack: Python, FastAPI, LangGraph, LangChain-style tool loops, Azure OpenAI/Claude/Gemini/Ollama, Azure Blob, Azure DevOps PR APIs

**API/UI/DB Agent Integration — Product Surface Automation**
- Integrated API Agent for QMigrator backend assessment controller scaffolding, .NET operation libraries, route constants, DI registration, and database-specific operations
- Integrated UI Agent for Angular 17 migration-type wiring across constants, services, enums, connection screens, schema extraction, E2E migration, and configuration flows
- Integrated DB Agent for database repository branch and pull-request automation as part of the release component flow
- Stack: FastAPI, Angular 17, .NET/QMigrator API conventions, Azure DevOps, Git automation

**DevOps Agent and Testing Automation — Deployment Validation Loop**
- Integrated DevOps Agent for Azure DevOps pipeline triggering, ArgoCD bootstrap, Azure project bootstrap, SaaS infra/Terraform setup, release summaries, and build remediation support
- Added pipeline build status polling with simple status outputs: running, success, failed
- Integrated Testing Automation after DevOps build success, including external trigger/status APIs, 60-second polling, E2E result interpretation, AI triage/remediation, redeploy, and retry loops
- Stack: Azure DevOps, ArgoCD, Kubernetes, Docker, Terraform workflows, Playwright/E2E automation APIs, FastAPI

**Conversion Agent Stage 1 and Stage 2 — Migration Error Resolution and Module Enhancement**
- Built and integrated Conversion Agent Stage 1 for automated migration error correction, SQL/code fix suggestions, and migration issue resolution workflows
- Built and integrated Conversion Agent Stage 2 for root-cause module fixes, reusable conversion module updates, and recurring conversion error reduction
- Stack: Python, FastAPI, LangChain, LangGraph, Azure OpenAI/Anthropic/Gemini/Ollama, migration validators, Excel/CSV processing

**Debug Mode, DBA, and Performance Agents — Expert Migration Assistants**
- Built Debug Mode Agent for human-in-the-loop debugging with snippet isolation, iterative fix validation, and audit-friendly review cycles
- Built DBA Agent for natural-language database analysis and DBA support across PostgreSQL, Oracle, SQL Server, and related migration environments
- Built Performance Agent for SQL query tuning, execution-plan analysis, index recommendations, and query optimization support
- Stack: Python, FastAPI, LangChain, SQLAlchemy, PostgreSQL, Oracle, SQL Server

**Dev Conversion, Connector, and Test Coverage Agents — Workflow Automation**
- Built Dev Conversion Agent for development/testing workflow support with run tracking, debugging assistance, and migration conversion validation
- Built Connector Agent for connector automation and migration integration support
- Built Test Coverage Agent for automated coverage assistance and validation support
- Stack: Python, FastAPI, Streamlit, LangChain/LangGraph, multimodel LLM integrations

#### QMigrator Development: Multi-LLM Infrastructure | 2025 - Present

- Architected enterprise-grade LLM abstraction layer supporting Azure OpenAI, Anthropic Claude, Groq, Google Gemini, and Ollama
- Built dynamic model switching with cost optimization, fallback mechanisms, and token usage tracking
- Integrated AI guardrails and evaluation frameworks (DeepEval, Ragas) for quality assurance and safety
- Standardized agent communication surfaces with A2A/ADK-style contracts so independently built agents could be discovered, invoked, tracked, and chained consistently
- Stack: Python, LangChain, DeepEval, Ragas, JSON/YAML Configuration

#### QMigrator Development: Core Migration Engine | 2021 - 2022

- Developed core migration engine components with modular Python architecture
- Built Django REST Framework APIs and React-based UI for migration workflow management
- Designed extensible plugin architecture supporting 50+ migration feature types

#### QMigrator Development: QBook V2 — Feature Management Platform | 2020 - 2021

- Created self-service platform enabling developers to register and manage migration features
- Built multi-level migration types, approval workflows, and version control for feature modules
- Developed full-stack Django + React application with admin dashboard serving 30+ developers

#### QMigrator Development: QBook V1 — Feature Management System | 2019 - 2020

- Established foundational architecture for feature-based migration approach
- Implemented developer registration, authentication, and approval workflows
- Built Python-based feature templates for standardized development across teams

---

### QMigrator Client Deployments

#### Project: CARELON HEALTH / ELEVANCE HEALTH — Sybase to SQL Server Migration
**Ongoing Migration Automation Support** | 2026 - Present

- Supporting ongoing Sybase to SQL Server migration work under the Carelon Health / Elevance Health account
- Applying the integrated QMigrator agent ecosystem for migration-path generation, API/UI/DB integration, DevOps orchestration, and Testing Automation validation
- Coordinating release flow across Migration Agent, Release Agent, DevOps Agent, QCam UI, and execution triage/remediation components
- Focused on reducing manual release coordination by standardizing request tracking, pipeline status, E2E testing feedback, and remediation loops

#### Project: NIKE — Cloud Data Platform Modernization
**Snowflake to Databricks Migration** | 2026 - Present

- Leading large-scale data platform migration for enterprise analytics on Databricks
- Designed ETL pipeline transformations achieving 98% data migration accuracy with automated validation
- Optimized query performance with 40% faster execution times on Databricks
- Deployed on AWS infrastructure with Delta Lake architecture for data lakehouse implementation

#### Project: eBAY — Enterprise Database Migration
**Oracle to PostgreSQL Migration** | 2024 - 2026

- Deployed Stage 1 and Stage 2 conversion agents for automated error correction pipeline
- Implemented Performance Agent for query optimization during migration
- Achieved 98% automation in schema conversion with AI-driven validation
- Deployed on AWS using ECS with Fargate, ECR, and API Gateway

#### Project: ELEVANCE HEALTH (Formerly Anthem) — Enterprise Migration
**SQL Server to Azure PostgreSQL** | 75,000+ Objects | 2024 - 2025

- Orchestrated AI agent workflows for complex PL/SQL to PL/pgSQL conversions
- Implemented Debug Mode for human-in-the-loop validation of critical business logic
- Achieved 95% conversion accuracy for stored procedures and functions
- Reduced manual intervention by 80% through intelligent agent automation

#### Project: UHG (United Health Group) — Enterprise Migration
**Oracle to PostgreSQL** | 50,000+ Objects, 2TB+ Data | 2023 - 2025

- Deployed all 6 AI agents to production serving 100+ concurrent users
- Achieved 98% schema conversion automation with AI-driven error correction
- Implemented Kubernetes-based architecture for horizontal scaling
- Reduced migration timeline by 60% compared to traditional approaches with zero-downtime deployment

#### Project: APOLLO HOSPITALS — Healthcare System Migration
**On-Premise Oracle to Azure PostgreSQL** | 2022 - 2024

- Managed weekly release cycles with comprehensive deployment validations
- Coordinated cross-functional teams (DBA, Application, Infrastructure) for seamless rollouts
- Ensured 100% compliance with healthcare data security standards (HIPAA)
- Achieved zero data loss during mission-critical healthcare system migration

---

## EDUCATION

**Master of Technology (M.Tech)** in Computer Science and Engineering  
KITS Engineering College, JNTU Kakinada — Kakinada, Andhra Pradesh

**Bachelor of Technology (B.Tech)** in Computer Science and Engineering  
Chalapathi Engineering College, JNTU Kakinada — Guntur, Andhra Pradesh

**Diploma** in Electrical and Electronics Engineering  
Al-Huda Polytechnic College, AICTE — Nellore, Andhra Pradesh

---

## CERTIFICATIONS

- Advanced LangChain and LangGraph Patterns for Production Systems
- Azure Solutions Architect — Cloud Infrastructure and DevOps
- Kubernetes Application Development and Container Orchestration
- Database Performance Tuning and Query Optimization
- Agile and Scrum Methodologies — Sprint Planning and Team Leadership

---

## LANGUAGES

- English: Professional Working Proficiency
- Telugu: Native
- Hindi: Professional Working Proficiency
