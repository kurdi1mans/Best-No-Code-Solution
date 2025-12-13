# Xano
**Category:** Backend/database builder (API-first)

- **Summary:** No-code/low-code backend with database, authentication, and API builder for powering apps.
- **Strengths:**
  - Fast to model data and generate REST APIs with auth and rate limiting.
  - Serverless scaling handled by platform; background tasks and cron jobs available.
  - Marketplace of add-ons and functions; good Bubble/FlutterFlow partner.
- **Limitations:**
  - Complex business logic uses function stacks; debugging can feel opaque.
  - Vendor lock-in for backend; migrations to custom stacks require effort.
  - Pricing scales with records/storage/API limits.
- **Best for:** Startups needing a backend for mobile/web apps without managing infrastructure.
- **Pricing snapshot:** Free dev tier; paid for higher records/storage, environments, and collaboration.
- **Notable integrations:** REST/GraphQL, webhooks, OAuth providers, external DB connectors, Zapier/Make.

- **Evaluation notes:**
  - No-code backend with Postgres and auto-generated APIs; good schema tools but complex migrations need care.
  - Auth, RBAC, and row-level policies supported; audit/logging exist though customer-managed keys are limited.
  - Scales well for typical SaaS backends; vendor-managed infrastructure means some lock-in to their runtime.
