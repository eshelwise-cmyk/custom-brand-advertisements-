# Brand Context Skill

## Goal

Turn incomplete brand information into a structured context record that can drive advertising concepts without inventing facts.

## Inputs

Accept any combination of:

- brand brain or brand intelligence file;
- website copy;
- product/service description;
- offer and pricing context;
- target audience notes;
- customer research;
- existing visual guidelines;
- campaign objective;
- channel and aspect-ratio requirements.

## Process

1. Extract explicit facts.
2. Separate facts from assumptions.
3. Identify audience pains, desires, objections, motivations, and desired outcomes.
4. Identify the offer, proof, differentiators, constraints, and prohibited claims.
5. Identify existing visual assets or rules that must remain consistent.
6. Mark missing information as `unknown` instead of filling it from general knowledge.
7. Produce a compact brand context object.

## Output contract

Return:

- `brand_summary`
- `audience`
- `pains`
- `desires`
- `objections`
- `offer`
- `proof_points`
- `visual_constraints`
- `copy_constraints`
- `campaign_goal`
- `unknowns`

## Quality gate

Do not move to style mining when the audience or campaign goal is unknown unless the user explicitly accepts exploratory assumptions. Label every accepted assumption.
