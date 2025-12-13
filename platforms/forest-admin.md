# Forest Admin
**Category:** Admin panel for databases/APIs

- **Summary:** Hosted admin UI that connects to your database or API via an agent, generating CRUD dashboards with permissions.
- **Strengths:**
  - Rapid setup for admin panels with smart views, search, filters, and export.
  - Granular RBAC, audit logs, and environment management suited to production data access.
  - Extensible with custom actions, charts, and segments; supports SQL/NoSQL and REST/GraphQL via agent.
- **Limitations:**
  - Requires deploying/maintaining an agent near your data; hosted UI but self-managed backend piece.
  - Complex business logic may require code in the agent; not fully no-code.
  - Pricing scales with seats/features; vendor lock-in to hosted UI.
- **Best for:** Teams needing secure, customizable admin panels fast without building UI from scratch.
- **Pricing snapshot:** Free trial; paid tiers per user/environment with enterprise options for SSO and audit.
- **Notable integrations:** Postgres/MySQL/SQL Server/MongoDB, REST/GraphQL via agent, custom actions, charts, webhooks.

- **Evaluation notes:**
  - Admin UI layer over your DB/API; data stays in your backend with an agent, preserving control but adding maintenance.
  - Strong granular permissions, audit logs, and approvals; good compliance story when hosted in your infra.
  - Works best for CRUD/back-office; heavy custom UI patterns may require code extensions and performance tuning of agent queries.
