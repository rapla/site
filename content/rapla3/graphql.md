---
title: GraphQL API
description: One typed API for everything the clients can do.
weight: 20
_build:
  render: never
  list: always
---

Every resource type you configure in Rapla becomes a typed GraphQL object, so a room's attributes are real fields, not strings in a map.

```graphql
query {
  resources(filter: { isPersonEq: false, limit: 10 }) {
    name
    isLocation
    classification { typeKey }
  }
}
```

Filter by type with `typeIn` and read the typed attributes with a fragment such as `... on <TypeKey>Classification` — both are generated from your own resource types.

![GraphiQL with schema docs, a query and its result](/images/rapla3/graphiql.png)

## Stored views

Save a query with `@window` and `@param` as a named view — the web app renders it as a table or calendar without writing code.
