---
title: OPfN Wiki
excerpt: Explorations of key concepts involved in the OPfN Pallas project
---
This is a wiki-style knowledge-management system intended to help clarify [OPfN](https://vaporware.network)'s Pallas Operating Function. It is intended to be explored organically as your interest leads you, by clicking on linked articles and exploring [[backlinks]].

- **TODO: At the moment, most of the documents are more like simple "definitions". Ideally they would be more like short discussions and explanations (like the below) with links between each other as relevant.**
- **TODO**: the below needs a reference to [[solid-state interpreter|SSI]]

---

[[Pallas]] is a [[free]] and [[open source]], [[distributed]] [[operating function]] designed for use by individual people, not corporations. It is our belief that a personal internet, composed of [[personal server]] computers entirely owned by normal people, is both possible and desirable.

Pallas runs on the [[Plunder]] [[virtual machine]]. Plunder is a [[solid-state interpreter]]: a [[programming environment]] which combines [[orthogonal persistence|automatic orthogonal persistence]], [[functional programming]], and [[homoiconicity]]. Imagine an [[exokernel]]-like Scheme [[lisp machine]] with automatically persisted application state, and you’re not far off the mark. Plunder and Pallas are not the same project, but share some of the same long term goals; Pallas is the first third-party developer to adopt the Plunder software stack.

The main pieces of the Pallas system are:

- [[PLAN]]: the [[data model]] and [[graph reduction]] system of Plunder
- [[Sire]]: a functional language, [[bootstrap|bootstrapped]] from PLAN
- [[cog|Cogs]]: a [[microservices]] architecture for development of [[user space]] applications and [[appliances]]
- [[runtime]]: the environment on the [[host OS]] in which Pallas runs