### Brice Drouin - Full-stack & AI developer · Développeur full stack & IA

Paris · Freelance

I build AI products that work on real data and hold up in production: assistants grounded in a
company's own documents, APIs and backends that stay fast under load, and SaaS foundations
(multi-tenancy, queues, observability) done right from day one.

*Je conçois des produits IA qui fonctionnent sur des données réelles et tiennent en production :
assistants qui répondent à partir des documents d'une entreprise, API et backends qui restent
rapides sous charge, et fondations SaaS (multi-tenant, files de tâches, supervision) solides dès
le départ.*

---

#### Featured project · Projet phare

**[Corpus](https://github.com/WolfieToAI/corpus)** - a multi-tenant "chat with your documents"
platform. Answers are streamed with page-level citations, and the whole thing is measured, tested
and operable.

| | |
|---|---|
| Retrieval | Hybrid search (pgvector + PostgreSQL full-text, RRF), cross-encoder re-ranking, query rewriting |
| Quality | Labelled evaluation set: Recall@1 0.90, MRR 0.958, published by CI |
| Performance | ~40 searches/s with 0 % errors on 2 vCPU (k6), graceful load shedding beyond |
| Security | Tenant isolation by PostgreSQL Row-Level Security, hashed and scoped API keys |
| Reliability | Durable job queue: leases, retries with backoff, dead-lettering, crash recovery |
| Operations | Prometheus, Grafana, OpenTelemetry traces across the queue, JSON logs |
| Product | Chat widget embeddable in one `<script>` tag; PDF (with OCR), Word, HTML |

[Release 1.0.0](https://github.com/WolfieToAI/corpus/releases/tag/v1.0.0) ·
[Architecture](https://github.com/WolfieToAI/corpus/blob/main/docs/ARCHITECTURE.md) ·
[Evaluation](https://github.com/WolfieToAI/corpus/blob/main/docs/EVALUATION.md) ·
[Load testing](https://github.com/WolfieToAI/corpus/blob/main/docs/OBSERVABILITY.md)

---

#### How I work · Ma façon de travailler

- **Measured, not assumed** - retrieval quality and latency are benchmarked, and every change is
  checked against the numbers. *Mesuré, pas supposé.*
- **Tested where it matters** - integration tests against real databases, concurrency and
  failure scenarios included. *Testé là où ça compte.*
- **Built to be run** - metrics, traces, alerts and documentation ship with the code.
  *Conçu pour être exploité.*

#### Stack

Python · FastAPI · PostgreSQL (pgvector, RLS) · SQLAlchemy · TypeScript · React · Docker ·
GitHub Actions · Prometheus · Grafana · OpenTelemetry · LLM APIs · RAG

---

Open to freelance missions, remote or in Paris. Contact details are on my GitHub profile.
*Disponible pour des missions freelance, à distance ou à Paris. Coordonnées sur mon profil GitHub.*
