# Ivory-app

This file provides guidance to Claude Code when working in this repository.

## Status

New repository with no source code yet. Update this file with build, test, and architecture notes as the project takes shape.

## Git

- Default branch: `main`, remote `origin` (https://github.com/mberrys/Ivory-app.git).
- Make changes on a feature branch; commit only when asked.

## Scope
This repo is backend only. The UI lives in a separate repo, `mberrys/ivory-ui` (private, empty placeholder so far). Do not add UI or workbench code here.

The UI should reach this backend through an API, never a shell, so sandboxing and the `local-only` guarantee stay on this side. The API contract (start, stop and stream experiment runs) is not defined yet.

## 6.0 plan
Under 6.0 Theia is proposed to be dropped and the execution base (Zed, ORX's React UI or other) is still open (decision 6, experiment X8). The UI choice is a `ivory-ui` concern; this repo's role is still to be defined. See `docs/ivory-6.0/` in https://github.com/mberrys/Ivory.
