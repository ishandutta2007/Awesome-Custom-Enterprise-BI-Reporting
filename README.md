# Awesome-Custom-Enterprise-BI-Reporting

## Top Custom Enterprise BI & Reporting Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Governed Self-Service Analytics, Embedded Reporting & Enterprise Data Exploration*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Custom Enterprise BI & Reporting**. These tools help organizations turn raw data into governed dashboards, pixel-perfect reports, and embedded analytics—covering everything from self-service exploration to scheduled distribution and row-level security.

**Examples** include Microsoft Power BI, Tableau, Looker, Qlik Sense, Sisense, Domo, IBM Cognos Analytics, GoodData, and open-source alternatives like Apache Superset and Metabase (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted BI, open-source reporting engines, and community-driven analytics platforms—ideal for organizations seeking data sovereignty and predictable costs over per-seat enterprise licensing. The open-source BI landscape has matured to the point where **Apache Superset offers enterprise governance features (RLS, embedding, SSO) for free**, while Metabase provides the friendliest self-service experience with a genuinely free unlimited-user tier [citation:9][citation:7].

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global Business Intelligence (BI) and analytics software market is estimated at **$33 billion to $35 billion in 2025** and projected to exceed **$40 billion by 2026**, growing at a CAGR of ~10–12% fueled by cloud migration and generative AI integration. The sector is **moderately fragmented**: mega-cap enterprise incumbents (Microsoft, Salesforce/Tableau, Google Cloud, SAP, IBM) control significant enterprise market share through ecosystem bundling, while a vibrant landscape of specialized SaaS vendors and open-source challengers thrive in areas like embedded analytics, code-first BI, and self-hosted governance.

## SaaS/Hosted Platforms

| Product | Valuation / Company Size | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|--------------------------|-------------|-------------------|--------------------------|
| **[Microsoft Power BI](https://powerbi.microsoft.com/)** | ~$3.1T Market Cap (Microsoft) | Microsoft's enterprise BI platform with desktop authoring and cloud publishing. Deep integration with Excel, Azure, and Microsoft 365. | $14/user/month (Pro); $24/user/month (Premium Per User) | **Free forever**: Power BI Desktop (local authoring only, no cloud sharing); **60-day trial** for Pro/Premium |
| **[Looker (Google Cloud)](https://looker.com/)** | ~$2.1T Market Cap (Alphabet) | Enterprise BI platform centered on LookML semantic modeling for governed self-service with consistent metric definitions. | $5,000/month (Standard Platform base with 10 Standard + 2 Developer users) | **No free forever tier**; **30-day trial** (via Google Cloud console / sales evaluation with $300 GCP trial credit) |
| **[Tableau](https://www.tableau.com/)** | ~$280B Market Cap (Salesforce) | Visual analytics platform with drag-and-drop dashboards and deep chart customization. Acquired by Salesforce. | $15/user/month (Viewer, billed annually); minimum 1 Creator required at $75/user/month | **Free forever**: Tableau Public (for publicly shared dashboards only); **14-day trial** for full Tableau Cloud/Creator |
| **[SAP Crystal Reports](https://www.sap.com/)** | ~$270B Market Cap (SAP SE) | Industry standard for pixel-perfect formatted and printable operational reports. | $495 one-time per user (Named User License) | **No free forever tier**; **30-day trial** (full report designer features) |
| **[IBM Cognos Analytics](https://www.ibm.com/products/cognos-analytics)** | ~$200B Market Cap (IBM) | Enterprise BI suite offering reporting, governed dashboards, and AI-assisted data exploration. | $11.25/user/month (Standard On-Demand Cloud tier) | **No free forever tier**; **30-day trial** (up to 5 Premium users, full capabilities) |
| **[Qlik Sense](https://www.qlik.com/)** | ~$10B Valuation (Thoma Bravo PE) | Associative analytics engine with in-memory data indexing for exploring complex relationships across disparate sources. | $300/month (Starter tier, includes 10 users and 10 GB data) | **No free forever tier**; **30-day trial** (full Qlik Cloud Analytics features, no credit card required) |
| **[Sisense](https://www.sisense.com/)** | ~$1.1B Valuation (Private / Late-stage) | Analytics platform specialized in embedded analytics and white-label customer-facing application dashboards. | $3,000/month (Entry/Essential tier, billed annually ~$36,000–$40,000/year) | **No free forever tier**; **7-day trial** (full access to cloud test drive, no credit card required) |
| **[Domo](https://www.domo.com/)** | ~$160M Market Cap (NASDAQ: DOMO) | Cloud-native BI platform featuring end-to-end data integration, visual ETL dataflows, and real-time executive dashboards. | $2,500/month (Base consumption tier starting ~$30,000/year for data credits, unlimited users) | **No free forever tier**; **30-day trial** (full platform access with unlimited users, no credit card required) |
| **[GoodData](https://www.gooddata.com/)** | ~$60M Annual Rev / Private (~$350M raised) | Cloud analytics and semantic layer platform tailored for multi-tenant SaaS application embedding. | $1,000/month (Professional tier with multi-tenant workspaces, unlimited users) | **No free forever tier**; **30-day trial** (full GoodData Cloud access, no credit card required) |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Apache Superset](https://github.com/apache/superset)** | [![Stars](https://img.shields.io/github/stars/apache/superset?style=social&color=white)](https://github.com/apache/superset/stargazers) | **The enterprise-grade open-source BI platform** (~75,500 stars, Apache-2.0). Ships with 40+ visualization types, a SQL IDE, no-code viz builder, and a plug-in architecture for custom charts. Superset provides row-level security, dashboard embedding, and enterprise SSO for free. Connects to any SQL database at petabyte scale. |
| **[Metabase](https://github.com/metabase/metabase)** | [![Stars](https://img.shields.io/github/stars/metabase/metabase?style=social&color=white)](https://github.com/metabase/metabase/stargazers) | **The user-friendly open-source BI tool** (~50,300 stars, AGPL). Free open-source edition supports unlimited users, questions, and dashboards with 20+ database connectors. Includes visual query builder, SQL editor, automated dashboard subscriptions, and guest embeds. |
| **[Redash](https://github.com/getredash/redash)** | [![Stars](https://img.shields.io/github/stars/getredash/redash?style=social&color=white)](https://github.com/getredash/redash/stargazers) | **SQL-first BI & visualization platform** (~28,900 stars, BSD-2). Provides interactive query editor with autocomplete and snippets, multi-chart dashboards, automated alerts, and REST API. |
| **[DataEase](https://github.com/dataease/dataease)** | [![Stars](https://img.shields.io/github/stars/dataease/dataease?style=social&color=white)](https://github.com/dataease/dataease/stargazers) | **Open-source Tableau alternative** (~24,700 stars, GPL-3.0). Modern web-based data visualization and dashboard platform with drag-and-drop report authoring, multi-data source connectivity, dataset modeling, and embedded sharing. |
| **[Cube](https://github.com/cube-js/cube)** | [![Stars](https://img.shields.io/github/stars/cube-js/cube?style=social&color=white)](https://github.com/cube-js/cube/stargazers) | **Universal semantic layer & embedded analytics engine** (~21,200 stars, Apache-2.0). Provides centralized data modeling, access control, caching/pre-aggregations, and SQL/REST/GraphQL APIs to power enterprise BI dashboards and client-facing analytics. |
| **[Perspective](https://github.com/perspective-dev/perspective)** | [![Stars](https://img.shields.io/github/stars/perspective-dev/perspective?style=social&color=white)](https://github.com/perspective-dev/perspective/stargazers) | **High-performance streaming analytics & reporting engine** (~11,400 stars, Apache-2.0). Originally created at J.P. Morgan, built in C++/WebAssembly for fast, interactive pivot tables and real-time streaming data visualization. |
| **[JimuReport](https://github.com/jeecgboot/jimureport)** | [![Stars](https://img.shields.io/github/stars/jeecgboot/jimureport?style=social&color=white)](https://github.com/jeecgboot/jimureport/stargazers) | **Enterprise reporting & dashboard builder** (~8,600 stars). Web-based drag-and-drop designer for complex enterprise print/export reports, operational dashboards, big-screen data displays, and barcode/QR reporting with JimuChatBI natural language queries. |
| **[Evidence](https://github.com/evidence-dev/evidence)** | [![Stars](https://img.shields.io/github/stars/evidence-dev/evidence?style=social&color=white)](https://github.com/evidence-dev/evidence/stargazers) | **Business intelligence as code** (~7,100 stars, MIT). Build fast, interactive reports and analytical applications using SQL and Markdown. Version-controlled in Git, rendered statically or deployed to serverless hosts. |
| **[Lightdash](https://github.com/lightdash/lightdash)** | [![Stars](https://img.shields.io/github/stars/lightdash/lightdash?style=social&color=white)](https://github.com/lightdash/lightdash/stargazers) | **The BI platform built for dbt** (~6,200 stars, MIT). Translates existing dbt models into self-service dashboards without raw SQL—using dbt YAML as the semantic single source of truth with version-controlled metric governance. |
| **[Rill](https://github.com/rilldata/rill)** | [![Stars](https://img.shields.io/github/stars/rilldata/rill?style=social&color=white)](https://github.com/rilldata/rill/stargazers) | **Fast code-first operational BI** (~3,000 stars, Apache-2.0). Powered by DuckDB and ClickHouse, Rill defines data models, metrics, and interactive dashboards as code files for low-latency operational exploration. |
| **[Helical Insight](https://github.com/helicalinsight/helicalinsight)** | [![Stars](https://img.shields.io/github/stars/helicalinsight/helicalinsight?style=social&color=white)](https://github.com/helicalinsight/helicalinsight/stargazers) | **Open-source framework for custom BI & reporting** (~1,100 stars). Supports AI conversational analytics, pixel-perfect paginated reports, interactive dashboards, multi-tenancy, and row-level security. |

**Frameworks for building custom systems**: Combine **Apache Superset** for governed self-service with free RLS/embedding/SSO, **Metabase** for business-user-friendly exploration with unlimited free users, and **Lightdash** for dbt-native metric layers managed as code—all deployable via Docker without per-seat licensing. For pixel-perfect operational reporting, **Helical Insight** or **JimuReport** fill the gap that dashboard-first tools leave open.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Enterprise BI platforms handle sensitive business metrics and customer data; enforce row-level security, SSO, and audit logging for dashboard access.
- **Open-source BI tools have a critical distinction in enterprise feature availability.** Apache Superset provides row-level security, embedding, and SSO **for free** [citation:9]. Metabase gates these behind paid tiers—the open-source edition is unlimited-user but lacks RLS and white-label embedding [citation:2][citation:7]. Lightdash's core is MIT but `ee/` features (SSO, custom roles, MCP server) require an Enterprise subscription [citation:10][citation:15]. **Redash is in maintenance mode**—avoid for new projects [citation:9]. Self-hosting costs are not zero: Superset requires ~0.25–0.5 FTE of operations effort, and it becomes cheaper than Tableau at roughly 80+ users [citation:9].

---

**Made for data analysts, BI developers, platform teams, and organizations building governed analytics infrastructure.**  
Let's make enterprise BI and reporting more open, governed, and cost-predictable.
