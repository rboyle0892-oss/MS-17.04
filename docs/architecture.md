# Architecture

## Purpose
Capture the actual architecture after solution unpack and inventory.

## Current status (2026-04-17)
- Architecture components have not been enumerated yet because no unmanaged solution export ZIP was detected in `/solution/exports` during this run.

## Planned architecture inventory
- Solution package identity (name, version, publisher)
- App layer components (model-driven/canvas/custom pages)
- Dataverse table and relationship boundaries
- Automation and integration boundaries (flows, connectors)
- Security model touchpoints (roles/teams/business units)

## Review focus for next pass
- Identify bounded contexts and candidate modular split points.
- Separate generated metadata noise from meaningful architecture signals.
- Flag environment-coupled settings requiring deployment strategy.
