# Anointed (Excel) Olu-Sunmboye

**Senior Full-Stack Engineer** · Lagos, Nigeria

I build production systems that carry real users and real money — AI proof-verification and anti-fraud, real-time bidding engines, fintech exchanges, multi-vendor marketplaces. Five years shipping softwa# Anointed Olu-Sunmboye

**Senior Full-Stack Engineer** · Lagos, Nigeria

I build production systems that carry real users and real money — AI proof-verification and anti-fraud, real-time bidding engines, fintech exchanges, multi-vendor marketplaces. Five years shipping software that has to stay up, including work taken over mid-flight on platforms that could not go down.

Currently founding [Ternary Technologies](https://github.com/Ternary-Technologies), an EdTech startup teaching children aged 6–18 to build with technology rather than only consume it.

---

### Decisions I'd defend in any room

**The AI advises. The server decides.** VIREL pays members to promote music, so every payout rests on proof that a real action happened — and anything that pays out gets attacked. I joined the platform after launch, with live members and money already moving. The vision model returns a score, but it never gets the final word: the server holds the hard rules and rejects on them no matter how confidently the model approved. We shipped that split after watching the model read a timestamp correctly, judge it out of range, and approve the submission anyway. Behind it, identity fingerprinting matches every new signup against existing accounts across nine independent signals.

Everything went in behind feature flags and in phases, because the one rule on a live platform is that nobody loses access while you are making it harder to cheat.

**A public certificate verification endpoint, no login required.** TekyPro's LMS issued credentials that nobody outside the platform could check — which made them worth nothing. One open endpoint turned a PDF into a claim an employer could verify in a second. Built on a 54-model relational schema serving 100+ US learners, at an 85% completion rate.

**Routing AI cost by what the decision is worth.** Birdhouse HRM runs two OpenAI models, not one: `gpt-4o-mini` for high-frequency HR chat and job descriptions, `gpt-4o` for resume screening and performance reviews. Cheap where volume lives, expensive where the stakes are. Every AI call fails open — no key, no crash.

**Idempotency keys with a 24-hour TTL on a P2P exchange.** Vybrate moves money between strangers. A network retry that double-spends is not a bug you apologise for, so the retry can't happen twice by construction.

**A three-provider fallback chain for AI vision.** AquaLens identifies a fish from a photo and returns 25 structured fields — species, habitat, edibility, danger. It calls Claude first, then Gemini, then OpenAI, because an app that dies when one provider has a bad afternoon is not a product. 97% accuracy on real-world photos.

**Server-synced countdowns in live auction rooms.** CarHubAuction resolves a bid placed at the final second the same way for every person watching, because the clock lives on the server and not in ten different browsers. Kept alive on a free tier by a 22-line cron job — the smallest and most load-bearing file in the repository.

---

### Selected work

| Project | Stack | What it is |
### Selected work

| Project | Stack | What it is |
|---|---|---|
| **VIREL** *(private — client platform)* | Express · TypeScript · MongoDB · Redis · Socket.IO · OpenAI · React Native · AWS S3 | Music-promotion platform paying real members — AI proof verification, anti-fraud, payouts. API, mobile app, admin and site |
| [CarHubAuction](https://github.com/Anointed-Excel/carhub-auction) | React · Node · MongoDB · Socket.IO · Paystack | Real-time automotive bidding with live WebSocket rooms, triple OAuth, server-synced countdowns |
| [Birdhouse HRM](https://github.com/Anointed-Excel/birdhouse-hrm) | Express · TypeScript · PostgreSQL · Prisma · OpenAI | AI-powered HR platform — resume  real members — AI proof verification, anti-fraud, payouts. API, mobile app, admin and site |
| [CarHubAuction](https://github.com/Anointed-Excel/carhub-auction) | React · Node · MongoDB · Socket.IO · Paystack | Real-time automotive bidding with live WebSocket rooms, triple OAuth, server-synced countdowns |
| [Birdhouse HRM](https://github.com/Anointed-Excel/birdhouse-hrm) | Express · TypeScript · PostgreSQL · Prisma · OpenAI | AI-powered HR platform — resume screening, ATS, performance reviews |
| [TekyPro LMS](https://github.com/Anointed-Excel/tekypro-lms) | Node · TypeScript · MySQL · Redis · Swagger | Learning platform backend, 54-model schema, public credential verification |
| [AquaLens](https://github.com/Anointed-Excel/aqualens) | React Native · Flask · PostgreSQL · OpenAI Vision | AI fish identification — three-provider fallback chain, 97% accuracy |
| [Vybrate](https://github.com/Anointed-Excel/vybrate) | React · Flutter · TypeScript · TailwindCSS | P2P currency exchange with escrow and KYC |

---

### Stack

TypeScript · React · React Native · Node.js · Express · Python (Flask) · PostgreSQL · MongoDB · Redis · Socket.IO · Prisma · Docker · Flutter · OpenAI

---

Led a four-engineer team while keeping the IC seat. Delivered CarHubAuction's frontend in four weeks against a two-month deadline.

**Open to senior engineering roles** — remote, Lagos, or relocation. [Email](mailto:anointedexcel59@gmail.com) · [LinkedIn](https://linkedin.com/in/anointed-olu-sunmboye)re that has to stay up, including work taken over mid-flight on platforms that could not go down.

Currently founding [Ternary Technologies](https://github.com/Ternary-Technologies), an EdTech startup teaching children aged 6–18 to build with technology rather than only consume it.

---

### Decisions I'd defend in any room

**The AI advises. The server decides.** VIREL is a rewards platform: money only moves when a member can prove they completed a task, and anything that pays out gets attacked. I joined after launch, with live members and real payouts already running. The vision model scores each submitted screenshot, but it never gets the final word: the server holds the hard rules and rejects on them no matter how confidently the model approved. We shipped that split after watching the model read a timestamp correctly, judge it out of range, and approve the submission anyway. Behind it, identity fingerprinting matches every new signup against existing accounts across nine independent signals.

Everything went in behind feature flags and in phases, because the one rule on a live platform is that nobody loses access while you are making it harder to cheat.

**A public certificate verification endpoint, no login required.** TekyPro's LMS issued credentials that nobody outside the platform could check — which made them worth nothing. One open endpoint turned a PDF into a claim an employer could verify in a second. Built on a 54-model relational schema serving 100+ US learners, at an 85% completion rate.

**Routing AI cost by what the decision is worth.** Birdhouse HRM runs two OpenAI models, not one: `gpt-4o-mini` for high-frequency HR chat and job descriptions, `gpt-4o` for resume screening and performance reviews. Cheap where volume lives, expensive where the stakes are. Every AI call fails open — no key, no crash.`gpt-4o` for resume screening and performance reviews. Cheap where volume lives, expensive where the stakes are. Every AI call fails open — no key, no crash.

**Idempotency keys with a 24-hour TTL on a P2P exchange.** Vybrate moves money between strangers. A network retry that double-spends is not a bug you apologise for, so the retry can't happen twice by construction.

**A three-provider fallback chain for AI vision.** AquaLens identifies a fish from a photo and returns 25 structured fields — species, habitat, edibility, danger. It calls Claude first, then Gemini, then OpenAI, because an app that dies when one provider has a bad afternoon is not a product. 97% accuracy on real-world photos.

**Server-synced countdowns in live auction rooms.** CarHubAuction resolves a bid placed at the final second the same way for every person watching, because the clock lives on the server and not in ten different browsers. Kept alive on a free tier by a 22-line cron job — the smallest and most load-bearing file in the repository.

---

### Selected work

| Project | Stack | What it is |
|---|---|---|
| **VIREL** *(private — client platform)* | Express · TypeScript · MongoDB · Redis · Socket.IO · OpenAI · React Native · AWS S3 | Consumer rewards platform — AI proof verification, anti-fraud and payouts, across API, mobile app, admin and site |proof verification, anti-fraud and payouts, across API, mobile app, admin and site |
| [CarHubAuction](https://github.com/Anointed-Excel/carhub-auction) | React · Node · MongoDB · Socket.IO · Paystack | Real-time automotive bidding with live WebSocket rooms, triple OAuth, server-synced countdowns |
| [Birdhouse HRM](https://github.com/Anointed-Excel/birdhouse-hrm) | Express · TypeScript · PostgreSQL · Prisma · OpenAI | AI-powered HR platform — resume screening, ATS, performance reviews |screening, ATS, performance reviews |
| [TekyPro LMS](https://github.com/Anointed-Excel/tekypro-lms) | Node · TypeScript · MySQL · Redis · Swagger | Learning platform backend, 54-model schema, public credential verification |
| [AquaLens](https://github.com/Anointed-Excel/aqualens) | React Native · Flask · PostgreSQL · OpenAI Vision | AI fish identification — three-provider fallback chain, 97% accuracy |
| [Vybrate](https://github.com/Anointed-Excel/vybrate) | React · Flutter · TypeScript · TailwindCSS | P2P currency exchange with escrow and KYC |

---

### Stack

TypeScript · React · React Native · Node.js · Express · Python (Flask) · PostgreSQL · MongoDB · Redis · Socket.IO · Prisma · Docker · Flutter · OpenAI

---

Led a four-engineer team while keeping the IC seat. Delivered CarHubAuction's frontend in four weeks against a two-month deadline.

**Open to senior engineering roles** — remote, Lagos, or relocation. [Email](mailto:anointedexcel59@gmail.com) · [LinkedIn](https://linkedin.com/in/anointed-olu-sunmboye)
