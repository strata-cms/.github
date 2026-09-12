# Strata

**A CMS built in layers. Extended by design.**

Strata is an open-source, API-first content management system for Python and Django.

It is designed around a small, stable core and explicit extension points rather than framework magic. Content is structured and versioned, publishing is based on immutable revisions, and integrations such as search, caching, messaging, storage, and background processing live behind replaceable interfaces.

## What defines Strata

* **Structured content** — strongly defined content types and composable, versioned blocks.
* **Immutable revisions** — draft history and published state are explicit rather than hidden behind mutable rows.
* **Extensible by design** — content types, blocks, infrastructure adapters, admin functionality, and integrations can be provided by plugins.
* **API first** — delivery and management APIs are first-class interfaces.
* **Clean architecture** — domain logic is independent of Django ORM, HTTP, queues, caches, and other infrastructure.
* **Simple by default** — a useful installation should not require Redis, RabbitMQ, Celery, or an external search engine.
* **Production ready** — typing, automated testing, security analysis, dependency auditing, and containerized deployment are part of the standard development workflow.

## Main project

**[strata](https://github.com/strata-cms/strata)** — the Strata CMS core, Management API, Delivery API, Django/Unfold administration, and default infrastructure adapters.
