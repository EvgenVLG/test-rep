# Independent engineering portfolio — November 4, 2026

## The 30-second overview

I bring a diagnostics-first engineering approach from complex physical systems to Linux, embedded electronics, API integration and AI-assisted software development. The core method is consistent: **reproduce the defect, isolate the boundary, gather evidence, verify the fix, and never confuse activity with completion.**

The most recent project is a **self-hosted, multi-agent AI engineering Farm**. It coordinates Git-submitted work through a durable scheduler, one Foreman, specialist workers, isolated task worktrees, executable tests and an independent reviewer. It exposes live task state and keeps release ownership separate from model-generated output.

This is an **actively evolving private experimental system**, not a claim that a public beta provides every private runtime capability.

## Where to start

| Area | Public project | Evidence |
|---|---|---|
| AI engineering / developer productivity | [Production Zoo](https://github.com/EvgenVLG/production-zoo) | [November Farm architecture, E2E results, limitations](https://github.com/EvgenVLG/production-zoo/blob/main/docs/architecture/november-2026-private-farm.md) |
| Linux / infrastructure / observability | [HomeLab Core](https://github.com/EvgenVLG/homelab-core) | [Sanitized host and AI-stack snapshot](https://github.com/EvgenVLG/homelab-core/blob/main/docs/NOVEMBER_2026_ENGINEERING_SNAPSHOT.md) |
| Portable speech / embedded integration | [Marinka](https://github.com/EvgenVLG/Marinka-assistant) | ESP32-S3 and server-side voice pipeline R&D; public keyless assistant reference |
| Deterministic authority / physical AI | [The Nest](https://github.com/EvgenVLG/the-nest-runtime) | Identity, policy, capability, execution and evidence boundary |
| Cross-device UI / wearable experiments | [Workshop](../Workshop/README.md) | Browser-to-mobile structured data and heads-up display prototypes |

## What changed recently

1. **Multiple model providers:** 11 selected model routes exercised through direct API and Git-backed acceptance paths (Nov 1).
2. **Delegated execution:** four root slots and seven native child sessions recorded in a bounded end-to-end test (Nov 1).
3. **Review and fault recovery:** independent reviewer verdicts drive a constrained rework process instead of being silently overridden (Nov 3).
4. **Tool isolation:** a real model-invoked shell task was executed under restrictive Docker limits and independently reviewed (Nov 2).
5. **Operational accountability:** current processes and task-state receipts checked on the private Ubuntu host (Nov 4).
6. **Single management authority:** one Foreman coordinates work; formal acceptance and release gates remain independent.

The project has visible paused, blocked and owner-gated tasks. Those states are evidence of how it handles uncertainty, **not** completed deliverables. Public reference tests are intentionally separate from private runtime claims.

## My engineering responsibilities

Defining system architecture and boundaries, selecting and evaluating tools, defining evidence/acceptance criteria, investigating failures, validating fixes, integrating hardware/software components, and owning release decisions. AI workers accelerate the work; they are not the owner of its quality.

Projects are independent engineering R&D, not representations of paid enterprise software deployments. Private code, credentials, home topology and raw logs remain private.
