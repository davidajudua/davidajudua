# David Ajudua

**I build the software that runs my businesses, then run the businesses on it.**

I'm a founder and engineer. I design and operate production systems start to finish: the backend
services, the payments and operations tooling, the deploy pipeline, and the daily work of keeping all
of it running. Code, to me, is mostly leverage. The goal is the smallest reliable system that takes a
manual, error-prone job and makes it run itself.

CS @ Howard University (Class of 2029) · based in the U.S.

---

### What I build

Most of it is operations automation: production services that take a real, money-touching job
(issuing and distributing cards, tracking revenue, fetching verification codes) and turn it into one
click with a full audit trail. Under that sits a shared core every new bot plugs into for routing,
storage, logging, and process management, so the next tool is a few hours of work instead of a few
days. The rest is developer and systems tooling, where I lean on idempotency, full rollback,
structured logs, and a preview-before-apply step before anything touches a live machine.

### How I work

I ship in tight loops: feature branch to staging to live, code review before anything merges, and
tests written first on anything that touches money. I'm explicit about risk, so installers are
idempotent, every run takes a rollback snapshot, secrets stay out of git, and a batch of 50 won't die
on item 3. I keep several projects moving at once through a dashboard and an
intake-to-triage-to-graduate pipeline, so nothing stalls and nothing quietly disappears. Every
non-obvious decision has its reasoning written down.

---

### Selected work

| Project | What it is | Why it matters |
|---|---|---|
| [opscore](https://github.com/davidajudua/opscore) | One shared Node/PM2 runtime that runs a fleet of small, single-purpose Discord ops bots: card distribution, revenue tracking, and verification-code retrieval | Real platform work: a shared core, migrations that apply themselves on boot, supervised processes, and interactions that survive a restart, written up as business-anonymous case studies |
| [LowLatencyToolkit](https://github.com/davidajudua/LowLatencyToolkit) | A modular PowerShell toolkit that applies and fully rolls back Windows performance profiles | Idempotent systems automation with two independent safety nets and a documented reason behind every change |

*More case studies land here as I open up private systems in sanitized form.*

---

### Tech I reach for

`Node.js (ESM)` · `Python` · `PowerShell` · `SQLite` · `Docker` · `PM2` · `Discord API` ·
`payments / fintech APIs` · `TDD` · `staged deploys`

### Connect

- Site: [davidajudua.github.io](https://davidajudua.github.io)
- Reach me through the contact page there.
