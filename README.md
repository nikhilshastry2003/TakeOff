# Production Readiness

**Know if your app is actually ready for production — with evidence.**

Upload a GitHub repo or ZIP. Get a clear readiness score, findings backed by real evidence, and a prioritized plan to fix what matters.

No vague AI opinions. No deployment platform. Just honest answers.

---

## The problem

Most small teams ship code that works... until it doesn't.

They have Dockerfiles, CI pipelines, and config files — but no clear answer to:

- Is the production image pinned?
- Are secrets leaking?
- Is there a health check?
- Can we actually recover if something fails?
- Is the app observable?

Manual review is slow and inconsistent. This product automates the first serious pass.

## What it does

1. Inspects the repository
2. Collects evidence (Dockerfiles, CI workflows, configs, docs, etc.)
3. Runs deterministic readiness checks
4. Surfaces findings with severity + proof
5. Explains why each gap matters
6. Produces a prioritized remediation plan

### Categories (V1)
- Security
- Docker / Containers
- CI/CD
- Reliability
- Observability
- Configuration & Environment
- Deployment / Operations

## Core principle

**Evidence before judgment.**

Deterministic checks establish the facts.  
AI is used only to explain findings and suggest fixes — never as the source of truth.

## What this is *not*

- Not a deployment platform
- Not a CI/CD tool
- Not infrastructure provisioning
- Not an autonomous DevOps agent

It assesses and recommends. It does not take control of your infrastructure.

## Who it's for

Small software teams (1–20 engineers):
- SaaS startups
- Development agencies
- Product engineering teams
- MSPs

## Status

Early development. Building a focused, trustworthy V1 that can be launched and validated quickly.

---

*This repository contains the source code for the product.*
