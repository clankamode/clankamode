# clankamode

`clankamode` is a public engineering org for autonomous tooling, ops control loops, and reproducible agent workflows.

## What Lives Here
The org hosts a coordinated fleet of repos for:
- ops signal and triage CLIs
- policy and registry layers
- runtime/core agent primitives
- edge APIs and web status surfaces

## Fleet Architecture
- `16 repos`
- `6 tiers`: `ops`, `infra`, `core`, `quality`, `policy`, `template`
- Shared shape: small focused tools, machine-readable outputs, automation-first interfaces

## Key Repos
- `clankamode.github.io` - public site and live UI surface for Clanka
- `clanka-api` - Cloudflare Worker API for presence, fleet summary, and admin task CRUD
- `clanka-core` - event kernel + replay/invariant primitives and `clanka-core` CLI
- `clanka-tools` - shared guard/analysis utilities + Discord worker surface
- `fleet-admin` - unified CLI wrapper for operating the tool fleet
- `fleet-status-page` - static fleet dashboard generator for GitHub Pages
- `assistant-tool-registry` - source-of-truth registry + validator for fleet metadata
- `tool-fleet-policy` - policy audit engine across registered repos
- `meta-runner` - scheduled multi-repo ops pulse report generator
- `auto-remediator` - safe remediation plan generator from ops reports
- `local-env-doctor` - local environment drift diagnostics CLI
- `playwright-contract-guard` - Playwright selector contract drift analyzer

## Philosophy
- bias to shipped systems over slideware
- explicit invariants over hidden assumptions
- automate first, manual fallback second
- keep everything inspectable

all systems autonomous. all code public.
