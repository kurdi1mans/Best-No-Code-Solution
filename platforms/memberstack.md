# Memberstack
**Category:** Membership/auth/payments layer

- **Summary:** Add-on for Webflow/JS sites to handle authentication, gated content, and subscriptions without building auth from scratch.
- **Strengths:**
  - Quick setup for login/signup, gated pages, and subscription/one-time payments.
  - Works well with Webflow and vanilla JS sites via embeds and front-end APIs.
  - Handles customer portal, emails, and basic profile data storage.
- **Limitations:**
  - Content gating depends on front-end; security relies on correct implementation.
  - Limited backend logic; complex workflows need external automation or custom code.
  - Pricing scales with members and features; not ideal for large free-user bases.
- **Best for:** Membership sites, paid communities, and course portals on Webflow or static sites needing fast auth/payments.
- **Pricing snapshot:** Free dev; paid tiers by active members with features like SSO, advanced roles, and white-labeling.
- **Notable integrations:** Webflow, custom JS SDK, Stripe, Zapier/Make, webhooks, simple user APIs.

- **Evaluation notes:**
  - Drop-in auth/payments for JAMstack sites; good for gated content but limited for complex tenant hierarchies.
  - Supports JWTs, hooks, and webhooks; audit, RBAC depth, and SSO/SCIM are minimal.
  - Stripe dependency drives pricing; scalability is fine for SMB memberships but enterprise compliance is light.
