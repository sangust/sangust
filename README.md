# Olá, sou Gustavo Santana 👋

FullStack Engineer focado no desenvolvimento de APIs de alta performance, resiliência de microsserviços e engenharia de agentes de IA para produção.

---

##  Tech Stack

* **Backend & IA:** Python (FastAPI, Django), Celery, LangChain, LangGraph, vLLM, llama.cpp, pgvector.
* **Infra & Cloud:** Docker, AWS, GCP, Coolify, Redis, PostgreSQL, Linux, GitHub Actions.
* **Frontend:** React, TypeScript, TailwindCSS.

---

##  Projetos em Destaque

###  [AfiliBot Core] — IA & Busca Semântica
> Ecossistema distribuído em FastAPI e Celery para automação conversacional e recomendação por similaridade de vetores.

* **Busca Vetorial:** Similaridade de cosseno em sub-milissegundos usando **PostgreSQL + pgvector** e índice **HNSW** para vetores de 768 dimensões (`nomic-embed-text`).
* **AfiliBotDM:** Microsserviço de mensageria que processa webhooks da **Evolution API (WhatsApp)** e gerencia a memória contextual/RAG da LLM (`llama3`) via **Redis** com `ltrim` e TTL.

###  [Montseguro Core] — Microsserviços & Auditoria de IA
> Migração estratégica de monolito corporativo de seguros para arquitetura distribuída e tolerante a falhas.

* **Shadow API Core:** Desenvolvida via engenharia reversa para integrar o CRM Moskit, mitigando gargalos estritos de *rate limit*.
* **Auditoria de Vendas:** Pipeline de inteligência comercial com OpenAI (GPT-4o-mini) e arquitetura de *fallback* automático no **Groq** para controle de custos e alta disponibilidade.

---

##  Contato

* **LinkedIn:** [/in/zssantana](https://linkedin.com/in/zssantana)
* **Email:** [gustavosantana2006@gmail.com](mailto:gustavosantana2006@gmail.com)
