# Ad Copy and Layout Skill

## Goal

Design image compositions that leave usable space for headlines, supporting copy, logos, offers, and calls to action.

## Process

1. Identify the required copy hierarchy before generating the image.
2. Choose a copy-safe zone: left, right, top, bottom, or center depending on the campaign.
3. Ask the image prompt to preserve that zone as intentional negative space.
4. Keep the focal subject away from required text areas.
5. Generate the image without relying on model-rendered typography unless typography generation is a deliberate part of the provider workflow.
6. Add final text in the design layer where possible.
7. Check readability at the actual placement size.

## Layout fields

- `headline_zone`
- `support_zone`
- `logo_zone`
- `cta_zone`
- `focal_zone`
- `safe_margin`
- `aspect_ratio`

## Quality checks

Reject an image when the intended copy zone is visually noisy, the focal subject collides with the text area, or the composition cannot support the required hierarchy.
