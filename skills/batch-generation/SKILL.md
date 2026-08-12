# Batch Generation Skill

## Goal

Build a reusable bank of advertising concepts while preserving the locked brand style.

## Batch dimensions

Vary only dimensions that are intentionally approved:

- scene;
- audience segment;
- emotional trigger;
- environment;
- subject action;
- crop/aspect ratio;
- copy-space placement;
- product prominence.

Do not vary the locked style unless the style-lock process is restarted.

## Variation syntax

The source workflow uses grouped prompt alternatives, including curly-brace variation syntax, to generate multiple related concepts from one prompt. Treat this as a provider-specific adapter. For providers without that syntax, expand the combinations before sending requests.

## Batch sizing

Create a small validation batch first. Scale only after the style remains consistent and the concepts remain useful. Prefer controlled combinatorial expansion over dozens of near-duplicate prompts.

## Asset metadata

Every generated concept should retain:

- concept ID;
- style-lock version;
- prompt version;
- scene ID;
- audience segment;
- aspect ratio;
- generation provider;
- generation date;
- approval status;
- failure reason if rejected.
