# Henrique Proscholdt

## Data Engineer & AI Engineer | Software Architecture | Azure | Lakehouse

Construo pipelines de dados de ponta a ponta e sistemas de IA para produção.
Meu trabalho vive na intersecção entre **engenharia de dados**, **inteligência artificial** e **arquitetura de software** — sempre orientado a produto real, não prova de conceito.

---

## O que eu faço

### Engenharia de Dados
- Pipelines ETL com arquitetura **Medallion (Bronze / Silver / Gold)** em Azure Data Lake
- Modelagem dimensional: **star schema** com fato + dimensao
- Processamento com **Polars**, Pandas, PyArrow, PySpark
- Storage em **Parquet / Delta Lake** com carga incremental e deduplicacao via hash
- Integracao de multiplas fontes: APIs (Facebook Ads, Google Ads, Hotmart, Pipedrive), Google Sheets, webhooks
- Orquestracao de pipelines com controle sequencial e arquivamento automatico
- **Docker** para ambientes reprodutiveis

### Inteligencia Artificial Aplicada
- Sistemas RAG (retrieval-augmented generation) — tradicional, hibrido e multi-etapas
- Agentes especializados com **LangGraph / LangChain**
- Embeddings + busca vetorial com **Pinecone**
- Transcricao de video (Whisper) + indexacao semantica
- Assistentes de IA com memoria, roteamento e contexto de negocio

### Arquitetura de Software
- **Clean Architecture** com separacao em camadas (Router / Service / Factory / Repository)
- Principios **SOLID** aplicados em backends Python
- Camadas opacas: Service e Router nunca conhecem campos do DTO
- Factory como dona das regras de negocio
- Mensageria com **Azure Service Bus** para desacoplamento e escalabilidade
- APIs REST com **FastAPI** + processamento assincrono

---

## Projetos em destaque

### [Medallion Data Platform](https://github.com/proscholdt/medallion-data-platform)
Plataforma de engenharia de dados com 8 pipelines ETL integrados, arquitetura Medallion no Azure Data Lake, star schema na camada Gold e Docker.

`Python` `Polars` `PyArrow` `Delta Lake` `Azure Blob Storage` `Parquet` `Docker`

### Klaus — Assistente de IA
Assistente inteligente para ecossistemas educacionais: base vetorial, agentes especializados, memoria e roteamento por contexto.

`LangGraph` `LangChain` `Pinecone` `RAG` `FastAPI`

### Microservicos WhatsApp
Pipeline de mensageria com API oficial da Meta: payloads de eventos, templates dinamicos, filas desacopladas, retentativas.

`FastAPI` `Azure Service Bus` `Meta API` `Webhooks`

---

## Stack

<table>
<tr>
<td><b>Dados</b></td>
<td>Polars, Pandas, PyArrow, PySpark, Delta Lake, Parquet, SQL, Power BI</td>
</tr>
<tr>
<td><b>Cloud</b></td>
<td>Azure Data Lake Gen2, Azure Blob Storage, Azure Service Bus, Azure Synapse</td>
</tr>
<tr>
<td><b>IA / LLM</b></td>
<td>OpenAI API, LangGraph, LangChain, LangSmith, Pinecone, RAG, Whisper</td>
</tr>
<tr>
<td><b>Backend</b></td>
<td>Python, FastAPI, Clean Architecture, SOLID, REST APIs</td>
</tr>
<tr>
<td><b>Infra</b></td>
<td>Docker, Git, GitHub Actions</td>
</tr>
<tr>
<td><b>Frontend</b></td>
<td>SvelteKit, TypeScript, Tailwind CSS</td>
</tr>
</table>

---

## Tecnologias

<div align="left">
  <img width="50" height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" title="Python" />
  <img width="50" height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" title="FastAPI" />
  <img width="50" height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" title="Docker" />
  <img width="50" height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" title="Azure" />
  <img width="50" height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" title="PostgreSQL" />
  <img width="50" height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/microsoftsqlserver/microsoftsqlserver-original-wordmark.svg" title="SQL Server" />
  <img width="50" height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/svelte/svelte-original.svg" title="Svelte" />
  <img width="50" height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" title="TypeScript" />
  <img width="50" height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" title="Git" />
  <img width="50" height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" title="GitHub" />
</div>

---

## Foco atual

- Plataformas de dados com lakehouse architecture no Azure
- Sistemas de IA para producao com agentes e RAG
- Arquitetura de software orientada a dominios (Clean Architecture)
- Pipelines ETL incrementais com qualidade de dados

---

## Contato

Explore os repositorios para ver codigo real em producao — de pipelines de dados a sistemas de IA.
