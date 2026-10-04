# Gabriel Campos Berlofa
**Software Engineer | Distributed Systems, Data Pipelines & AI Agents**

![React](https://img.shields.io/badge/React-19-149ECA?logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-strict-3178C6?logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-06B6D4?logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-8-646CFF?logo=vite&logoColor=white)
![Motion](https://img.shields.io/badge/Motion-physics-0055FF?logo=framer&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-CD792C?logo=polars&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

Atuo no desenvolvimento de software focado em arquitetura N-Tier, resiliência de dados e segurança em nível de aplicação. Atualmente graduando em Análise e Desenvolvimento de Sistemas (SENAI), aplico conceitos de Zero Trust, processamento assíncrono e otimização de recursos em projetos híbridos (Edge/Cloud), e integro IA em produção com aprovação humana nas ações críticas.

## Arquitetura & Domínio Técnico

| Domínio | Stack & Padrões de Projeto |
|---|---|
| **Arquitetura & Nuvem** | Edge & N-Tier, SaaS Multi-Tenant, Padrão Supervisor (multiagente), Docker Compose, Linux, Supabase, Render, Reverse Proxy / domínio próprio, Neon (PostgreSQL serverless), SSH (ufw, fail2ban), VirtualBox |
| **Core & Back-End** | Python, Java, FastAPI, Flask, SQLAlchemy, Pydantic, API REST, Asyncio, Multithreading, Gunicorn, migrações SQL versionadas |
| **Engenharia de Dados** | Polars (Lazy Evaluation), PostgreSQL, Supabase, DLQ (Dead Letter Queue), Circuit Breaker |
| **Segurança** | Zero Trust, IAM & Token Management, Licenciamento por hardware (HMAC-SHA256), Privacy by Design (LGPD/GDPR), Defesa contra Prompt Injection, Red Teaming, Sandbox & Menor Privilégio, bcrypt, JWT, Rate limiting, CORS, Zero-Data Egress |
| **IA & Agentes** | LangGraph, Human-in-the-Loop, Claude API, Ollama (Llama 3, Qwen), LLaVA, Gemini API, Prompt Engineering, benchmark de modelos locais, WhatsApp (Meta Cloud API), LangChain |
| **Qualidade & DevOps** | pytest, unittest, Vitest e Testing Library, GitHub Actions (CI/CD), testes com PostgreSQL real, fuzzing de validadores, Lighthouse, axe-core, PyInstaller, Inno Setup, Dependabot e gestão de dependências, análise estática (AST), pip-audit e npm audit |
| **Front-end & Interfaces** | HTML, CSS (Grid/Flexbox), JavaScript, TypeScript, React, Tailwind CSS, Motion (animações com física de mola), Feature-Sliced Design, CustomTkinter, acessibilidade (WCAG) e layout responsivo, Vite, Zustand, TanStack Query, Zod, Core Web Vitals |

## Projetos & Estudos de Caso

### ► Kuro SaaS — Distributed System & Software DRM
Ecossistema híbrido (Edge/Cloud) para gestão e automação de IA local, com processamento 100% no cliente (Zero-Data Egress).
* Motor de ingestão agnóstico em Polars, resiliência via DLQ, licenciamento Zero Trust por hardware, tolerância offline com cache assinado e suporte automatizado via WhatsApp. 81 testes automatizados, com CI contra PostgreSQL real.
* [↳ Ver Estudo de Caso de Arquitetura](https://github.com/Gabriel-nux/kuro-core-case-study)

### ► Kuro Agentic Workflow — Multi-Agent Orchestration & Zero-Trust Automation
Agentes de IA que vigiam e testam a infraestrutura do Kuro SaaS, fora do caminho das requisições dos clientes.
* Claude como Master e juiz, modelos locais (Ollama) como workers, ferramentas tipadas via SSH, aprovação humana para ações destrutivas, gatilhos automáticos somente leitura e Red Team em banco sintético. 239 testes automatizados.
* [↳ Ver Estudo de Caso de Arquitetura](https://github.com/Gabriel-nux/kuro-agentic-workflow-case-study)

### ► Forno & Código — E-commerce Full-Stack
Aplicação full-stack para uma pizzaria: cardápio e sacola com pizza meio a meio (preço do sabor mais caro), cadastro e login por API Flask com PostgreSQL e senhas em bcrypt.
* Front-end em HTML, CSS e JavaScript puros, com catálogo único e acessibilidade; back-end com testes automatizados e CI. Demo do front-end publicada via GitHub Pages. Migração para React + TypeScript em andamento (v2).
* [↳ Ver Demo ao Vivo](https://gabriel-nux.github.io/Forno-e-C-digo/)
* [↳ Ver Código-Fonte](https://github.com/Gabriel-nux/Forno-e-C-digo)

### ► Portfolio Web — React, TypeScript & Feature-Sliced Design
Portfólio que reúne os projetos, as competências e os estudos de caso, tratado como um projeto de engenharia.
* React 19, TypeScript estrito, Tailwind v4 e Motion, com arquitetura Feature-Sliced Design verificada por lint (Steiger), esquemas Zod, 34 testes e CI/CD no GitHub Actions. HTML pré-renderizado no build, com hidratação adiada.
* Lighthouse na URL pública (2026-10-04): celular 99 e desktop 99 em desempenho; 100 em acessibilidade, boas práticas e SEO. `axe-core` sem violações.
* [↳ Acessar Portfólio Ao Vivo](https://gabriel-nux.github.io/)
* [↳ Ver Código-Fonte e Arquitetura](https://github.com/Gabriel-nux/Gabriel-nux.github.io)

## Contato
* **E-mail:** berlofaspike@gmail.com
* **LinkedIn:** [linkedin](https://www.linkedin.com/in/gabriel-berlofa-b65a31431/)
