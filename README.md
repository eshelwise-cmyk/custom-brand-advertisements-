# Custom Brand Advertisements

A production-oriented skill system for turning brand context into consistent, distinctive advertising concepts and image-generation prompts.

This repository is derived from the workflow described in the supplied video transcript. The transcript's core process is preserved and extended into reusable, tool-agnostic skills. The source transcript is credited in `docs/source-notes.md`.

## What it does

1. Collects brand context, audience pains, desires, offers, psychographics, and constraints.
2. Mines multiple visual directions instead of relying on a single prompt.
3. Auditions and evaluates styles against representative scenes.
4. Locks a reusable style specification.
5. Generates a structured bank of ad concepts across formats.
6. Preserves negative space and layout intent for copy, CTAs, and product placement.
7. Supports batching and variation without losing brand consistency.

## Repository structure

- `skills/brand-context/` - extract and validate brand intelligence.
- `skills/style-mining/` - explore and evaluate visual directions.
- `skills/style-lock/` - turn a selected direction into a reusable style contract.
- `skills/ad-concept-generation/` - create audience-specific advertising scenes.
- `skills/batch-generation/` - expand approved concepts into controlled variants.
- `skills/ad-copy-layout/` - plan text-safe composition and placement.
- `skills/quality-control/` - detect generic, off-brand, repetitive, or unusable outputs.
- `schemas/` - machine-readable contracts for brand context, style locks, and ad concepts.
- `examples/` - fictional examples that demonstrate the workflow without exposing private brand data.
- `docs/` - workflow, attribution, limitations, and implementation notes.

## Source and attribution

The implementation is based on a user-supplied transcript. The transcript describes a Claude skill + Midjourney workflow involving brand context, style-reference exploration, style weights, stylization, image references, curly-brace prompt variations, and a reusable image bank. See `docs/source-notes.md` for the source-derived portions and the additions made for this repository.

## Scope

This project is a skill and workflow repository. It does not claim to reproduce any proprietary software, hidden model behavior, or undocumented API. Provider-specific syntax should be validated against the current provider documentation before production use.

## License

MIT. See `LICENSE`.
