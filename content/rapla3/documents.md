---
title: Documents & templates
description: Loan slips, schedules and notices as HTML or PDF.
weight: 50
---

Documents pair a stored view with a [Mustache](https://mustache.github.io/) template. The server renders HTML; PDF comes straight from the browser's print dialog.

```mustache
<h1>Loan slip {{number}}</h1>
{{#items}}<li>{{name}} — due {{due}}</li>{{/items}}
```

{{< shot "Template editor with live preview" >}}

Planned: a loan lifecycle (lend, return, overdue) and a free-slot search across resources.
