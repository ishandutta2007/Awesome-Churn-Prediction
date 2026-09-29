# Awesome-Churn-Prediction

## Top Churn Prediction Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Customer Health Scoring, Retention Automation, Revenue Forecasting & Proactive Engagement*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Churn Prediction**. These tools help Customer Success (CS), Revenue Operations, and Growth teams identify at-risk accounts, understand churn drivers, automate retention plays, and forecast recurring revenue.



**Examples** include Vitally, ChurnZero, Gainsight, Totango, Catalyst, Planhat, Optimove, Amplitude Predict, Custify, and Velaris (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom health scoring, and transparent customer data — ideal for teams that need full control over their retention infrastructure without per-account SaaS fees or vendor lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Gainsight](https://www.gainsight.com/)**

  The enterprise standard for Customer Success. Provides 360-degree customer views, health scores, success plans, journey orchestration, and revenue forecasting. Deep integration with Salesforce and CRM ecosystems. G2 rating: 4.4/5. Pricing is private but typically starts well above $20K/year .



- **[Vitally](https://www.vitally.io/)**

  Modern, developer-friendly Customer Success platform. Known for its clean API, flexible data model, and "Docs" feature for collaborative success plans. Implementation measured in weeks, not months. Strong automation engine for agile teams. Pricing typically well below Gainsight's, though still quote-based .



- **[ChurnZero](https://churnzero.com/)**

  Customer Success platform focused on real-time usage data and automated plays. Provides health scoring, in-app messaging, and churn alerts. Popular with mid-market B2B SaaS companies .



- **[Totango](https://www.totango.com/)**

  Customer Success platform with a modular, composable architecture. Offers health scores, success plays, and customer communities. Acquired by SAP in 2024 .



- **[Catalyst](https://catalyst.io/)**

  Customer Success platform focused on data-driven account management. Provides health scoring, playbooks, and revenue forecasting.



- **[Planhat](https://www.planhat.com/)**

  Customer platform combining CS, sales, and product data. Strong for European companies with flexible data modeling and automation.



- **[Optimove](https://www.optimove.com/)**

  Customer-led growth platform with AI-powered churn prediction and retention marketing. Focuses on B2C and B2B2C engagement.



- **[Amplitude Predict](https://amplitude.com/)**

  Product analytics platform with AI-powered churn prediction and behavioral cohort analysis. Predicts churn from product usage patterns.



- **[Custify](https://www.custify.com/)**

  Customer Success platform for SMB and mid-market SaaS. Provides health scores, automated tasks, and churn alerts at accessible price points.



- **[Velaris](https://www.velaris.io/)**

  Customer Success platform with AI-powered health scoring, churn prediction, and automation. Focuses on B2B SaaS retention.



## Open-Source GitHub Projects



- **[ChurnPilot](https://github.com/sehidesena/ChurnPilot)**

  **The most complete open-source churn prediction platform for e-commerce.** An intelligent platform that automates churn prediction and customer retention processes with **Agentic AI** . Flexible architecture designed for easy implementation and scaling across different sectors (originally telecom, pivoted to e-commerce). Provides ML-based churn scoring with feature engineering including `order_count`, `days_since_last_order` (recency), `MembershipTier`, and `ProductCategory` . **Open source**.



- **[Customer Intelligence for WooCommerce](https://wordpress.org/plugins/customer-intelligence-for-woocommerce/)**

  **The most mature open-source churn prediction tool for WooCommerce stores.** 100% WordPress-native with **no external API calls** — all processing happens on your server . Features: **Churn Prediction** with heuristic churn-risk scoring and configurable thresholds; **RFM Segmentation** with visual 5×5 matrix classifying customers into Champions, Loyal, At Risk, Lost, and more; **Customer Lifetime Value (CLV)** prediction; **Cohort Retention Heatmap**; and **Segment Export** compatible with Mailchimp, Klaviyo, and ConvertKit . Named as a free open-source alternative to Metorik ($50-200/mo) and Glew.io ($79+/mo) . **Open source**.



- **[CRMlytics](https://wordpress.org/plugins/crmlytics/)**

  **WooCommerce-native CRM with predictive churn analytics.** Combines machine learning, customer management, and email campaigns in one unified plugin . Features: **Churn risk identification** with health scores (0-100 scale: Excellent, Healthy, Good, Weak, Critical); **Customer Health Scoring** based on buying behavior; **RFM (Recency, Frequency, Monetary)** segmentation with visual matrix; **Expected future orders** prediction (30, 90, 180 days); and **Email campaign manager** targeted by segment . All processing runs locally — no external APIs, no monthly fees . **Open source**.



- **[Sentiment Evolution Tracker (MCP)](https://huggingface.co/spaces/MCP-1st-Birthday/mcp-nlp-analytics)**

  **Enterprise-ready MCP server for sentiment-based churn prediction.** Runs as a Model Context Protocol server that Claude (or any MCP-compatible LLM) can invoke . Features: **Churn probability scoring** with configurable thresholds; **Automated trend detection** (RISING/DECLINING/STABLE); **Real-time alerts** when risk exceeds 70%; **Persistent customer histories** in SQLite; and **Seven MCP tools** including `analyze_sentiment_evolution`, `detect_risk_signals`, `predict_next_action`, `get_high_risk_customers`, and `get_database_statistics` . Python 3.10+ with TextBlob and NLTK. **Open source**.



- **[SuiteCRM](https://github.com/salesagility/SuiteCRM)**

  **The world's most popular open-source CRM.** Can be fully customized to replicate Gainsight's 360-degree views and health metrics for **$0** . You own the data entirely with massive community support. **Requires a developer/admin** to set up the "Success" logic and health scores manually . 26,887+ stars. **AGPL-3.0**.



- **[Twenty](https://github.com/twentyhq/twenty)**

  **Modern open-source CRM built to replace Salesforce.** Highly flexible data model allows building custom Customer Success workflows for free . Natively collaborative for teams. Still in active development with a leaner feature set than SuiteCRM . **AGPL-3.0**.



- **[Helio](https://github.com/achref-soua/helio)**

  **Open-source growth platform with CDP, segmentation, and cross-channel journeys.** AI-native marketing automation that can be adapted for churn prediction and retention campaigns . Features: multi-tenant isolation with PostgreSQL row-level security; ClickHouse for analytics; Temporal for journey orchestration; and **~20,000 events/s ingestion capacity** . Self-hostable via Docker Compose or Helm. **Open source**.



### Additional Strong Open-Source Options



- **E-commerce Churn Prediction**: **Customer Intelligence for WooCommerce** (most mature, no external APIs), **CRMlytics** (health scores + email campaigns), **ChurnPilot** (Agentic AI, ML-based) .

- **CRM Foundations**: **SuiteCRM** (26,887 stars, fully customizable), **Twenty** (modern, flexible data model), **Odoo** (integrated ERP + CRM) .

- **MCP/AI-Powered**: **Sentiment Evolution Tracker** (LLM-invocable churn prediction via MCP) .

- **Growth Infrastructure**: **Helio** (CDP + segmentation + journeys, ~20k events/s) .



**Frameworks for building custom systems**: Combine **SuiteCRM** or **Twenty** for the CRM foundation, **Customer Intelligence for WooCommerce** for e-commerce churn prediction, **ChurnPilot** for ML-based scoring, and **Sentiment Evolution Tracker** for LLM-powered risk detection. Add **PostgreSQL** for persistence and **Docker** for deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Churn prediction platforms handle sensitive customer data; ensure compliance with GDPR, CCPA, and relevant data protection regulations.

- **Open-source reality**: The open-source ecosystem for churn prediction is **concentrated in e-commerce** (**Customer Intelligence for WooCommerce**, **CRMlytics**, **ChurnPilot**) and **CRM foundations** (**SuiteCRM**, **Twenty**) . For **B2B SaaS churn prediction** with product usage analytics, health scoring across multiple data sources, and automated success plays, commercial platforms (Gainsight, Vitally, ChurnZero) remain the primary choice. The open-source path requires significant custom development to match enterprise CS platform capabilities.



---



**Made for Customer Success leaders, Revenue Operations teams, and retention-focused product managers.**

Let's make churn prediction more open, transparent, and actionable.
