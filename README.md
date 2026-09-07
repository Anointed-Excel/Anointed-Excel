# Anointed (Excel) Olu-Sunmboye

**Senior Full-Stack Engineer** · Lagos, Nigeria

I build production systems that carry real users and real money — real-time bidding engines, AI-powered platforms, fintech exchanges, multi-vendor marketplaces. Five years shipping software that has to stay up.

Currently founding [Ternary Technologies](https://github.com/Ternary-Technologies), an EdTech startup teaching children aged 6–18 to build with technology rather than only consume it.

---

### Decisions I'd defend in any room

**A public certificate verification endpoint, no login required.** TekyPro's LMS issued credentials that nobody outside the platform could check — which made them worth nothing. One open endpoint turned a PDF into a claim an employer could verify in a second. Built on a 54-model relational schema serving 100+ US learners, at an 85% completion rate.

**Routing AI cost by what the decision is worth.** Birdhouse HRM runs two OpenAI models, not one: `gpt-4o-mini` for high-frequency HR chat and job descriptions, `gpt-4o` for resume screening and performance reviews. Cheap where volume lives, expensive where the stakes are. Every AI call fails open — no key, no crash.

**Idempotency keys with a 24-hour TTL on a P2P exchange.** Vybrate moves money between strangers. A network retry that double-spends is not a bug you apologise for, so the retry can't happen twice by construction.

**Server-synced countdowns in live auction rooms.** CarHubAuction resolves a bid placed at the final second the same way for every person watching, because the clock lives on the server and not in ten different browsers. Kept alive on a free tier by a 22-line cron job — the smallest and most load-bearing file in the repository.

---
---

### Selected work

| Project | Stack | What it is |
|---|---|---|
| [CarHubAuction](https://github.com/Anointed-Excel/carhub-auction) | React · Node · MongoDB · Socket.IO · Paystack | Real-time automotive bidding with live WebSocket rooms, triple OAuth, server-synced countdowns |
| [Birdhouse HRM](https://github.com/Anointed-Excel/birdhouse-hrm) | Express · TypeScript · PostgreSQL · Prisma · OpenAI | AI-powered HR platform — resume screening, ATS, performance reviews |
| [TekyPro LMS](https://github.com/Anointed-Excel/tekypro-lms) | Node · TypeScript · MySQL · Redis · Swagger | Learning platform backend, 54-model schema, public credential verification |
| [Vee Vill Hub](https://github.com/Anointed-Excel/vee-vill-hub) | React · Node · Supabase · Redis · Socket.IO | Three-tier marketplace — admin, manufacturer, retailer |
| [Vybrate](https://github.com/Anointed-Excel/vybrate) | React · Flutter · TypeScript · TailwindCSS | P2P currency exchange with escrow and KYC |
| [Vee Vill Hub](https://github.com/Anointed-Excel/vee-vill-hub) | React · Node · Supabase · Redis · Socket.IO | Three-tier marketplace — admin, manufacturer, retailer |
| [Vybrate](https://github.com/Anointed-Excel/vybrate) | React · Flutter · TypeScript · TailwindCSS | P2P currency exchange with escrow and KYC |retailer |
| [Vybrate](https://github.com/Anointed-Excel/vybrate) | React · Flutter · TypeScript · TailwindCSS | P2P currency exchange with escrow and KYC |
retailer |
| [Vybrate](https://github.com/Anointed-Excel/vybrate) | React · Flutter · TypeScript · TailwindCSS | P2P currency exchange with escrow and KYC |
retailer |
| [Vybrate](https://github.com/Anointed-Excel/vybrate) | React · Flutter · TypeScript · TailwindCSS | P2P currency exchange with escrow and KYC |

---

### Stack

TypeScript · React · Node.js · Express · PostgreSQL · MongoDB · Redis · Socket.IO · Prisma · Docker · Flutter · OpenAI

---

Led a four-engineer team while keeping the IC seat. Delivered CarHubAuction's frontend in four weeks against a two-month deadline.

**Open to senior engineering roles** — remote, Lagos, or relocation. [Email](mailto:anointedexcel59@gmail.com) · [LinkedIn](https://linkedin.com/in/anointed-olu-sunmboye)one and make sure LinkedIn says the same thing.
one and make sure LinkedIn says the same thing.
