# NocoDB
**Category:** Open-source database/spreadsheet

- **Summary:** Open-source Airtable alternative that turns databases (Postgres/MySQL/SQL Server) into spreadsheet-like views with API generation.
- **Strengths:**
  - Self-hosted; connects to existing SQL databases without migrating data.
  - Generates REST/GraphQL APIs automatically; role-based permissions per table/view.
  - Supports forms, views, and extensions; active OSS community.
- **Limitations:**
  - Hosting and scaling are user-managed unless using the cloud offering.
  - Some UI/UX rough edges vs. polished SaaS tools; fewer native automations.
  - Ecosystem smaller than Airtable; complex workflows may need external automation.
- **Best for:** Teams wanting Airtable-like UI on top of their own database with open-source control.
- **Pricing snapshot:** Free OSS; paid cloud for hosting, SSO, audit, and enterprise features.
- **Notable integrations:** REST/GraphQL APIs, webhooks, Zapier/Make connectors, plugins, external DB connectors.

- **Evaluation notes:**
  - Maps existing SQL tables to spreadsheet views; great for data staying in your DB, but migrations are up to you.
  - Row-level permissions and audit features are evolving; self-host provides residency and backup control.
  - API generation is handy; performance hinges on underlying SQL tuning and connection pooling.
