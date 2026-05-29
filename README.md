# David Ajudua

**I build the software that runs my businesses — then run the businesses on it.**

Founder and engineer. I design, ship, and operate production systems end-to-end: the
backend services, the payment and operations tooling, the deploy pipeline, and the day-to-day
program management that keeps it all running. I care less about code as a craft object and more
about code as **leverage** — the smallest reliable system that turns a manual, error-prone process
into something that runs itself.

CS @ Howard University (Class of 2029) · based in the U.S.

---

### What I build

- **Operations automation** — production services that take real, money-touching workflows
  (issuing and distributing cards, processing payouts, fetching verification codes) and make them
  one-click and auditable.
- **Internal platforms** — a shared-core service fleet where each new tool reuses the same router,
  database, logging, and process-management layer, so shipping the *next* automation is hours, not days.
- **Developer & systems tooling** — idempotent automation with full rollback, structured logging,
  and "preview-before-apply" safety on anything that changes a live system.

### How I work (the program-management half)

- **Ship in tight loops.** Staged deployment — feature branch → staging → live — with code review
  as a merge gate. Money-touching logic gets tests *first*.
- **Manage risk explicitly.** Idempotent installers, dual rollback snapshots, secrets kept out of
  version control, partial-failure handling so a batch of 50 doesn't die on item 3.
- **Run parallel workstreams.** I coordinate multiple concurrent projects through a dashboard +
  intake → triage → graduate pipeline, so nothing stalls and nothing gets silently dropped.
- **Decide on trade-offs, not preferences.** Every non-obvious choice has a documented *why*.

---

### Selected work

| Project | What it is | Why it matters |
|---|---|---|
| [LowLatencyToolkit](https://github.com/davidajudua/LowLatencyToolkit) | Modular PowerShell toolkit that applies & **rolls back** Windows performance profiles | Idempotent, dual-safety-net systems automation with a documented reason behind every change |
| [cardslinger](https://github.com/davidajudua/cardslinger) | Discord-native system for issuing single-use cards to a team, one at a time | Reliable distribution with consumption tracking, admin controls, and a full audit log |

*More case studies are in progress as I bring private operational systems into the open in
sanitized form.*

---

### Tech I reach for

`Node.js (ESM)` · `Python` · `PowerShell` · `SQLite` · `Docker` · `PM2` · `Discord API` ·
`payments / fintech APIs` · `TDD` · `staged deploys`

### Connect

- Site — [davidajudua.github.io](https://davidajudua.github.io)
- Reach me through the contact page on the site above.
