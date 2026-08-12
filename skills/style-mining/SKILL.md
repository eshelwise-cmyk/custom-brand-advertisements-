# Style Mining Skill

## Goal

Explore visual directions for a brand before committing to one style.

## Core rule

Do not optimize for a clever prompt. Optimize for a visual direction that is distinctive, audience-relevant, repeatable, and usable across many scenes.

## Process

1. Select 3 to 6 representative audience scenes. Include both pain-based and desire-based situations when appropriate.
2. Keep the scene intent stable while varying visual direction.
3. Generate a broad exploration set using randomized style references or the equivalent mechanism supported by the image provider.
4. Curate results using human taste and explicit criteria.
5. Reject generic, trendy-for-its-own-sake, overly literal, inconsistent, or unusable directions.
6. Select a small number of finalists.
7. Re-run finalists across unrelated scenes.
8. Record the settings that remain stable across scenes.

## Evaluation rubric

Score each direction from 1 to 5 for:

- brand fit;
- audience relevance;
- distinctiveness;
- repeatability;
- composition and copy space;
- emotional signal;
- product compatibility;
- cross-format usability.

A direction should not be locked from one attractive image alone. It must survive multiple scene tests.

## Provider adapter

The source transcript uses Midjourney concepts such as randomized style references, style-reference strength, stylization, and image references. Keep these as adapter fields rather than hard-code them into the core workflow.
