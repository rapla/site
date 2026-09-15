---
title: Features
description: What Rapla 2 does today
---

Rapla speaks many languages: the user interface is available in English and German, with translations of varying completeness in French, Dutch, Polish, Spanish, Finnish, Portuguese (Brazil) and Czech.

![Main view with resource tree and week calendar](/images/rapla2_thumbnail.jpg)

## {{< icon "calendar-days" >}}Scheduling {#scheduling}

- Many specialised scheduling views besides the usual month, week and day calendars
- Reservations group appointments; repeating appointments with exceptions
- Conflict management — double bookings are shown before you save
- Support for {{< wiki "PeriodSupport" "periods" >}} such as semesters
- Read-only HTML month, week and day views
- PDF and iCal export
- Email notification when a resource is allocated

![Conflict view: two weekly reservations overlap on the same resource](/images/wiki/conflicts.png)

## {{< icon "settings" >}}Administration {#administration}

- A fine-grained {{< wiki "Permissions" "permission model" >}}: who may see, book or change what, and when
- Your own {{< wiki "DynamicTypes" "resource, person and event types" >}} with their own attributes
- {{< wiki "Categories" "Categories" >}} to model hierarchical organisations
- Plugins and table columns configurable in the preferences

![Preferences: plugin list and table view configuration](/images/wiki/tableconfig1.png)

## {{< icon "server" >}}Installation {#installation}

- Multi-user and multi-language
- Standalone application or client-server mode
- Desktop client via Java Web Start / OpenWebStart — no local installation
- Data in a file or a database: MySQL, PostgreSQL or HSQLDB

## {{< icon "monitor" >}}Supported platforms {#supported-platforms}

| | Platforms |
|---|---|
| Client | Linux, Windows, macOS with Java and OpenWebStart |
| Server | any platform with Java; Jetty included, or any servlet container such as Tomcat |

## {{< icon "code" >}}Developing {#developing}

- Plugin architecture with about a dozen plugins
- Free and open source — {{< wiki "DevelopersGuide" "contribute" >}}
