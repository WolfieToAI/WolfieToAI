## Hi, I'm Brice 👋

**Freelance full-stack & AI developer in Paris.** I help startups and SMEs ship software that
works on their real data and keeps working in production: AI assistants grounded in their own
documents, automated business processes, and fast, reliable backends.

I care about the parts most demos skip: tests against real databases, numbers instead of
promises, and systems that recover when something breaks. You get working software, clear
documentation, and someone who explains the trade-offs in plain words.

<details>
<summary>🇫🇷 <b>Version française</b></summary>
<br>

**Développeur freelance full stack & IA, à Paris.** J'aide les startups et les PME à livrer des
logiciels qui fonctionnent sur leurs vraies données et tiennent en production : assistants IA qui
répondent à partir de leurs propres documents, processus métier automatisés, backends rapides et
fiables.

Je soigne ce que la plupart des démos oublient : des tests sur de vraies bases de données, des
chiffres plutôt que des promesses, et des systèmes qui repartent quand quelque chose casse. Vous
obtenez un logiciel qui marche, une documentation claire, et un interlocuteur qui explique les
choix simplement.

**Ce que je peux faire pour vous :** un assistant IA sur vos documents (support, interne, base de
connaissances) · l'automatisation de vos processus (relances, commandes, onboarding) · une API ou
un backend qui tient la charge · un MVP SaaS solide, prêt pour de vrais clients.

</details>

---

### What I can build for you

| Service | What you get |
|---|---|
| 🤖 **AI assistant on your documents** | Customer support, internal knowledge base, document search: answers with sources, measured quality |
| ⚙️ **Business process automation** | Follow-ups, orders, onboarding: workflows that run for days, wait for events and survive crashes |
| 🚀 **APIs and backends** | Fast under load, secure by default, with metrics and traces from day one |
| 🧱 **SaaS MVP** | Multi-tenancy, auth, background jobs, deployment: foundations you won't have to rewrite |

---

### Projects

#### 📚 [Corpus](https://github.com/WolfieToAI/corpus) · AI assistant on your documents

A multi-tenant "chat with your documents" platform: answers stream in with page-level citations,
and the quality is measured, not guessed.

- **Accurate**: hybrid search, re-ranking and a labelled evaluation set (Recall@1 0.90, MRR 0.958)
- **Solid**: ~40 searches/s with 0 % errors on 2 vCPU, durable job queue with crash recovery
- **Secure**: tenant isolation enforced by PostgreSQL Row-Level Security, scoped API keys
- **Easy to adopt**: a chat widget in one `<script>` tag; PDF (with OCR), Word and HTML

**[▶ Try the live demo](https://corpus-8jf9.onrender.com/demo)** ·
[Architecture](https://github.com/WolfieToAI/corpus/blob/main/docs/ARCHITECTURE.md) ·
[Evaluation](https://github.com/WolfieToAI/corpus/blob/main/docs/EVALUATION.md)

#### 🔁 [Flowline](https://github.com/WolfieToAI/flowline) · Durable workflows for TypeScript

A workflow engine for business processes that must never lose a step: create an order, wait
three days for the payment, send a reminder, even if servers restart in between.

- **Crash-proof**: tested by killing workers mid-step; every run finishes, no step is recorded twice
- **Visual**: a drag-and-drop flow editor and a live dashboard of every run, retry and failure
- **Fast**: up to ~850 runs/s on a laptop, idle workers wake up in ~8 ms
- **Observable**: OpenTelemetry traces and metrics for every step

[Code](https://github.com/WolfieToAI/flowline) ·
[Release notes](https://github.com/WolfieToAI/flowline/releases/latest) ·
[Explication technique (FR)](https://github.com/WolfieToAI/flowline/blob/main/docs/EXPLICATION-TECHNIQUE.md)

---

### How I work

- **Measured, not assumed**: quality, latency and throughput are benchmarked, and every change
  is checked against the numbers.
- **Tested where it matters**: integration tests on real databases, including concurrency and
  failure scenarios.
- **Built to be run**: metrics, traces and documentation ship with the code.
- **Clear communication**: regular demos, honest estimates, no jargon when it isn't needed.

### Stack

| Area | Tools |
|---|---|
| **Back end** | Python · FastAPI · TypeScript · Node.js · PostgreSQL (pgvector, RLS) · SQLAlchemy |
| **Front end** | React · Vite |
| **AI** | LLM APIs · RAG · embeddings · evaluation |
| **Ops** | Docker · GitHub Actions · OpenTelemetry · Prometheus · Grafana · Render |

---

📬 **Available for freelance missions, remote or on site.**
*Disponible pour des missions freelance, à distance ou sur site.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Brice%20Drouin-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/brice-drouin-068953280)
