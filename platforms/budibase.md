# Budibase
**Category:** Internal tool builder (open-source)

- **Summary:** Open-source low-code platform for building internal tools from data sources with self-hosting and cloud options.
- **Strengths:**
  - Connects to SQL/NoSQL/data APIs; can host its own built-in database.
  - Component builder with permissions, environments, and automation workflows.
  - Self-hosted friendly (Docker/K8s) with open-source core; SSO and audit on paid tiers.
- **Limitations:**
  - Component polish and performance can lag commercial tools; smaller ecosystem.
  - Complex logic may need custom JavaScript/queries; not purely no-code.
  - Public-facing apps less refined; focused on internal/admin use cases.
- **Best for:** Teams wanting OSS internal tools with self-hosting, data connectors, and low-code flexibility.
- **Pricing snapshot:** Free OSS/self-host; cloud and enterprise plans add SSO, RBAC depth, audit, and support.
- **Notable integrations:** SQL databases, REST/GraphQL, Elasticsearch, S3, automation flows, webhooks.

- **Evaluation notes:**
  - Open-source internal tool builder; supports external data sources with caching, but lacks opinionated data modeling.
  - RBAC and SSO available on paid tiers; self-host enables more control though audits/logging are basic.
  - Works well for CRUD dashboards; performance depends on datasource latency and deployment sizing.
