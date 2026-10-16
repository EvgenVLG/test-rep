# Workshop — Pocket & Heads-Up Display

> **Status: Experimental prototype.** This is a public project overview, not a certified hardware release or a production-ready app.

[← Engineering Portfolio](../README.md) · [Versions & milestones](versions/README.md)

## Overview

**Workshop** explores ways to move concise, actionable technical information from a browser or phone onto a compact, glanceable interface, including a smart-glasses-style HUD.

It combines two related workstreams:

- **Workshop Pocket:** structured browser capture and an iPhone-oriented viewer for portable notes, checklists and inspection packets.
- **Workshop HUD:** portable cards, navigation and display adapters for wearables or a simulated heads-up display.

These components are developed as one logical product family, not separate root folders for every experiment.

## Engineering goals

- A device-independent data contract that separates source content, transport and display.
- Short technical cards, steps and checklists suitable for hands-busy work.
- Browser-to-mobile workflows and simulator-first usability experiments.
- Privacy-conscious data handling and reproducible interface/contract tests.

## Validation boundaries

Browser and phone prototypes, a synthetic HUD simulator, and shared-contract experiments exist in private development. This public overview does **not** claim successful end-to-end operation on commercial smart-glasses hardware, certified integration, background notifications, or production Slack/Telegram delivery.

Such integrations require separate platform testing, access permissions and acceptance evidence.

## One project, versioned releases

Workshop has one public root. Code evolution should be tracked through Git history, tags and release notes — not dozens of copied source trees named v01, v02 and v06. See [versions/README.md](versions/README.md).

The private development environment contains experimental branches and fixtures. They are not published wholesale: source, auth configuration and personal/household details must be reviewed and sanitized before any future public code release.

## Scope

Personal engineering R&D in cross-device interfaces, software/hardware boundaries, structured information transfer and test-driven prototyping. Product and release decisions remain human-owned.
