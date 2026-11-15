# DTSIM

**Digital Transcription Software Intelligence Module** — part of [Site Security OPS](https://site-security-ops.sitesecurityops.workers.dev)

DTSIM is a forensic software overlay for sites that already run separate video and access-control systems. It connects to the Video Management System (VMS) and Access Management System (AMS) a site already operates, merges camera footage with access events, and builds a single chronological forensic picture. It is designed to run on local compute with a zero-footprint, volatile-memory execution model.

This repository contains the DTSIM Technical Blueprint, which outlines the system architecture, operational workflow, compliance model and module design.

## Core Capabilities
- AI-assisted event querying (Intel Prompter)
- Correlation of access logs and camera feeds into one timeline
- In-memory forensic timeline generation and investigation packs
- Forensic Detail Mode and Privacy-First Log Masking
- Zero-residual, volatile-memory execution model (design goal)
- Hardware-bound, plug-and-play deployment, or online connection by subscription
- Privacy-aligned design, with the NZ Privacy Act (IPP3A) as the target baseline

## What This Repository Contains
- `index.html` — the DTSIM Technical Blueprint
  - Architectural overview
  - Operator workflow and module breakdown
  - Forensic workflow design
  - Compliance and security considerations
  - Place within Site Security OPS (OPS-Access)

## Purpose of This Repository
This blueprint serves as:
- a technical reference
- a portfolio artifact
- a copyright placeholder
- a foundation for future development
- an investor-facing architectural overview

## Status
DTSIM is in the prototype phase. The demo pipeline is complete, including the Intel Prompter, Camera Module and Case Forensic Timeline. Live integration with real VMS and AMS systems is in progress.

Compliance and security properties described in the blueprint are design targets. They are not certifications, and independent testing and audit are still to come.

## Roadmap
- VMS/AMS ingestion bridge (live integration)
- Expanded forensic automation
- Hardware-bound deployment package
- Multi-module intelligence orchestration
- DTSIM Pulse — a reporting lens that shows a site's busiest and quietest timeframes and where department activity collides, unlocked with a DTSIM purchase

## Licence
See `LICENSE`.
