# Marcio Viana Junior

**QA Engineer · Founder & Tech Lead @ MVX Automação e Tecnologia**
São Paulo, Brazil · Remote / Hybrid · English C1 · [LinkedIn](https://www.linkedin.com/in/marcio-viana-junior-75647b18/)

I test software the way an auditor reads a ledger: assume the numbers are wrong until something proves them right.
15+ years in finance and audit, now building — and breaking — my own SaaS products.

---

## Products I build and test

| Product | What it is | Quality highlights | Case study |
|---|---|---|---|
| **Nvendas** | Multi-tenant WhatsApp sales automation: lead → payment → delivery → invoice | 75 domain tests · 13 SQL tenant-isolation assertions · idempotent webhooks · failure simulator | [nvendas-case-study](https://github.com/msvjr/nvendas-case-study) |
| **Toaki.vip** | Collaborative photo album for parties and event venues | Serverless on Cloudflare · Pix/card checkout · AI moderation with human review queue | [toaki-case-study](https://github.com/msvjr/toaki-case-study) |
| **Direito.club** | AI assistant on WhatsApp for law firms, integrated with ADVBOX | Identity check before any case data · per-firm isolation · prompt-injection test suite | [direito-club-case-study](https://github.com/msvjr/direito-club-case-study) |

`TypeScript` `Node.js` `PostgreSQL` `Cloudflare Workers / D1 / R2` `Docker` `WhatsApp Cloud API` `Claude API` `Asaas` `InfinitePay` `PayPal` `Secret Manager`

## QA portfolio

| Repo | What it shows |
|---|---|
| [conduit-e2e-playwright](https://github.com/msvjr/conduit-e2e-playwright) | UI + API automation in Playwright/TypeScript, Page Object Model, API-seeded test data, CI on GitHub Actions |
| [petstore-api-tests](https://github.com/msvjr/petstore-api-tests) | Postman collection run by Newman in CI: CRUD, negative and lifecycle checks |
| [qa-documentation](https://github.com/msvjr/qa-documentation) | Test plan, RTM, permission table, smoke checklist and bug report standard for Conduit |

## How I think about quality

- **A 200 is not proof.** A mock that always succeeds hides the failure until it shows up in production with customer money.
- **Money is a string, not a float.** And `APPROVED` is not `PAID`.
- **Isolation belongs to the database,** not to a `WHERE` clause someone might forget.
- **Every defect has a root cause** and a cheaper place where it could have been caught.

---

<sub>🇧🇷 QA Engineer com 15+ anos em finanças e auditoria, fundador da MVX. Aberto a vagas de QA Pleno/Sênior, QA Lead e Product Owner técnico.</sub>
