---
title: Login & API keys
description: Single sign-on, OAuth 2.0 and scoped API keys.
weight: 30
_build:
  render: never
  list: always
---

- **OAuth 2.0 with PKCE** for the web app and the desktop client
- **Sign in with Microsoft, Google or Keycloak** — Keycloak can connect your organisation's own identity provider
- **Scoped API keys** for scripts and integrations, rotatable by the user

![Login page with sign-in buttons for Microsoft, Google and Keycloak next to the local login](/images/rapla3/login-providers.png)

![Account settings: API keys with scope and expiry](/images/rapla3/api-keys.png)

Permissions are additive: a user gets the highest right any of their groups grants — the same model in the web app, the desktop client and the API.
