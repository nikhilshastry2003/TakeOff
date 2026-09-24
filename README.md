# Production Readiness

Evidence-based production readiness auditor for software repositories.

Upload a GitHub repository or ZIP and get a clear answer to:

> Is this application ready for production?  
> What is stopping it?  
> What should the team fix first?

## What it does (V1)

1. **Inspects** the repository (Dockerfile, CI/CD, configs, dependencies, documentation, etc.)
2. **Collects evidence** with deterministic checks
3. **Evaluates** readiness across key categories:
   - Security
   - Docker / Containers
   - CI/CD
   - Reliability
   - Observability
   - Configuration & Environment
   - Deployment / Operations
4. **Produces findings** with severity and evidence
5. **Explains** the gaps (via AI)
6. **Generates** a prioritized remediation plan and professional report

## Core principle

**Evidence before judgment.**

Deterministic checks establish facts. AI is used only for explanation, prioritization, and remediation suggestions — never as the source of truth.

## Product boundaries (V1)

This is an **auditor and advisor**, not a deployment platform.

It does **not**:
- Deploy applications
- Provision infrastructure
- Take control of customer environments
- Act as a CI/CD or monitoring platform

It tells teams what is wrong, why it matters, what the evidence is, how serious it is, and how to fix it.

## Target users

Small software teams (roughly 1–20 engineers):
- SaaS startups
- Development agencies
- MSPs
- Product engineering teams

## Status

Early development. Focused on a fast, trustworthy V1 that can be launched and validated quickly.

---

*This repository contains the source for the Production Readiness product.*
