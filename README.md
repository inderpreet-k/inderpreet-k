### Inderpreet Kaur
**Data Analytics · AI / ML · Power Platform**

BTech IT @ KPU Surrey · Co-op @ Fraser Health Authority · Graduating June 2027

I build tools that solve real problems. Currently automating infrastructure vulnerability reporting at Fraser Health — turning a fully manual monthly process into a self-service Power BI platform. Previously shipped a live ML web firewall (92% accuracy, 0 critical false negatives) and an AI bank statement analyzer deployed on Vercel — the firewall now protects the analyzer in production.

🇨🇦 Canadian Citizen — no sponsorship required in Canada or the US (TN Visa eligible).

---

#### 🩺 Currently — Fraser Health Authority (Jun 2026 – Present)
- Automated a monthly infrastructure vulnerability reporting process — previously a fully manual, ~1-week effort every month — into a self-service Power BI platform across 3,100+ managed servers
- Built folder-based ingestion with dynamic filename parsing and automated Power Query cleaning of merged monthly workbooks
- Implemented Role-Level Security with dynamic user-to-asset mapping so each application owner sees only their own data
- Designed executive and operational dashboards (trends, severity, aging, machine/asset views); fully built and self-tested, rollout to real users in progress

---

#### 🚀 Projects

| Project | Stack | Status |
|---|---|---|
| [Sentinel AI — ML Web Firewall](https://github.com/inderpreet-k/sentinel-ai) | Python · Scikit-Learn · FastAPI · PostgreSQL | 🟢 Live · 92% accuracy |
| [Spending Spotlight — AI Bank Analyzer](https://github.com/inderpreet-k/spending-spotlight) | React · OpenAI API · Flask · Vercel | 🟢 Live |
| [TransLink Transit Intelligence](https://github.com/inderpreet-k/translink-transit-intelligence) | PostgreSQL · Flask · Chart.js · GTFS | 📐 Design Complete (A+) · Build Sep–Dec 2026 |
| [Catering Management System](https://github.com/inderpreet-k/catering-management-system) | PHP · MySQL · XAMPP | ✅ Complete |

<br>

<details>
<summary><b>Sentinel AI — ML Web Firewall</b></summary>
<br>

**Goal:** Build a real-time ML web firewall any site can drop in — not just a single local app.

**Description:** Rebuilt from a single-machine PHP/MySQL academic prototype into a hosted, multi-tenant security API. Combines explicit rule matching with a trained ML classifier, deployed as FastAPI + PostgreSQL with SDKs in PHP, JS, and Python.

**Results:** 92% detection accuracy, 0 critical false negatives across SQL injection, XSS, and OS command injection — Random Forest trained on 24,161 labeled payloads, character-level TF-IDF n-grams. Currently protecting **Spending Spotlight** in live production traffic.

[Live demo](https://sentinel-ai-web.onrender.com/) · [GitHub](https://github.com/inderpreet-k/sentinel-ai)
</details>

<details>
<summary><b>Spending Spotlight — AI Bank Statement Analyzer</b></summary>
<br>

**Goal:** Let anyone upload a bank statement and instantly see which transactions were expected vs. unexpected.

**Description:** React frontend, Flask backend, GPT-4o-mini classification. Diagnosed real-world noise from Chase statement formatting and engineered pattern filtering end-to-end. Every request is screened live by **Sentinel AI** before processing.

[Live demo](https://spending-spotlight.vercel.app/)
</details>

<details>
<summary><b>TransLink Transit Intelligence Pipeline</b></summary>
<br>

**Goal:** Give TransLink riders plain-language route recommendations and interactive network visualizations, powered by full production GTFS data.

**Description:** Technical Lead on a KPU capstone team. Designed a two-layer PostgreSQL schema (raw staging + curated), full ERD, and a four-view dashboard — Network Overview, Route Analyser, Stop Deep-Dive, Comparison Tool.

**Results:** Schema validated against 242 routes, 63,250 weekly trips, and 1.85M+ stop-time records. Design phase complete with an A+ (INFO 4190). Implementation begins INFO 4290, Sep–Dec 2026.

[GitHub](https://github.com/inderpreet-k/translink-transit-intelligence)
</details>

<details>
<summary><b>Catering Management System</b></summary>
<br>

**Goal:** Give a catering business one platform to run admin, staff, and customer operations from.

**Description:** Full-stack system with separate admin, staff, and customer portals. Led backend architecture and relational schema design, and coordinated front-end integration across the team.

[GitHub](https://github.com/inderpreet-k/catering-management-system)
</details>

---

#### 🛠 Skills
**Data & Analytics** — Power Platform · Power BI · Power Automate · Tableau · PostgreSQL · MySQL · SQLite · Jupyter
**AI / ML** — Scikit-Learn · Random Forest · TF-IDF · OpenAI API · Pandas · NLTK
**Languages** — Python · JavaScript · SQL · PHP · Java
**Frameworks** — FastAPI · Flask · React

---

#### 🔗 Links
[Portfolio](https://inderpreet-k.github.io/) · [LinkedIn](https://linkedin.com/in/inderpreet-kaur29/) · Email

Surrey, BC · Open to remote & hybrid
Dean's Honour Roll ×4 · GPA 3.43 / 4.33 · KPU
