# Engineering Portfolio Index

This repository is the landing page for my public engineering work. The repository name is legacy; the content below is the intended entry point.

I come from hands-on diagnostics and field technical work on complex physical systems. My current independent engineering work extends the same method - reproduce the failure, isolate the boundary, gather evidence, verify the fix - into Linux systems, embedded devices, APIs, and AI-assisted engineering workflows.

## Start here by role

| If you are evaluating... | Start with | What it demonstrates |
|---|---|---|
| Systems integration / validation / field systems | [HomeLab Core](https://github.com/EvgenVLG/homelab-core) + [Marinka](https://github.com/EvgenVLG/Marinka-assistant) | Linux operations, networking, hardware/software boundaries, observability, controlled verification |
| AI enablement / agentic workflows | [Production Zoo](https://github.com/EvgenVLG/production-zoo) | bounded AI workers, Git worktrees, review gates, model/tool routing, recovery, evidence-driven acceptance |
| API / authorization / trustworthy AI integration | [The Nest](https://github.com/EvgenVLG/the-nest-runtime) | deterministic identity/policy/capability boundary, typed outcomes, HTTP/SQLite reference path |
| Embedded / voice / edge integration | [Marinka](https://github.com/EvgenVLG/Marinka-assistant) | ESP32-S3 endpoint R&D, server/device partitioning, telemetry, OTA/recovery work |
| Linux / self-hosted operations | [HomeLab Core](https://github.com/EvgenVLG/homelab-core) | service composition, DNS/reverse proxy, remote access, monitoring, automation, runtime/secret boundaries |

## Public projects

### Production Zoo
A controlled AI-assisted engineering production workflow. Human-owned task definition and release decisions; bounded workers for research/implementation/review; verification tied to the actual claim.

Recent public case study: [Read-only should not mean blind](https://github.com/EvgenVLG/production-zoo/blob/main/docs/case-studies/read-only-reviewer-not-blind.md).

### The Nest
A deterministic authority layer for physical/connected environments. AI can interpret intent; identity, policy, capabilities, execution, and evidence stay deterministic.

### Marinka
A portable assistant runtime plus active private R&D around an ESP32-S3 audio endpoint, server-side speech processing, telemetry, wake-word evaluation, and safe OTA recovery.

### HomeLab Core
The Linux/container environment used to operate and test surrounding services. The public repository is sanitized; current architecture and operational work are documented without publishing credentials or private topology.

## Engineering approach

Across these projects I use the same discipline:

1. define the boundary and likely failure modes;
2. reproduce the problem under controlled conditions;
3. distinguish activity from useful progress;
4. collect evidence at the layer that can actually prove the claim;
5. keep permissions and trust explicit;
6. verify recovery paths, not only the happy path;
7. separate what the public artifact proves from what remains private R&D.

## Current focus - October 2026

- hardware/software integration and observability for a streamed ESP32-S3 audio endpoint;
- signed A/B OTA and recovery behavior;
- server-side voice/wake experimentation using long real-room captures;
- multi-model reviewer/tool permission boundaries;
- Linux service integration and operational reliability;
- deterministic authority/evidence contracts for AI-connected physical systems.

These are independent engineering projects, not claims of paid enterprise software tenure.
