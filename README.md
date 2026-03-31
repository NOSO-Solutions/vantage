# VANTAGE

**Open source shadow AI governance for small and mid-size businesses.**

VANTAGE answers three questions:

- What AI tools are running in your organization?
- Who is using them?
- What data are they touching?

---

AI tools already exist in your organization.
They're probably being used as you're reading this.
ChatGPT. Claude. Grammarly. Copilot.

As the tools become more affordable and more accessible,
they become harder to govern.

The problem isn't the use of AI.
It's knowing which tools, which teams, and what data is involved.

That gap is a governance problem.
In the next few years, it becomes a compliance problem too.

Enterprise platforms exist to help solve this.
They're priced and scoped for enterprise teams.

VANTAGE is built for everyone else.
Lightweight. Simple. Open source.

---

## What VANTAGE Does

A structured, auditable inventory of every AI tool in use.
Each record captures four things:

**Identity** — what the tool is, who makes it, what it does

**Ownership** — who owns it, which department, Authorized or Unauthorized

**Data Exposure** — what it touches: customer PII, employee records,
financial data, IP, or nothing sensitive

**Risk Signal** — a simple Low / Medium / High flag based on
authorization status and data exposure. Your team overrides it.
Your team makes the call.

---

## What VANTAGE Is Not

- Not a network scanner
- Not automated AI detection
- Not a full compliance platform

Structured visibility through intentional human input.
The humans stay in the loop. That's the point.

---

## Tech Stack

- Frontend: React (Vite) + Tailwind CSS
- Backend: Node.js + Express
- Database: Supabase or SQLite (MVP)
- License: MIT

---

## Status

**Pre-release. Architecture and documentation phase.**

The repo is public because the architecture story is worth sharing before the code ships.
See `/docs` for the full picture.

---

## Documentation

- [Architecture](docs/architecture.md)
- [Data Model](docs/data-model.md)
- [MVP Scope](docs/mvp-scope.md)
- [Market Context](docs/market-context.md)
- [Roadmap](docs/roadmap.md)

---

## Contributing

MIT license. Contributions welcome once MVP ships.
See [CONTRIBUTING.md](CONTRIBUTING.md).

---

**Built by [NOSO Solutions](https://github.com/NOSO-Solutions)**
