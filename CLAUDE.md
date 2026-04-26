# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Construction-app is an AI-assisted construction lifecycle monitoring tool for residential projects. It tracks products/units from planning through delivery, surfaces risk signals, and monitors phase progress, timeline health, and quality issues.

## Current State

This repository is in its **initial bootstrapping phase**. As of now, only `LICENSE` and `README.md` exist. No application code, frameworks, dependencies, or tooling have been set up yet. When adding the first code, establish the tech stack, folder structure, and this file should be updated to reflect it.

## Domain Model

Core entities described in the project scope:

- **Product/Unit** — identified by lot, block, and model
- **Phase** — construction stages: foundation → structure → finishing → delivery
- **Timeline** — planned vs. actual dates per phase
- **Issue** — quality problems or blockers with resolution status
- **Milestone** — key checkpoints within a phase

## Development Branch

Active development branch: `claude/add-claude-documentation-vWk6F`

Push all changes to this branch. Never push directly to `main`.

## Commands

No build, test, or lint commands exist yet. This section should be updated as tooling is added.

## Architecture Notes

No architecture has been implemented yet. When the stack is chosen, document here:
- Frontend framework and routing approach
- Backend/API layer (if any)
- Database and ORM choice
- State management strategy
- AI/ML integration approach for risk signal detection
