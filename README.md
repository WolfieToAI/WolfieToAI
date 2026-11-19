## Brice Drouin · Wolf To Dev

[wolftodev.fr](https://wolftodev.fr)

**Senior software engineer, EPITA graduate, independent since 2017.** Nine years of software
engineering: fixed-term contracts at Criteo, Doctolib and OVHcloud (2017 to 2022), then seven
freelance missions since April 2022, from BlaBlaCar to Bpifrance. The path starts with code in
production, goes through operations, then up to architecture and technical audit. I also build
websites on WordPress, including my own site on a theme I wrote by hand.

I test against real databases and publish the numbers. You'll get working software and plain
explanations of the trade-offs.

Since January 2023, I've also run **EXIST**, the web agency I founded: its work is shown on
[e-xist.fr](https://e-xist.fr).

<details>
<summary>🇫🇷 <b>Version française</b></summary>
<br>

**Brice Drouin, alias Wolf To Dev** · [wolftodev.fr](https://wolftodev.fr)

**Développeur senior, ingénieur EPITA, indépendant depuis 2017.** Neuf ans d'ingénierie
logicielle : CDD chez Criteo, Doctolib et OVHcloud (2017 à 2022), puis sept missions freelance
depuis avril 2022, de BlaBlaCar à Bpifrance. Mon parcours part du code en production, passe par
l'exploitation, puis remonte vers l'architecture et l'audit technique. Je crée aussi des sites
WordPress, dont mon propre site, sur un thème que j'ai écrit à la main.

Je teste sur de vraies bases de données et je publie les chiffres. Vous obtenez un logiciel qui
marche et des explications claires sur les choix techniques.

**Ce que je peux faire pour vous :** un site vitrine ou e-commerce, avec un thème WordPress écrit
sur mesure et le référencement naturel (SEO) · un assistant IA sur vos documents (support,
interne, base de connaissances) · l'automatisation de vos processus (relances, commandes,
onboarding) · une API ou un backend qui tient la charge · un MVP SaaS solide, prêt pour de vrais
clients.

Depuis janvier 2023, je dirige aussi **EXIST**, l'agence web que j'ai fondée : ses réalisations sont sur
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

The Wolf To Dev site runs on a WordPress theme I wrote by hand in HTML, CSS, JavaScript and PHP,
with no page builder. It's in French, English and Arabic, and the animations are part of the theme.

**[▶ Visit the site](https://wolftodev.fr)**

---

### Experience

| Period | Company | Role | Contract |
|---|---|---|---|
| Mar 2026 to now | **Bpifrance** | Technical due diligence expert | Freelance |
| Jul 2025 to Feb 2026 | **Orange Business** | AI developer (RAG, agents, LLM evaluation) | Freelance |
| Nov 2024 to Jun 2025 | **Back Market** | Analytics engineer (dbt, BigQuery, A/B tests) | Freelance |
| Apr 2024 to Oct 2024 | **Airbus** | Cloud architect (AWS landing zone, Terraform) | Freelance |
| Sep 2023 to Mar 2024 | **Société Générale CIB** | Quantitative Python developer | Freelance |
| Jan 2023 to Aug 2023 | **Decathlon Digital** | Design system lead (Vitamin, WCAG 2.1 AA) | Freelance |
| Apr 2022 to Dec 2022 | **BlaBlaCar** | Mobile developer (Kotlin, Swift) | Freelance |
| Jan 2021 to Mar 2022 | **OVHcloud** | Site Reliability Engineer (managed Kubernetes) | Fixed-term |
| Sep 2019 to Dec 2020 | **Doctolib** | Full-stack developer (Rails, React) | Fixed-term |
| Sep 2017 to Aug 2019 | **Criteo** | Backend software engineer (real-time bidding) | Fixed-term |

Since January 2023: founder of **EXIST**, a web agency ([e-xist.fr](https://e-xist.fr)). 2012 to 2017: engineering degree in computer science, **EPITA**.
Full details: [CV and portfolio on wolftodev.fr](https://wolftodev.fr/a-propos/).

---

### How I work

I benchmark quality and speed, and I check every change against the numbers. Integration tests
run on real databases, concurrency and failure cases included. Metrics, traces and docs ship with
the code. You'll get regular demos and honest estimates, without jargon when it isn't needed.

### Stack

| Area | Tools |
|---|---|
| **Languages** | C# · Java · Scala · Ruby · Python · Go · Kotlin · Swift · TypeScript · JavaScript · SQL · C++ |
| **Back end & distributed** | .NET · Ruby on Rails · FastAPI · Node.js · Fastify · Kafka · Spark · REST & gRPC · PostgreSQL (pgvector, RLS) · Redis · Elasticsearch |
| **Front end & mobile** | React · Next.js · Storybook · design tokens · Jetpack Compose · SwiftUI · WCAG 2.1 AA |
| **Web & CMS** | WordPress · PHP · HTML · CSS · JavaScript · SEO |
| **Cloud & infrastructure** | Kubernetes · OpenStack · AWS · Terraform · Ansible · Docker · GitLab CI · GitHub Actions · Prometheus · Grafana · OpenTelemetry |
| **Data & AI** | dbt · BigQuery · Airflow · A/B testing · RAG · embeddings · vector databases · LLM evaluation |
| **Practices** | Code review · TDD · trunk-based development · SLOs & error budgets · post-mortems · ADRs |

---

📬 **Available for freelance projects, fully remote.**
*Disponible pour des missions freelance, 100 % à distance.*

[![Website](https://img.shields.io/badge/Website-wolftodev.fr-111827?logo=wordpress&logoColor=white)](https://wolftodev.fr)
[![Malt](https://img.shields.io/badge/Malt-Brice%20Drouin-FC5757)](https://www.malt.fr/profile/bricedrouin)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Brice%20Drouin-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/brice-drouin-068953280)
