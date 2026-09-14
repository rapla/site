---
title: Deployment
description: One JAR, a Docker image, and several pods if you need them.
weight: 60
---

Rapla 3 ships as a single Spring Boot JAR and as the container image `ghcr.io/rapla/rapla`.

Several instances can share one database and coordinate through the change history.

```sh
docker run -d --name rapla -p 127.0.0.1:8051:8051 \
  -v rapla-data:/opt/rapla/data -v rapla-logs:/opt/rapla/logs \
  ghcr.io/rapla/rapla:nightly
```

The volumes keep your data across restarts, and the port is only reachable from this machine. Set an admin password right after the first start.

![Server status page with version and build date](/images/rapla3/status-page.png)
