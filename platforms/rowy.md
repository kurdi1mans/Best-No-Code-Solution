# Rowy
**Category:** Low-code backend (Firestore spreadsheet UI)

- **Summary:** Open-source spreadsheet-like UI for managing Firestore collections with cloud functions and automation.
- **Strengths:**
  - Works directly on Firestore; no data migration, keeps native Firebase auth/security rules.
  - Column types, roles, and triggers for workflows; integrates with Cloud Functions and third-party APIs.
  - Self-hostable and open-source; good for teams already on Firebase.
- **Limitations:**
  - Tied to Firestore/Firebase; not a general-purpose database for SQL workloads.
  - UI and ecosystem smaller than Airtable; requires Firebase familiarity.
  - Cloud Functions/trigger logic may need TypeScript; not purely no-code for complex flows.
- **Best for:** Teams using Firebase who want a spreadsheet UI and low-code triggers to manage data and automations.
- **Pricing snapshot:** Free OSS; managed hosting plans add usage-based pricing, SSO, and support.
- **Notable integrations:** Firebase Auth/Firestore/Cloud Functions, HTTP and third-party APIs, Zapier/Make via webhooks.

- **Evaluation notes:**
  - Spreadsheet UI for Firestore/BigQuery; real-time sync is strong but schema evolution and migrations need Firebase tooling.
  - Permissions inherit from Firebase rules; governance is as strong as your Firebase setup, though UI roles are basic.
  - Great for operational CRUD on Firebase data; performance tied to Firestore limits and indexing.
