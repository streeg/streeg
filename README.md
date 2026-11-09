<p align="right"><a href="https://github.com/streeg"><img src="assets/lang-en-on.svg" alt="English (current)"></a><a href="https://github.com/streeg/streeg/blob/master/README.pt-BR.md"><img src="assets/lang-pt-off.svg" alt="Ler em português"></a></p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" width="100%" alt="Guilherme Andreúce, Senior Full-Stack Developer. I build the business-critical parts of a product: search, revenue, payments, integrations and deploys, with AI in the loop.">
</picture>

<p align="center"><a href="https://streeg.github.io"><img src="assets/btn-website.svg" alt="Website"></a><a href="https://www.linkedin.com/in/guilherme-andre%C3%BAce-monteiro-4b046814b/"><img src="assets/btn-linkedin.svg" alt="LinkedIn"></a><a href="mailto:guilhermeandreuce@gmail.com"><img src="assets/btn-email.svg" alt="Email"></a><a href="https://t.me/guileb"><img src="assets/btn-telegram.svg" alt="Telegram"></a></p>

<p align="center"><sub><a href="#impact"><b>Impact</b></a> &nbsp;·&nbsp; <a href="#experience"><b>Experience</b></a> &nbsp;·&nbsp; <a href="#stack"><b>Stack</b></a> &nbsp;·&nbsp; <a href="#security--research"><b>Security</b></a> &nbsp;·&nbsp; <a href="#projects"><b>Projects</b></a> &nbsp;·&nbsp; <a href="#lets-talk"><b>Contact</b></a></sub></p>

## Impact

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/impact-dark.svg">
  <img src="assets/impact-light.svg" width="100%" alt="7+ banking apps built at Dimensa for client banks like Banco BV, Travelex, Dock and Bankly, with Pix in production · ~3 years leading teams: two teams of 7 people at Dimensa and one of 7 at Ploomes · 13 CRM integrations · deploys moved from fragile to automated CI/CD on Kubernetes · search migrated from Sphinx to Elasticsearch, with keyword search and highlighted matches · built the placements module that runs the firm's placement revenue">
</picture>

## Experience

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/job-haistack-dark.svg">
  <img src="assets/job-haistack-light.svg" width="100%" alt="LateralLink · Haistack. Senior Full-Stack Developer, Oct 2026 – present and Oct 2022 – Nov 2024.">
</picture>

<details>
<summary><b>What I built at Haistack</b></summary>

- Migrated platform search from Sphinx to **Elasticsearch**, then added keyword search with highlighted matches across candidates, notes, emails and submissions.
- Built the **placements module** that runs the firm's placement revenue: commission splits, signing bonuses and deal notifications.
- Hardened **security** with SMS two-factor authentication, an API key lifecycle, vendor permission rules and CSV formula-injection protection.
- Shipped **LLM features** in the CRM, such as candidate recommendations and AI-drafted recruiter emails.
- Set up the team's **AI-assisted development workflow**: a shared knowledge base and runbooks that let coding agents investigate, plan and ship changes within the team's conventions.

</details>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/job-ploomes-dark.svg">
  <img src="assets/job-ploomes-light.svg" width="100%" alt="Ploomes. Senior Full-Stack Developer, Nov 2024 – Oct 2026.">
</picture>

<details>
<summary><b>What I built at Ploomes</b></summary>

- Replaced manual, unsafe deploys that often broke and needed rollbacks with **automated CI/CD on Kubernetes** for the email and integrations services, and made them stable.
- Consolidated the **email microservices into the monolith**, making the flow simpler to run and debug.
- Replaced Datadog with **OpenTelemetry** for logging and telemetry across the email services.
- Built and maintained [**13 CRM integrations**](https://www.ploomes.com/produto/integracoes): RD Station, ActiveCampaign, Neppo, Flowbiz, WhatsApp, Facebook Lead Ads, Mailchimp, Meetime, Omie, Outlook, Gmail, Google Calendar and Zenvia.
- Wrote the **missing documentation** for the email and integrations domains and created operational routines for them.
- Hardened the integrations: **OAuth** flows, **URL sanitization**, permission checks and a **secrets-rotation runbook**.
- Brought **AI-assisted development** into my workflow in early 2026, with context files for each service and an integrations knowledge base for coding agents.
- Refactored legacy code for maintainability and security, and **informally led a team of 7 for four months**.

</details>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/job-dimensa-dark.svg">
  <img src="assets/job-dimensa-light.svg" width="100%" alt="Dimensa (mobile2you). Mid-level Developer and Team Lead, 2019 – 2022.">
</picture>

<details>
<summary><b>What I built at Dimensa</b></summary>

- **Led two teams** of 7 people for two and a half years.
- At Dimensa (mobile2you), delivered **7+ white-label banking apps** for client banks such as [Banco BV](https://www.bv.com.br), [Travelex Bank](https://www.travelexbank.com.br), [Dock](https://dock.tech), [Bankly (Acesso)](https://bankly.com.br) and [Banco BBC Digital](https://bancobbcdigital.com.br), each tailored to the client's product and brand.
- Worked on the **Dimensa app**, the rebuild of the white-label platform itself.
- Implemented **Pix** payments and refunds in the white-label core, live in production across the apps built on it.

</details>

## Education

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/edu-unb-dark.svg">
  <img src="assets/edu-unb-light.svg" width="100%" alt="Education: Universidade de Brasília (UnB), Bachelor's degree in Computer Science.">
</picture>

## Stack

**Language-agnostic.** I pick the tool for the problem, not the other way around, and ramp up fast on new stacks.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stack-dark.svg">
  <img src="assets/stack-light.svg" width="100%" alt="Languages: TypeScript, JavaScript, Ruby, Python, Java, Lua. Frameworks: Rails, React, Node.js, Vue, Angular. Data and infrastructure: Elasticsearch, Redis, AWS, Docker, Kubernetes, Git, Linux.">
</picture>

## Security & research

Security runs through my work: from research on cryptographic API misuse to tests for a forensic tool used by the Federal Police.

<p align="center"><a href="https://github.com/streeg/tcc"><img src="assets/project-thesis.svg" width="49%" alt="Thesis: how third-party libraries affect cryptographic API misuse reports in Android apps, using CryptoGuard, CogniCrypt and LibScout."></a> <a href="https://github.com/sepinf-inc/IPED"><img src="assets/project-iped.svg" width="49%" alt="IPED: the Federal Police's digital forensics tool. I wrote unit tests for its evidence parsers and regex search, and fixed the bugs they uncovered."></a></p>

## Projects

<p align="center"><a href="https://github.com/streeg/Riposte"><img src="assets/project-riposte.svg" width="49%" alt="Riposte: a timing circle for every enemy hit in Clair Obscur: Expedition 33, plus a grace period that turns near-misses into reduced damage."></a></p>

**From the CS degree:** [Pipelined MIPS CPU](https://github.com/streeg/oac20191unb2) (VHDL) · [Compiler](https://github.com/streeg/guillex2) (C, Flex, Bison) · [Java Virtual Machine](https://github.com/Skalwalker/JVM) (C++) · [Pseudo operating system](https://github.com/streeg/pseudo-os) (Python)

## Let's talk

Always up for a conversation about product engineering, search, integrations or AI-assisted development. Based in Brasília, Brazil.

<p align="center"><a href="https://streeg.github.io"><img src="assets/btn-website.svg" alt="Website"></a><a href="https://www.linkedin.com/in/guilherme-andre%C3%BAce-monteiro-4b046814b/"><img src="assets/btn-linkedin.svg" alt="LinkedIn"></a><a href="mailto:guilhermeandreuce@gmail.com"><img src="assets/btn-email.svg" alt="Email"></a><a href="https://t.me/guileb"><img src="assets/btn-telegram.svg" alt="Telegram"></a></p>
