# Selected Work

Business-systems architecture and implementation by **Simon Haugk**. These descriptions distinguish earlier operational work, software implementation and current development.

## FightPass

**Commercial ticketing system**

[Product website](https://fightpass.ch/)

FightPass connects event inventory, seat selection, checkout, payments, ticket delivery and admission. My work covers the architecture and implementation of these connected workflows.

The architectural problem is maintaining a consistent transaction across steps that can expire, fail or be retried:

- Seat holds coordinate availability while a purchase is in progress.
- Idempotent payment-event processing handles retries without repeating the same operation.
- Ticket identity connects an order to its admission entitlement and check-in.
- Automated tests cover application logic and browser workflows.

The focus is the interaction between inventory, payment and admission systems. The commercial source repository and operational documents remain private.

## WoosaWorks

**Internal ERP · Scrum Product Owner**

WoosaWorks was a self-funded ERP developed for internal e-commerce operations. I served as Product Owner in the Scrum context.

The work connected business requirements, product priorities and the software used in the operating business. It is an example of product ownership and process design within an existing company.

The system was used internally and was not publicly launched.

## Company OS

**Business operating architecture · In development**

Company OS is being developed to represent roles, decision rules and workflows in software and support their execution.

Its architecture separates:

- **Company model:** business structure, responsibilities, decision rights and workflows.
- **Governance:** policies, permissions and human approvals for actions that require authorization.
- **Execution:** replaceable software and AI executors and adapters.
- **Systems of record:** the systems responsible for the underlying business data.

This separation is intended to keep business rules independent of a particular agent runtime or software provider. The architecture and implementation remain in development; a connection with Build to Leave™ is planned.

## Business context: Build to Leave™ and P17

[Methodology and business context](https://ceopreneur.com/en/build-to-leave)

Build to Leave™ is my methodology for reducing the dependence of a business on its owner. P17 is the accompanying diagnostic in development.

This work concerns how knowledge, decisions and responsibility are embedded in a company. The diagnostic work includes structured inputs, data contracts, validation and report-generation workflows; development and validation are ongoing.

---

[Back to profile](README.md) · [CEOPRENEUR](https://ceopreneur.com/) · [LinkedIn](https://www.linkedin.com/in/haugk/)
