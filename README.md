# Antonio — `@27te`

**Backend engineer.** I build production SaaS in TypeScript: Fastify APIs, PostgreSQL/Prisma data layers, containerized deploys and CI. Most of my work is in electronic invoicing and document automation for the Peruvian market (SUNAT).

Currently building [Clainev](https://clainev.com), a small product studio.

---

### What I work with

**Backend** · TypeScript · Node.js · Fastify · Prisma · PostgreSQL · Zod · Vitest
**Infra** · Docker · GitHub Actions · Railway · OpenAPI
**Frontend** · Astro · Next.js · React · Tailwind
**Also** · Go · Lua · SQL

---

### What I'm building

**Emitiva** — Electronic invoicing SaaS for SUNAT *(private, commercial)*
Multi-tenant Fastify + TypeScript API. Typed error layer, auth middleware, plan-based billing, XML signing and SUNAT integration. ~50 test files, OpenAPI spec, Dockerized with a production compose setup and CI on every push.

**Firma Segura** — Document analysis platform *(private, commercial)*
Next.js app over a Fastify API with a provider-agnostic AI layer: one interface, three interchangeable backends (Anthropic, Gemini, Groq) with schema-validated responses, so a provider outage or a pricing change is a config edit rather than a rewrite.

*Happy to walk through either codebase in an interview.*

---

### Open source

**[backend-devops](https://github.com/27te/backend-devops)** — Backend & DevOps handbook
Long-form technical documentation I wrote on API design, security, caching, queues, observability and testing. Astro Starlight, deployed via Actions.

**[27nvim](https://github.com/27te/27nvim)** — Neovim configuration
A modular, fast Neovim setup for full-stack and systems work. Native on Windows and Linux.

**[winshell](https://github.com/27te/winshell)** — Terminal environment manager for Windows
Written in Go. Manages shell profiles and tooling across environments.

---

### How I approach things

I care about the parts that show up six months later: typed boundaries, tests that describe behavior instead of implementation, migrations that roll back cleanly, and READMEs that explain *why* rather than *what*. I'd rather ship one service that holds up under load than five that demo well.

📍 Peru · 🌐 [clainev.com](https://clainev.com)
