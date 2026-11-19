## Brice Drouin · Wolf to Dev

[wolftodev.fr](https://wolftodev.fr)

**Full-stack web & AI developer, EPITA engineer, freelance since 2017.** I build websites on
WordPress, including my own site on a theme I wrote by hand. For startups and SMEs, I ship
software that runs on their real data: AI assistants on their documents, automated processes,
fast backends.

I test against real databases and publish the numbers. You'll get working software and plain
explanations of the trade-offs.

I also run **EXIST**, the web agency I founded in 2017: its work is shown on
[e-xist.fr](https://e-xist.fr).

<details>
<summary>🇫🇷 <b>Version française</b></summary>
<br>

**Brice Drouin, alias Wolf to Dev** · [wolftodev.fr](https://wolftodev.fr)

**Développeur web full stack et IA, ingénieur EPITA, freelance depuis 2017.** Je crée des sites
web sur WordPress, dont mon propre site, sur un thème que j'ai écrit à la main. Pour les startups
et les PME, je livre des logiciels qui tournent sur leurs vraies données : assistants IA sur leurs
documents, processus automatisés, backends rapides.

Je teste sur de vraies bases de données et je publie les chiffres. Vous obtenez un logiciel qui
marche et des explications claires sur les choix techniques.

**Ce que je peux faire pour vous :** un site vitrine ou e-commerce, avec un thème WordPress écrit
sur mesure et le référencement naturel (SEO) · un assistant IA sur vos documents (support,
interne, base de connaissances) · l'automatisation de vos processus (relances, commandes,
onboarding) · une API ou un backend qui tient la charge · un MVP SaaS solide, prêt pour de vrais
clients.

Je dirige aussi **EXIST**, l'agence web que j'ai fondée en 2017 : ses réalisations sont sur
[e-xist.fr](https://e-xist.fr).

</details>

---

### What I can build for you

| Service | What you get |
|---|---|
| **Websites on WordPress** | Business websites and online shops, WordPress with a custom theme, responsive layouts, SEO |
| **AI assistant on your documents** | Customer support, internal knowledge base, document search: answers with sources, measured quality |
| **Business process automation** | Follow-ups, orders, onboarding: workflows that run for days, wait for events and survive crashes |
| **APIs and backends** | Fast under load, secure by default, with metrics and traces from day one |
| **SaaS MVP** | Multi-tenancy, auth, background jobs, deployment: foundations you won't have to rewrite |

---

### Projects

#### 📚 [Corpus](https://github.com/WolfieToAI/corpus) · AI assistant on your documents

A multi-tenant "chat with your documents" platform: answers stream in with page-level citations,
and the quality is measured on a labelled set.

- **Accurate**: hybrid search, re-ranking and a labelled evaluation set (Recall@1 0.90, MRR 0.958)
- **Solid**: ~40 searches/s with 0% errors on 2 vCPU (without re-ranking), durable job queue with crash recovery
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

**[▶ Try the live demo](https://flowline-demo.onrender.com)** ·
[Code](https://github.com/WolfieToAI/flowline) ·
[Release notes](https://github.com/WolfieToAI/flowline/releases/latest) ·
[Explication technique (FR)](https://github.com/WolfieToAI/flowline/blob/main/docs/EXPLICATION-TECHNIQUE.md)

#### [wolftodev.fr](https://wolftodev.fr) · My own site, on a custom WordPress theme

The Wolf to Dev site runs on a WordPress theme I wrote by hand in HTML, CSS, JavaScript and PHP,
with no page builder. It's in French, English and Arabic, and the animations are part of the theme.

**[▶ Visit the site](https://wolftodev.fr)**

---

### How I work

I benchmark quality and speed, and I check every change against the numbers. Integration tests
run on real databases, concurrency and failure cases included. Metrics, traces and docs ship with
the code. You'll get regular demos and honest estimates, without jargon when it isn't needed.

### Stack

| Area | Tools |
|---|---|
| **Back end** | Python · FastAPI · TypeScript · Node.js · PostgreSQL (pgvector, RLS) · SQLAlchemy |
| **Front end** | React · Vite |
| **Web & CMS** | WordPress · PHP · HTML · CSS · JavaScript · SEO |
| **AI** | LLM APIs · RAG · embeddings · evaluation |
| **Ops** | Docker · GitHub Actions · OpenTelemetry · Prometheus · Grafana · Render |

---

📬 **Available for freelance projects, remote or on site.**
*Disponible pour des missions freelance, à distance ou sur site.*

[![Website](https://img.shields.io/badge/Website-wolftodev.fr-111827?logo=wordpress&logoColor=white)](https://wolftodev.fr)
[![Malt](https://img.shields.io/badge/Malt-Brice%20Drouin-FC5757)](https://www.malt.fr/profile/bricedrouin)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Brice%20Drouin-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/brice-drouin-068953280)
