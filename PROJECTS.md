# Selected Work

Selected engineering and systems-architecture work by **Simon Haugk**. These are public-facing summaries, not open-source releases. The underlying commercial repositories remain private.

---

## FightPass

**Event ticketing and transaction infrastructure** · Implemented product

[Product website](https://fightpass.ch)

FightPass is a ticketing platform for combat-sports events, designed around real operational constraints rather than a static ticket checkout.

**Problem:** Sell assigned seats without double-booking, synchronize availability, collect payments and support admission at the venue.

**System scope:**
- Seat selection with time-limited holds and concurrency controls.
- Checkout and payment-event reconciliation with idempotent processing.
- Digital tickets, QR-based admission and protection against duplicate check-ins.
- Automated testing and release/operational controls.

**Engineering considerations:** transactional consistency, failure recovery, user experience across devices and end-to-end verification.

**Evidence boundary:** The production-facing product can be inspected via the link above. Source code, deployment details, customer information and internal runbooks are private. This summary does not imply published service-level or revenue metrics.

---

## P17

**Structured business diagnostics** · In development and validation

[CEOPRENEUR — Diagnostic](https://ceopreneur.com/en)

P17 is part of the Build to Leave™ work around owner dependency: the extent to which a business depends on its founder for decisions, relationships, knowledge and execution.

**Problem:** Turn an ambiguous organizational risk into a structured, repeatable diagnostic process and a usable decision basis.

**System scope:**
- Diagnostic inputs and structured data contracts.
- Consistent interpretation and report-generation pipelines.
- Validation, configuration controls and traceable results.

**Engineering considerations:** reproducibility, separation of measurement from interpretation, and prevention of fabricated or unsupported evidence.

**Evidence boundary:** This work is not presented as an open-source tool or as a completed, independently validated diagnostic instrument. The underlying models, configurations and customer data remain private.

---

## Company OS

**Business operating architecture and controlled agent execution** · Ongoing development

Company OS explores how organizational policy, business logic and software execution can be modeled separately from any specific AI agent, SaaS provider or runtime.

**Problem:** Business processes become hard to transfer when their logic lives in a founder's head, a collection of prompts or a specific vendor's automation.

**Architectural principles:**
- Explicit company model, roles, decision rights and policy boundaries.
- Separation of governance from execution.
- Replaceable executors and adapters, with durable systems of record.
- Human approvals, auditability and observable runtime behavior.

**Engineering considerations:** permission boundaries, idempotency, controlled automation and operational recoverability.

**Evidence boundary:** This is an architecture and implementation program, not a claim that every component is production-complete. Repositories, credentials, network design and operational documents remain private.

---

## Build to Leave™

**Business-systems framework** · Developed by Simon Haugk

[Framework and business context](https://ceopreneur.com/)

Build to Leave™ connects these technical projects to a commercial objective: creating companies that depend less on their owners. The framework is distinct from the software projects above.

---

**Disclosure principle:** No client code, confidential business data, secrets or private architecture documents are published here. Where precise performance evidence is unavailable for publication, no figures are invented.
