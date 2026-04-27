# Agent Guardrail Lab

An interactive, single-file web app inspired by the trend: **"An AI agent deleted our production database. The agent's confession is below"**.

## What it is

Agent Guardrail Lab is a deterministic incident simulator. You configure an AI agent's environment (autonomy, tooling quality, observability, guardrails like approvals/backups/sandbox), then run a simulated production incident and see how outcomes can shift from "saved" to "catastrophe".

## Features

- Scenario templates (safe rollout, ops pressure, startup speed, tool chaos, red team)
- Guardrail toggles: approvals, read-only defaults, dry-run mode, verified backups, sandbox
- Deterministic seeds for reproducible runs + share links
- Step-by-step simulation or fast-forward
- Narrative incident log with tagged events
- Risk gauge + outcome history chart
- Export a markdown run report

## Trend source

https://twitter.com/lifeof_jer/status/2048103471019434248

## Live demo

https://joho777.github.io/ai-app-2026-04-27/
