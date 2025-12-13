# Parabola
**Category:** Data automation/ETL (no-code)

- **Summary:** Drag-and-drop data flow builder for transforming, enriching, and moving data between SaaS apps.
- **Strengths:**
  - Visual graph of steps with built-in transforms (filter, merge, group) suited to ops teams.
  - Good for batch/recurring data workflows (CSV ingestion, enrichment, syncing).
  - Transparent step outputs aid debugging without code.
- **Limitations:**
  - Less real-time than Zapier/Make; oriented to batch flows.
  - Complex logic branching is limited compared to n8n/Make.
  - Pricing tied to credits/rows processed; large datasets can be costly.
- **Best for:** Operations/data teams cleaning and syncing datasets across SaaS tools without code.
- **Pricing snapshot:** Free trial; paid tiers based on credits/rows and scheduling frequency.
- **Notable integrations:** CSV/HTTP, Shopify, HubSpot, Salesforce, Google Sheets/BigQuery, Snowflake, S3, webhooks.

- **Evaluation notes:**
  - Visual ETL/dataflow for ops teams; works well for CSV/API ingestion and transformations but not real-time CDC.
  - Limited governance: user roles and run logs exist, yet SSO/audit depth are enterprise-only.
  - Pricing by row/run can climb with large datasets; scaling heavy workflows may need chunking and offloading to warehouses.
