# Gabriel Campos Berlofa
**Software Engineer | Distributed Systems, Data Pipelines & AI Agents**

Atuo no desenvolvimento de software focado em arquitetura N-Tier, resiliência de dados e segurança em nível de aplicação. Atualmente graduando em Análise e Desenvolvimento de Sistemas (SENAI), aplico conceitos de Zero Trust, processamento assíncrono e otimização de recursos em projetos híbridos (Edge/Cloud), e integro IA em produção com aprovação humana nas ações críticas.

## Arquitetura & Domínio Técnico

| Domínio | Stack & Padrões de Projeto |
|---|---|
| **Arquitetura & Nuvem** | Edge & N-Tier, SaaS Multi-Tenant, Padrão Supervisor (multiagente), Docker Compose, Linux, Supabase, Render, Reverse Proxy / domínio próprio |
| **Core & Back-End** | Python, Java, FastAPI, Flask, SQLAlchemy, Pydantic, API REST, Asyncio, Multithreading |
| **Engenharia de Dados** | Polars (Lazy Evaluation), PostgreSQL, Supabase, DLQ (Dead Letter Queue), Circuit Breaker |
| **Segurança** | Zero Trust, IAM & Token Management, Licenciamento por hardware (HMAC-SHA256), Privacy by Design (LGPD/GDPR), Defesa contra Prompt Injection, Red Teaming, Sandbox & Menor Privilégio, bcrypt |
| **IA & Agentes** | LangGraph, Human-in-the-Loop, Claude API, Ollama (Llama 3, Qwen), LLaVA, Gemini API, Prompt Engineering, benchmark de modelos locais, WhatsApp (Meta Cloud API) |
| **Qualidade & DevOps** | pytest, unittest, GitHub Actions (CI/CD), testes com PostgreSQL real, fuzzing de validadores, PyInstaller, Inno Setup |
| **Front-end & Interfaces** | HTML, CSS (Grid/Flexbox), JavaScript, React, Tailwind CSS, CustomTkinter, acessibilidade e layout responsivo |

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
* Front-end em HTML, CSS e JavaScript puros, com catálogo único e acessibilidade; back-end com testes automatizados e CI. Demo do front-end publicada via GitHub Pages.
* [↳ Ver Demo ao Vivo](https://gabriel-nux.github.io/Forno-e-C-digo/)
* [↳ Ver Código-Fonte](https://github.com/Gabriel-nux/Forno-e-C-digo)

### ► Portfolio Web — Platform & Technical Showcase
Interface web responsiva que reúne os projetos, as competências e os estudos de caso.
* Deploy via GitHub Pages, HTML5/CSS3 sem frameworks, com foco em performance e acessibilidade.
* [↳ Acessar Portfólio Ao Vivo](https://gabriel-nux.github.io/)
* [↳ Ver Código-Fonte](https://github.com/Gabriel-nux/Gabriel-nux.github.io)

## Contato
* **E-mail:** berlofaspike@gmail.com
* **LinkedIn:** [linkedin](https://www.linkedin.com/in/gabriel-berlofa-b65a31431/)
