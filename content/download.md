---
title: Download
description: Get Rapla
---

## {{< icon "download" >}}Rapla 2 — stable {#rapla-2--stable}

Releases up to 2.0 are on [GitHub: rapla/rapla releases](https://github.com/rapla/rapla/releases). Installation: {{< wiki "Installation-Guide" "installation guide" >}}.

## {{< icon "flask-conical" >}}Rapla 3 — nightly {#rapla-3-nightly}

Nightly builds of the development branch. Self-signed, untested, **not for production**.

| Channel | Where |
|---|---|
| JAR | [rapla.jar](https://github.com/rapla/rapla-releases/releases/download/nightly/rapla.jar) |
| Docker image | `ghcr.io/rapla/rapla:nightly` |

```sh
docker run -d --name rapla -p 127.0.0.1:8051:8051 \
  -v rapla-data:/opt/rapla/data -v rapla-logs:/opt/rapla/logs \
  ghcr.io/rapla/rapla:nightly
```

The volumes keep your data across restarts, and the port is only reachable from this machine. Set an admin password right after the first start.

Stable releases from 3.0 on will be published in [rapla/rapla-releases](https://github.com/rapla/rapla-releases/releases). [What's coming in Rapla 3 →](/rapla3.html)
