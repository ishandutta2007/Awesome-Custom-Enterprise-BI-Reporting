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
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Microsoft Power BI](https://powerbi.microsoft.com/)** | Microsoft's BI platform with desktop authoring and cloud publishing. Deep integration with Excel, Azure, and Microsoft 365. Power BI Embedded requires Fabric capacity for app embedding [citation:9]. | Pro: $14/user/month; Premium Per User: $24/user/month | **Free**: Power BI Desktop (authoring only); **60-day trial** for Pro/Premium |
| **[Tableau](https://www.tableau.com/)** | Visual analytics standard with drag-and-drop dashboards and extensive chart types. Acquired by Salesforce; per-seat Creator/Explorer/Viewer licensing. Strongest for analyst-driven visual exploration [citation:9]. | Quote-only (per-user licensing); Tableau Public free for public data | **Tableau Public**: free for publicly shared dashboards; **14-day trial** for full platform |
| **[Looker (Google Cloud)](https://looker.com/)** | BI platform built around LookML semantic modeling. Governed self-service with consistent metric definitions. Quote-based enterprise pricing. | Quote-only (enterprise contract; Google Cloud billing) | No free tier; trial via Google Cloud sales |
| **[Qlik Sense](https://www.qlik.com/)** | Associative analytics engine with in-memory data indexing. Positioned for exploratory analysis where users need to find unexpected relationships. | Quote-only (per-user or token-based) | No free tier; trial via sales |
| **[Sisense](https://www.sisense.com/)** | BI platform focused on embedded analytics for product teams. White-labeling and in-app dashboards. | Quote-only (custom enterprise pricing) | No free tier; demo via sales |
| **[Domo](https://www.domo.com/)** | Cloud BI platform with drag-and-drop dashboard builder, ETL, and embedded analytics. Consumption-based enterprise pricing. | Quote-only (consumption-based) | No free tier; demo via sales |
| **[IBM Cognos Analytics](https://www.ibm.com/products/cognos-analytics)** | Enterprise BI with reporting, dashboards, and AI-assisted exploration. Long-standing platform for large organizations with existing IBM investments. | Quote-only (per-user or capacity-based) | No free tier; trial via IBM sales |
| **[GoodData](https://www.gooddata.com/)** | Embedded analytics platform with semantic layer and white-labeling for SaaS products. | Quote-only (consumption-based) | **Community Edition**: free for up to 5 users (self-hosted); **trial** for cloud |
| **[SAP Crystal Reports](https://www.sap.com/)** | Pixel-perfect reporting engine for formatted, printable reports. Often deployed alongside SAP ERP or as a standalone reporting layer for operational documents. | Quote-only (per-user licensing) | No free tier; trial via SAP sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Apache Superset](https://github.com/apache/superset)** | [![Stars](https://img.shields.io/github/stars/apache/superset?style=social&color=white)](https://github.com/apache/superset/stargazers) | **The enterprise-grade open-source BI platform** (~75,100 stars, Apache-2.0). Ships with 40+ visualization types, a SQL IDE, no-code viz builder, and a plug-in architecture for custom charts [citation:3][citation:8]. **Critically, Superset is the only open-source BI tool that provides row-level security, embedding, and SSO for free**—Metabase gates these behind paid tiers, Tableau requires enterprise editions, and Power BI embedding needs Fabric capacity [citation:9]. Connects to any SQL database at petabyte scale. Heavier operational footprint (Redis + Celery + Kubernetes recommended). **Best for technical teams needing governance and scale.** |
| **[Metabase](https://github.com/metabase/metabase)** | [![Stars](https://img.shields.io/github/stars/metabase/metabase?style=social&color=white)](https://github.com/metabase/metabase/stargazers) | **The friendliest open-source BI tool** (AGPL). The open-source edition is **free with unlimited users, unlimited questions, unlimited dashboards**, and 20+ data source connections including PostgreSQL, MySQL, BigQuery, Snowflake, Redshift, and ClickHouse [citation:7]. Includes query builder, SQL editor, dashboard subscriptions, AI questions with your own model key, and guest embeds with a "Powered by Metabase" badge [citation:7]. **Best for business users who need to be productive in 30 minutes without SQL.** Paid cloud Starter ($100/month, 5 users) adds hosting, SOC 2, and multi-region options [citation:7]. |
| **[Lightdash](https://github.com/lightdash/lightdash)** | [![Stars](https://img.shields.io/github/stars/lightdash/lightdash?style=social&color=white)](https://github.com/lightdash/lightdash/stargazers) | **The BI platform built for dbt.** MIT-licensed core (with `ee/` directory source-available for enterprise features). Turns existing dbt models into dashboards without SQL—uses dbt YAML as the semantic layer [citation:4][citation:10]. Includes AI analyst co-pilot, version control, CI/CD tooling, and staging environments. Cloud Pro is **$3,000/month flat with unlimited users and viewers**, 21-day trial [citation:10]. **Best for dbt-native teams** where metrics are managed as code. Self-hosting requires Kubernetes, Postgres, S3, and a browserless container—platform team recommended [citation:10]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Redash](https://github.com/getredash/redash)** | [![Stars](https://img.shields.io/github/stars/getredash/redash?style=social&color=white)](https://github.com/getredash/redash/stargazers) | BSD-2 licensed SQL-first BI tool. Query editor with autocomplete, snippets, and results caching; dashboards with multiple visualizations; alerts and API [citation:4]. **In maintenance mode after Databricks acquisition**—still functional for existing deployments and simple SQL+viz workflows, but no new features [citation:4][citation:9]. |
| **[Helical Insight](https://github.com/helicalinsight/helicalinsight)** | [![Stars](https://img.shields.io/github/stars/helicalinsight/helicalinsight?style=social&color=white)](https://github.com/helicalinsight/helicalinsight/stargazers) | Open-source BI with **AI conversational analytics** (bring-your-own LLM), pixel-perfect paginated reports, interactive dashboards, SSO, embedding, multi-tenancy, and row-level security. **Every feature free in Community Edition**; Docker-ready [citation:11]. Positioned as a modern alternative to both dashboard builders and traditional reporting tools (JasperReports, BIRT, Crystal Reports) [citation:11]. |
| **[JimuReport](https://github.com/jeecgboot/jimureport)** | [![Stars](https://img.shields.io/github/stars/jeecgboot/jimureport?style=social&color=white)](https://github.com/jeecgboot/jimureport/stargazers) | Free open-source reporting and BI tool with **AI-powered generation** (JimuChatBI conversational analytics). Generates tables, charts, big screens, and grouped summaries from natural language. Supports 30+ databases including MySQL, Oracle, SQL Server, and PostgreSQL. Docker deployment [citation:6]. |

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
