---
title: Login & API keys
description: Single sign-on, OAuth 2.0 and scoped API keys.
weight: 30
---

- **OAuth 2.0 with PKCE** for the web app and the desktop client
- **External identity providers** such as Microsoft Entra ID or Keycloak
- **Scoped API keys** for scripts and integrations, rotatable by the user

{{< shot "Account settings — API keys" >}}

Permissions are additive: a user gets the highest right any of their groups grants — the same model in the web app, the desktop client and the API.
