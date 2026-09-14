---
title: Try the Rapla 3 demo
linkTitle: Demo
description: A public Rapla 3 instance to click through — reset every night.
weight: 5
tour: false
---

The demo at [demo.rapla.org](https://demo.rapla.org/) runs the current development version of Rapla 3 in your browser.

{{< cards >}}
{{< card "Open the web app" "https://demo.rapla.org/app/" >}}Calendar views, events, resources and the template picker.{{< /card >}}
{{< card "Open GraphiQL (after login)" "https://demo.rapla.org/graphiql/" >}}Explore the GraphQL API with schema docs and autocompletion. Log in to the web app first — GraphiQL uses the same session.{{< /card >}}
{{< /cards >}}

## Log in

The login page of the demo tells you which account to use. More demo users for different roles — planner, lecturer, student, desk staff and a faculty group admin — are listed on the [demo start page](https://demo.rapla.org/).

## Good to know

- **Everything resets every night** at 04:15 (Europe/Berlin). Feel free to change, create and delete — your changes are gone the next morning, and so are other visitors' changes.
- **Sample data:** a small faculty over one academic year — courses, rooms, lecturers, loanable equipment and booking requests.
- **Web app only.** The desktop client is not available on the demo.
- **Shared instance.** Other visitors use the same data at the same time — please do not enter personal information.

## What to try

- Create an event in the week view and move it by drag & drop.
- Add a resource type with your own attributes in GraphiQL, using the `saveDynamicType` mutation — a type editor in the web app is on its way.
- Run a query in GraphiQL, for example `{ resources(filter: { limit: 5 }) { name } }`.

Direct links to views and public calendars are on the [demo start page](https://demo.rapla.org/).
