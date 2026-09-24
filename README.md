# FOG-GLASSES-001

A tiny, local, browser-executable instrument for inspecting uncertainty without collapsing it into a verdict.

## Core law

> The glasses may change what you can distinguish. They may not change the world to make it easier to see.

## What it preserves

- Fog is not a topological wall. A route may still exist while visibility degrades locally.
- Fog has an address.
- Fog has composition, grain, depth, motion, persistence, response, and unresolved origin.
- Candidate-set size is not probability, truth, ranking, or evidentiary weight.
- A lamp is an investigative operation, not an answer.
- The caddy routes possible lamps; it does not select a belief.
- A lens controls how the same evidentiary state is experienced.
- Intuition may route a lamp, but intuition is not itself evidence.
- Failed illumination still leaves a receipt.
- More evidence may expose new fog or increase conflict.

## Run

Open `fog-glasses.html` directly in a modern browser. No server, account, package manager, or hardware integration is required.

Use the built-in specimen, import `examples/hostile-fog.json`, or create your own addresses and lamps in the UI.

## Main objects

- `FogAddress` — where a distinction currently fails.
- `Candidate` — a live compatible possibility.
- `Receipt` — a trace, claim, observation, source, or missing/contradictory line.
- `Lamp` — a declared investigative operation that may distinguish candidate pairs.
- `Angle` — how the lamp is configured for this use.
- `Lens` — how the resulting state is rendered to the observer.
- `Illumination` — one application of a lamp at an address.
- `Delta` — before/after candidate and fog changes.

## Lenses

- **LOOK** — source-first view with minimal interpretation.
- **FOG** — foreground unresolved addresses and fog composition.
- **SPATIAL** — render candidates and distinguishability as a navigable graph.
- **OPTOMETRY** — compare two declared lenses/lamps as “better one / better two / both / neither,” without declaring a winner.
- **RAW** — inspect the data and receipts directly.

## Input shape

See `examples/hostile-fog.json`. The app accepts JSON with `addresses` and `lamps` arrays.

## Export

`Export Receipt` downloads the current session state plus illumination history as JSON. This is the durable trace.